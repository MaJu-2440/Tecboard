# Landing Page - Tecboard

Esta é uma landing page inicial para a "Tecboard", uma plataforma fictícia de monitoramento de aplicações em tempo real. O projeto foi desenvolvido com foco em criar uma interface limpa, moderna e responsiva, utilizando a abordagem **Mobile-First**.

<img width="1291" height="770" alt="tecboard_thumb" src="https://github.com/user-attachments/assets/62806cf1-0d13-4edc-a9ef-f1f5b11738b3" />

## 📋 Índice

-   [✨ Funcionalidades](#-funcionalidades)
-   [🚀 Tecnologias Utilizadas](#-tecnologias-utilizadas)
-   [📂 Estrutura do Projeto](#-estrutura-do-projeto)
-   [🏁 Como Executar](#-como-executar)

## ✨ Funcionalidades

-   **Design Responsivo (Mobile-First):** O layout se adapta a diferentes tamanhos de tela, começando pelo design móvel e se ajustando a tablets e desktops (breakpoints em 768px e 1024px).
-   **Tema Dark (Padrão):** A página carrega com um tema escuro (dark mode) como padrão, utilizando uma paleta de cores moderna.
-   **CSS Variables:** O projeto utiliza variáveis CSS (`:root`) para gerenciar facilmente as cores do tema (dark/light) e fontes, facilitando a manutenção.
-   **Estrutura para Theming:** O cabeçalho já inclui um botão (`.btn-darklight-mode`) pronto para a implementação de uma funcionalidade de troca de tema (Light/Dark mode) com JavaScript.
-   **Fontes Customizadas:** Utiliza as fontes "Poppins" (para o corpo do texto) e "Unbounded" (para os títulos) via Google Fonts.

## 🚀 Tecnologias Utilizadas

-   **HTML5:** Para a estrutura semântica da página.
-   **CSS3:** Para estilização, layout e responsividade.
    -   Flexbox
    -   Media Queries
    -   Variáveis CSS

## 📂 Estrutura do Projeto

```
├── index.html # Arquivo principal da página 
├── css/ │ 
  └── style.css # Folha de estilos 
└── assets/ 
  ├── techboard-logo-dark.png 
  ├── techboard-favicon-dark.svg 
  ├── botão-light-mode.svg 
  └── celulares-desktop.png
```

## 🏁 Como Executar

Este é um projeto estático e não requer instalação.

1.  Clone este repositório:
    ```bash
    git clone (url-do-seu-repositorio)
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd (nome-da-pasta-do-projeto)
    ```
3.  Abra o arquivo `index.html` no seu navegador de preferência.
