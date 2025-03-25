# 🕒 Timer App

![React Logo](https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg)

Este é um aplicativo do IgniteTimer desenvolvido com Vite, TypeScript e ReactJS. O usuário pode definir uma atividade, escolher um tempo entre 0 e 60 minutos e iniciar a contagem.  

Na página de histórico, a atividade será exibida com o tempo decorrido e um status colorido:
- 🟢 **Verde**: Concluído
- 🟡 **Amarelo**: Em andamento
- 🔴 **Vermelho**: Interrompido

## 🚀 Tecnologias Utilizadas

- ⚡ Vite
- 🟦 TypeScript
- ⚛️ ReactJS
- 💅 Styled Components
- 📍 React Router DOM
- 🔄 useReducer e Immer
- 📜 React Hook Form + Zod (validação)
- 📆 Date-fns
- 🌍 useContext
- 🏗 useEffect

## 📂 Estrutura do Projeto
SRC
📂 ASSETS
📂 COMPONENTS
📂 HEADER
📜 index.tsx - Arquivo da Header
📜 styles.ts - Arquivo da Header
📂 CONTEXTS
📜 CyclesContext.tsx - Arqvuivo do CyclesContext
📂 LAYOUTS
📂 DEFAULTLAYOUT
📜 index.tsx - Arquivo do DefaultLayout
📜 styles.ts - Arquivo do DefaultLayout
📂 PAGES
📂 HISTORY
📜 index.tsx - Arquivo do History
📜 styles.ts - Arquivo do History
📂 HOME
📂 COMPONENTS
📂 COUNTDOWN
📜 index.tsx - Arquivo do Coutndown
📜 styles.ts - Arquivo do Countdown
📂 NEWCYCLEFORM
📜 index.tsx - Arquivo do NewCycleForm
📜 styles.ts - Arquivo do NewCycleForm
📜 index.tsx - Arquivo da Home
📜 styles.ts - Arquivo da Home
📂 REDUCERS
📂 CYCLES
📜 actions.ts - Arquivo da Cycles
📜 reducer.ts - Arquivo da Cycles
📂 STYLES
📂 THEMES
📜 default.ts - Arquivo do Themes
📜 global.ts - Arquivo da Styles
📜 App.tsx - Arquivo da SRC
📜 main.tsx - Arquivo da SRC
📜 Router.tsx - Arquivo da SRC 
📜 vite-env.d.ts - Arquivo da SRC

---

## ▶️ Como Executar

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/timer-app.git
   cd timer-app

2. Instale as dependências:
    ```sh
    npm install

3. Inicie o servidor de desenvolvimento:
    ```sh
    npm run dev

---

📌 Funcionalidades
Definir uma atividade e tempo de contagem.

Iniciar e interromper o Timer.

Histórico de atividades com status dinâmico.

---

🚀 Desenvolvido por Pedro Henrique Gouveia de Miranda Couto
[GitHub](https://github.com/PedroGouveia77) | [LinkedIn](https://www.linkedin.com/in/pedro-henrique-gouveia-590097257/)
