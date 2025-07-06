# Criador Mágico de Animação de IA 🤖✨

## Descrição

Aplicação web simples que permite ao usuário descrever uma animação desejada. Essa descrição é enviada para um webhook no **n8n**, que gera um código CSS e um preview HTML usando Inteligência Artificial. O resultado é exibido na tela em tempo real para visualização.

---

## Como funciona

- O usuário digita uma descrição da animação que deseja criar.
- O texto é enviado para o backend (webhook n8n) via requisição HTTP POST.
- O backend processa a requisição com IA e responde com o código CSS, preview HTML e estilo adicional.
- O frontend exibe o código CSS e o preview, aplicando o estilo dinamicamente.

---

## Tecnologias usadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API para comunicação HTTP assíncrona
- n8n para backend / webhook e processamento IA

---

## Estrutura do Projeto

- **index.html** — Estrutura da página, inputs e áreas para exibir o código e resultado.
- **style.css** — Estilos básicos para layout e aparência.
- **script.js** — Script para comunicação com o backend e manipulação do DOM.

---


