# Portfólio Profissional — Natan Chaves

**Aluno:** Natan Chaves de Souza  
**Curso:** Técnico em Desenvolvimento de Sistemas — ETEC  

## Descrição do Portfólio
Este projeto consiste no meu portfólio profissional desenvolvido em HTML5, CSS3 e Bootstrap 5. A página reúne minha apresentação pessoal, formação acadêmica, stack de tecnologias, nível de proficiência em habilidades técnicas, projetos práticos desenvolvidos e canais diretos de contato.

## Link do Site Publicado
Acesse o portfólio online pelo GitHub Pages:  
👉 [https://neytsinho.github.io/portfolio/](https://neytsinho.github.io/Portifolio/)

## Tecnologias Utilizadas
- **HTML5:** Estruturação semântica (`<header>`, `<nav>`, `<main>`, `<section>`, `<figure>`, `<footer>`).
- **CSS3:** Folha de estilo externa (`css/style.css`) para controle de altura de imagens, rolagem suave e animações.
- **Bootstrap 5.3 (CDN):** Sistema de grid responsivo (`container`, `row`, `col`), `navbar` fixa, `carousel`, `cards`, `badges`, `progress` e botões.
- **Devicon:** Biblioteca de ícones para exibição das linguagens e ferramentas.
- **Git & GitHub Pages:** Controle de versão e hospedagem estática gratuita.

## Funcionamento do Projeto
O site funciona como uma *Single Page Application* (página única) dividida em seções ancoradas por IDs (`#perfil`, `#habilidades`, `#projetos`, `#contato`):
1. **Menu de Navegação (`navbar`):** Fixo no topo (`sticky-top`), adapta-se automaticamente para menu hambúrguer em telas menores.
2. **Destaque (`carousel`):** Exibe três slides rotativos com transição *fade*, indicadores inferiores e botões de navegação.
3. **Perfil:** Apresenta foto circular (`rounded-circle`), resumo profissional, cards informativos e ícones das tecnologias utilizadas.
4. **Habilidades Técnicas:** Exibe barras de progresso segmentadas por área (Front-end e Back-end/IoT).
5. **Projetos:** Lista os principais sistemas desenvolvidos em cards alinhados com `h-100` e `mt-auto`, direcionando para os repositórios no GitHub.
6. **Contato e Rodapé:** Centraliza links rápidos para e-mail (`mailto:`), GitHub e LinkedIn.

## Recursos Novos Adicionados (Evolução do Projeto)
Além da estrutura base construída em aula, foram implementados os seguintes recursos:
1. **Nova Seção de Habilidades Técnicas (`#habilidades`):** Inclusão de indicadores visuais de progresso para cada tecnologia.
2. **Animações e Transições CSS (`hover` e `smooth scroll`):** Efeito de elevação nos cards e botões ao passar o cursor, além de rolagem suave entre as seções.
3. **Legendas Interativas no Carousel (`carousel-caption`):** Sobreposição de textos e botões de ação direta nos slides principais.

## Como os Recursos Foram Implementados
- **Seção de Habilidades:** Criada com uma `<section id="habilidades">` contendo cards divididos em grid (`col-md-6`) e componentes nativos `.progress` e `.progress-bar` do Bootstrap para representar percentuais de domínio.
- **Animações CSS:** No arquivo externo `css/style.css`, foi definida a propriedade `scroll-behavior: smooth` na tag `html` e criada a classe `.card-hover` utilizando `transition: transform 0.3s ease, box-shadow 0.3s ease` combinada com a pseudoclasse `:hover` (`transform: translateY(-6px)`).
- **Legendas no Carousel:** Adicionados blocos `<div class="carousel-caption">` dentro de cada `.carousel-item`, estilizados com classes utilitárias do Bootstrap (`bg-dark bg-opacity-75 rounded-4 p-4`) para garantir legibilidade sobre as imagens.