<h1>Backend-With-Node</h1>

<h2>JavaScript</h2>

- Uma linguagem de programação de alto nível, dinâmica e multiparadigma, amplamente utilizada para o desenvolvimento web.

- Permite criar desde interações simples em páginas da web até aplicações backend robustas, usando plataformas como Node.js.

- É uma linguagem de tipagem dinamica, isso significa que é uma linguagem fracamente tipada e que o tipo das variáveis é definido em tempo de execução.

- Interpretado: Não precisa de compilação prévia, sendo executado diretamente pelo navegador ou pelo Node.js.

- Multiparadigma: Suporta programação orientada a objetos, funcional e baseada em eventos.

- Assíncrono e não bloqueante: Usa callbacks, Promises e async/await para operações assíncronas, otimizando o desempenho.

<h2>Onde o JavaScript é usado?</h2>

- Frontend: Manipulação do DOM, animações, interações e frameworks como React, Vue e Angular.

- Backend: Com Node.js, é usado para criar APIs, microsserviços e aplicações escaláveis.

- Mobile: Aplicações híbridas com React Native ou Ionic.

- Desktop: Aplicações com Electron.js.

- IoT e Games: Controle de dispositivos e desenvolvimento de jogos com Phaser.js.

<h2>Node.js</h2>

- É um runtime de JavaScript baseado no motor V8 do Google Chrome, que permite executar código JavaScript no backend (fora do navegador).

- É um interpretador Javascript que roda fora dos navegadores

- Criar aplicações backend

- Programas para inteligencia artificial, ect

- Conecta banco de dados

- Executa JS fora dos navegadores.

<h2>Principais caracteristicas do Node.js</h2>

1. Single-threaded e Assíncrono: 
- Usa um único thread para lidar com múltiplas conexões simultaneamente.

- Utiliza event loop e non-blocking I/O para evitar bloqueios em operações demoradas.

2. V8 Engine
- O motor JavaScript do Google Chrome compila código JS para código de máquina, tornando-o muito rápido.

- Temos então um código JS rodando em C++ para garantir alta performace

3. Modularidade com NPM (Node Package Manager)
- Possui um enorme ecossistema de pacotes e bibliotecas para facilitar o desenvolvimento.

4. APIs Nativas
- Permite manipular arquivos, redes, processos e outras funcionalidades do sistema operacional.

<h2>Onde é que Node.js é usado?</h2>

- ✅ APIs REST e GraphQL – Frameworks como Express e NestJS.

- ✅ WebSockets e Aplicações em Tempo Real – Chat, notificações e multiplayer.

- ✅ Microservices – Arquitetura distribuída e escalável.

- ✅ Serverless e Cloud Computing – AWS Lambda, Firebase Functions, etc.

- ✅ Automação e Ferramentas CLI – Scripts, gerenciadores de pacotes e ferramentas DevOps.

<h2>Porque usar Node.Js?</h2>

1. Alta Performance ⚡
- ✔️ Baseado no V8 Engine – O código JavaScript é compilado para código de máquina, tornando a execução muito rápida.

- ✔️ Non-blocking I/O – Lida com múltiplas requisições simultaneamente sem bloquear a thread principal.

- ✔️ 10x mais requisições que php

- 📌 Ideal para: APIs de alta concorrência, aplicações em tempo real, microsserviços.

2. Assíncrono e Escalável 🔄
- ✔️ Event Loop – Gerencia operações assíncronas sem a necessidade de múltiplas threads.

- ✔️ Microservices & Serverless – Perfeito para arquiteturas distribuídas e escaláveis.

- 📌 Ideal para: Sistemas de mensageria, filas de processamento, servidores altamente disponíveis.

3. Grande Ecossistema e Comunidade 🌍
- ✔️ NPM (Node Package Manager) – Maior repositório de pacotes do mundo.

- ✔️ Frameworks e Bibliotecas – Express.js, NestJS, Socket.io, Sequelize, Mongoose, etc.

- 📌 Ideal para: Startups, times ágeis e projetos que precisam de soluções rápidas.

4. Fullstack JavaScript 🏗️
- ✔️ Backend e frontend na mesma linguagem – Facilita o desenvolvimento com frameworks como React, Vue e Angular.

- ✔️ Reaproveitamento de código entre frontend/backend.

- 📌 Ideal para: Aplicações web modernas (SPA, SSR, APIs).

5. Compatível com a Nuvem e Serverless ☁️
- ✔️ Fácil integração com AWS, Google Cloud e Azure.

- ✔️ Funciona bem com serviços como Lambda, DynamoDB, SQS e API Gateway.

- 📌 Ideal para: Redução de custos e arquiteturas elásticas.

<h2>Quando NÃO Usar Node.js?</h2>

- ❌ Aplicações com alto processamento (ex.: Machine Learning, IA) – O Node é single-threaded e pode não ser ideal para cálculos intensivos.

- ❌ Sistemas que exigem muitas operações síncronas – Pode ser melhor usar linguagens como Java ou Go em alguns casos.

<h2>O que é o NPM no Node.js? 📦</h2>

O NPM (Node Package Manager) é o gerenciador de pacotes do Node.js. Ele permite instalar, gerenciar e compartilhar bibliotecas e ferramentas para facilitar o desenvolvimento de aplicações Node.js.

<h2>Principais Funções do NPM</h2>

1️⃣ Gerenciar pacotes

- Instala, remove e atualiza dependências do projeto.

- A comunidade publica pacotes open-source que podem ser usados diretamente.

2️⃣ Gerenciar scripts

- Permite definir comandos personalizados para rodar no terminal (ex.: npm start, npm test).

3️⃣ Publicar pacotes

- Desenvolvedores podem publicar seus próprios pacotes no repositório do NPM.

<h2>Arquivos Importantes do NPM</h2>

- 📌 package.json – Contém informações do projeto e lista de dependências.
- 📌 package-lock.json – Garante que todas as máquinas usem as mesmas versões das dependências.
- 📌 node_modules/ – Pasta onde os pacotes instalados ficam armazenados.

<h2>NPM vs Yarn</h2>

- 📌 Yarn é uma alternativa ao NPM com algumas melhorias de performance e segurança. Ambos fazem a mesma coisa, e a escolha depende do projeto/time.