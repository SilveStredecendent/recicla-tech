# Projeto ReciclaTech ♻️

Landing page responsiva para a ReciclaTech, uma plataforma fictícia para doação de eletrônicos.

[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://recicla-tech-hwlq.vercel.app/)

**Confira o resultado online: [https://recicla-tech-hwlq.vercel.app/](https://recicla-tech-hwlq.vercel.app/)**

---

## Preview

![Preview da landing page ReciclaTech](./ReciclaTec%20-%20DESKTOP.jpg)

_(Dica: Se o caminho da imagem acima estiver errado, arraste um screenshot do seu projeto para cá para substituí-lo)_

---

## Sobre o Projeto

O ReciclaTech é um projeto de front-end que simula uma plataforma para conectar doadores de eletrônicos a quem precisa, visando reduzir o lixo eletrônico e promover a inclusão digital.

Este projeto foi desenvolvido para treinar e solidificar conhecimentos em desenvolvimento web, com foco especial na aplicação de uma arquitetura de estilos moderna e escalável, simulando um ambiente de desenvolvimento profissional.

## O Desafio

O desafio principal foi construir uma landing page responsiva e fiel a um design profissional, estruturando o código de forma limpa e organizada.

---

## Tecnologias Utilizadas

O foco principal foi o uso de **SASS (SCSS)** de forma profissional, com uma organização modular:

- **HTML5 Semântico:** Para a estrutura e acessibilidade da página.
- **SASS (SCSS):** Para a estilização, com uma arquitetura dividida em parciais (partials):
  - `_variables.scss`: Cores, fontes, breakpoints, etc.
  - `_base.scss`: Reset e estilos globais (body, h1, etc.).
  - `_components.scss`: Estilos para componentes reutilizáveis (botões, cards).
  - `_layout.scss`: Estilos do header, footer e grid principal.
  - `_sections.scss`: Estilos para cada seção específica da página (Hero, Stats, Products...).
  - `_responsive.scss`: Todas as media queries para responsividade.

---

## Como Rodar o Projeto Localmente

Para rodar este projeto e compilar o SASS, você precisará ter o [Git](https://git-scm.com/) e um compilador SASS (como o [Sass (Dart)](https://sass-lang.com/install)) instalados.

1.  **Clone o repositório:**

    ```bash
    git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
    ```

    _(Substitua pela URL do seu repositório)_

2.  **Navegue até a pasta do projeto:**

    ```bash
    cd nome-do-repositorio
    ```

3.  **Abra o `index.html`** no seu navegador para ver o site.

4.  **Para compilar o SASS:**
    Se você quiser fazer alterações nos estilos, você precisa "assistir" aos seus arquivos `.scss`. Use este comando no terminal:
    ```bash
    sass --watch scss/main.scss:css/style.css
    ```
    _Isso irá automaticamente compilar qualquer mudança de `scss/main.scss` para `css/style.css`._
