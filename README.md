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
 ┣ 📂 ASSETS
 ┃ ┗ 📜 logo.svg
 ┣ 📂 COMPONENTS
 ┃ ┗ 📂 HEADER
 ┃   ┣ 📜 index.tsx
 ┃   ┗ 📜 styles.ts
 ┣ 📂 CONTEXTS
 ┃ ┗ 📜 CyclesContext.tsx
 ┣ 📂 LAYOUTS
 ┃ ┗ 📂 DEFAULTLAYOUT
 ┃   ┣ 📜 index.tsx
 ┃   ┗ 📜 styles.ts
 ┣ 📂 PAGES
 ┃ ┣ 📂 HISTORY
 ┃ ┃ ┣ 📜 index.tsx
 ┃ ┃ ┗ 📜 styles.ts
 ┃ ┣ 📂 HOME
 ┃ ┃ ┣ 📂 COMPONENTS
 ┃ ┃ ┃ ┣ 📂 COUNTDOWN
 ┃ ┃ ┃ ┃ ┣ 📜 index.tsx
 ┃ ┃ ┃ ┃ ┗ 📜 styles.ts
 ┃ ┃ ┃ ┗ 📂 NEWCYCLEFORM
 ┃ ┃ ┃   ┣ 📜 index.tsx
 ┃ ┃ ┃   ┗ 📜 styles.ts
 ┃ ┃ ┣ 📜 index.tsx
 ┃ ┃ ┗ 📜 styles.ts
 ┣ 📂 REDUCERS
 ┃ ┗ 📂 CYCLES
 ┃   ┣ 📜 actions.ts
 ┃   ┗ 📜 reducer.ts
 ┣ 📂 STYLES
 ┃ ┣ 📂 THEMES
 ┃ ┃ ┗ 📜 default.ts
 ┃ ┗ 📜 global.ts
 ┣ 📜 App.tsx
 ┣ 📜 main.tsx
 ┣ 📜 Router.tsx
 ┗ 📜 vite-env.d.ts

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
