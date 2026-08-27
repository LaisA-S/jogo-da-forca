# 🔤 Jogo da Forca no Terminal (Node.js)

> Um clássico Jogo da Forca desenvolvido para ser executado diretamente no terminal utilizando Node.js e a API nativa `readline/promises`.

![NodeJS](https://img.shields.io/badge/Node.js-v18%2B-green?style=for-the-badge&logo=nodedotjs)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow?style=for-the-badge&logo=javascript)
![License](https://img.shields.io/badge/Licensa-MIT-blue?style=for-the-badge)

---

## 📌 Sobre o Projeto

Este projeto é uma implementação simples e funcional do **Jogo da Forca** via linha de comando (CLI). O tema do jogo é voltado para termos de **Desenvolvimento Web e Backend** (como `NODE.JS`, `JAVASCRIPT`, `EXPRESS`, entre outros).

O principal objetivo do projeto é demonstrar a manipulação de entrada/saída assíncrona no Node.js utilizando a API de **Promises** do módulo `readline`, além de aplicar conceitos essenciais de lógica de programação em JavaScript (arrays, laços de repetição, condicionais e manipulação de strings).

---

## 🚀 Funcionalidades

- 🎲 **Palavras Aleatórias:** Seleção dinâmica de palavras a cada nova partida.
- ⚡ **Assincronismo Moderno:** Utilização de `async/await` com a API `readline/promises` para capturar os chutes do jogador de forma fluida.
- 🔠 **Insenbilidade a Maiúsculas/Minúsculas:** O jogo converte automaticamente qualquer entrada para letras maiúsculas.
- ❤️ **Sistema de Vidas:** O jogador possui 6 vidas/tentativas. Cada erro reduz 1 vida.
- 🏆 **Condições de Vitória/Derrota:** Feedback imediato ao descobrir a palavra ou esgotar as tentativas.

---

## 🛠️ Tecnologias Utilizadas

- **[Node.js](https://nodejs.org/):** Ambiente de execução JavaScript no servidor/terminal.
- **`readline/promises`:** Módulo nativo do Node.js para interface de leitura interativa assíncrona.
- **`process` (`stdin` / `stdout`):** Manipulação dos fluxos de entrada e saída padrão do sistema.

---

## 💻 Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:
- [Node.js](https://nodejs.org/) (Versão 16.x ou superior recomendada).

---

## ⚙️ Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/LaisA-S/jogo-da-forca](https://github.com/LaisA-S/jogo-da-forca)