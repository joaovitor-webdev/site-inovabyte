# Inova Byte — Site Institucional
 
 Site institucional desenvolvido com React + Vite, apresentando serviços, portfólio, equipe e um showcase do produto GoMerce.
 
 ## Sobre

 Aplicação web responsiva com SPA (Single Page Application) que utiliza React Router, Tailwind CSS e componentes desacoplados. Inclui páginas como Home, Serviços, Portfólio, Equipe, Sobre, Contato e uma landing do GoMerce com formulário de demonstração e simulação de fluxo do usuário.

 ### Imagens do projeto

 ![Screenshot](./src/assets/images/screenshot.png)

 ### Demo

 Acesse a demo ao vivo aqui: [Link para Demo](https://inovabyte-sistemas.vercel.app)

 ## Tecnologias

 - React.js
 - Vite
 - React Router
 - Tailwind CSS (PostCSS, Autoprefixer)
 - JavaScript
 - ESLint
 
 ## Como Usar

 Opção 1 — Rodar localmente (recomendado)

 - Pré-requisitos: Node.js 18+ (ou compatível com Vite), npm ou yarn/pnpm
 - Instale as dependências:

 ```bash
 npm install
 # ou
 pnpm install
 # ou
 yarn
 ```

 - Rode em modo desenvolvimento com HMR:

 ```bash
 npm run dev
 ```

 - Acesse a aplicação no endereço indicado pelo terminal (por padrão):

 http://localhost:5173

 Opção 2 — Build de produção e pré-visualização

 ```bash
 npm run build
 npm run preview
 ```

 ## Estrutura

 - index.html: template raiz do Vite
 - src/main.jsx: bootstrap do React
 - src/App.jsx: roteamento e layout base
 - src/components: componentes de UI e layout
 - src/pages: páginas (home, services, portfolio, team, about, contact, gomerce)
 - src/assets: imagens e ícones
 - public/: estáticos servidos sem processamento

 ## Scripts

 - dev: inicia o servidor de desenvolvimento Vite
 - build: gera build de produção
 - preview: pré-visualiza a build localmente

 ## Autor

 - Nome: João Vitor - Web Dev
 - GitHub: https://github.com/joaovitor-webdev
 - Portfólio: https://joaovitor-webdev.vercel.app
