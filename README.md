# Mafia-agent
AI "Mafia" is coming! As night falls,9 ChatGPT AI players each harbor their own sinister motives. Let's see who will have the last laugh... 

Based on phaser3+vue3+typescript, and chatgpt (70% of the code is written by chatgpt).

Welcome to add stars to my project.

Welome to join my discord group. 

[![Discord](https://dcbadge.vercel.app/api/server/t2D84xMz39?compact=true)](https://discord.gg/t2D84xMz39)

https://github.com/JasonCaoCJX/mafia-agent/assets/58477254/72be8b1a-1213-44ee-8177-7dbc98d5804b

# Quick Start
This project is based on [Node.js](https://nodejs.org/en), and you can install the required dependencies by
```
npm install
# or
yarn
```

Then you need to configure your own `OPENAI_API_KEY`. You can get it from [OpenAI API Key](https://platform.openai.com/account/api-keys). It is recommended that you use a paid account, otherwise you will receive frequency restrictions during use. For details, please refer to [OpenAI rate limits](https://platform.openai.com/docs/guides/rate-limits/overview)

Set it in `src/utils/chatgpt.ts`.
```ts
const openai_api_key = "OPENAI_API_KEY"
```

Finally, run the demo
```
npm run dev
# or
yarn dev
```

Or you may want to package your project for deployment.
```
npm run build
# or
yarn build
```
