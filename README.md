# Projeto Juliana: letreiro digital dinâmico & realidade aumentada 🎂✨

Este projeto é uma aplicação web interativa criada para uma celebração especial. Ele consiste em um letreiro digital de alta performance que pode ser controlado remotamente, integrando música, animações e realidade aumentada.

## 🚀 Funcionalidades principais

- **Letreiro em tempo real:** Interface de exibição (`index.html`) que consome dados do KVDB.io continuamente.
- **Painel de controle:** Interface administrativa (`admin.html`) para gerenciar mensagens, velocidade e música.
- **Modo festa (Party Mode):** Ativado por gatilhos (ex: "te amo"), disparando confetes, música sincronizada, GIF surpresa e QR Code para AR.
- **Realidade aumentada (AR) evoluída:** Página `ar.html` com:
  - Estética "Hacker/Neon" consistente com o letreiro.
  - Barra de progresso customizada para carregamento do modelo 3D.
  - Prompt visual ("mãozinha") para facilitar a detecção de superfície.
  - Modelo 3D de bolo otimizado para Android e iOS.
- **Identidade Visual:** Favicons dinâmicos (🎂) e tema escuro unificado em todas as páginas.

## 🛠 Tecnologias utilizadas

- **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (ES6+).
- **Integrações:** YouTube API, Canvas-Confetti, Model-Viewer (Google), KVDB.io, QR Server API.

## 📁 Estrutura do projeto

- `index.html`: Exibição principal.
- `admin.html`: Painel de controle.
- `ar.html`: Experiência de Realidade Aumentada.
- `bolo.glb` / `bolo.usdz`: Modelos 3D do bolo.
- `juliana.gif`: GIF de celebração.
- `.gitignore`: Mantém o repositório limpo de arquivos de sistema e logs.

## 🕹 Como usar

1. Abra o `index.html` e clique para iniciar.
2. No `admin.html`, atualize a mensagem para "te amo".
3. Escaneie o QR Code que aparecerá no letreiro para ver o bolo em 3D na sua mesa!

---
Desenvolvido com ❤️ para uma ocasião especial.
