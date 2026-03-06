# 🌌 Universo Duna - Landing Page Interativa

Uma página web imersiva, responsiva e interativa dedicada ao épico universo de ficção científica "Duna", criado por Frank Herbert e adaptado para os cinemas por Denis Villeneuve. 

Este projeto foi construído para ser uma experiência visual atraente, utilizando animações CSS avançadas e manipulação inteligente do DOM com JavaScript.

---

## 🚀 Funcionalidades e Efeitos Visuais

O projeto não é apenas uma página estática; ele conta com diversas micro-interações e animações para imergir o usuário:

* ✨ **Fundo Estrelado Dinâmico:** Um céu estrelado infinito gerado via JavaScript, com estrelas de diferentes velocidades e durações flutuando verticalmente pelo fundo da tela.
* 🔥 **Título "Melting & Glowing":** O título principal ("DUNA") possui uma animação de brilho pulsante (Neon) e um efeito de sombra derretendo, criando uma estética sci-fi sombria.
* ⌨️ **Efeito Máquina de Escrever Inteligente:** A introdução do site é "digitada" na tela automaticamente. Usando a API `IntersectionObserver`, o efeito só é disparado quando o usuário rola a página até a seção correspondente.
* 📜 **Linha do Tempo (Timeline):** Uma interface elegante marcando os anos de lançamento e a ordem cronológica dos livros da saga.
* 🖱️ **Micro-interações de Hover:** * **Cards de Personagens:** Zoom suave na imagem ao passar o mouse.
  * **Cards de Filmes:** Painel de informações que desliza de baixo para cima ao interagir com a capa do filme.
  * **Cards de Curiosidades:** Efeito de flutuação e brilho dourado dinâmico.
* 📌 **Menu Pegajoso (Sticky Navigation):** O menu de navegação acompanha o usuário durante a rolagem da página para facilitar o acesso às seções.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando os pilares fundamentais da web, sem a necessidade de frameworks ou bibliotecas externas:

* **HTML5:** Estruturação semântica do conteúdo.
* **CSS3:** * Layouts modernos utilizando **Flexbox** e **CSS Grid**.
  * Animações contínuas (`@keyframes`).
  * Filtros (`blur`) e Tipografia externa (Google Fonts - *Cinzel*).
* **JavaScript (Vanilla):**
  * Geração de elementos dinâmicos no DOM (Fundo estrelado).
  * Lógica de temporização (`setTimeout`).
  * Observação de scroll (`IntersectionObserver`).

---

## 📂 Estrutura de Arquivos e Assets

Para que o projeto funcione perfeitamente com todas as imagens locais, certifique-se de que a estrutura de pastas do seu projeto esteja assim:

```text
/seu-projeto
│
├── index.html        # O código principal da página
├── README.md         # A documentação do projeto
└── /imagens          # Pasta contendo as imagens utilizadas
    ├── paul.png
    ├── jessica.png
    ├── leto.png
    ├── baron.png
    ├── Duna1.png
    ├── Duna2.png
    └── Duna3.png
