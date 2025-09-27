ProjetoCliente

📚 Projeto acadêmico em desenvolvimento durante as aulas.
Combina Node.js + Express no backend e React (Vite) no frontend.
⚠️ O projeto não está finalizado – novas features e ajustes serão adicionados nas próximas aulas.

📂 Estrutura Completa
projetoCliente/
│
├─ backend/                        # API Node.js + Express
│  ├─ data/
│  │  └─ dados.json                # “Banco de dados” simples
│  ├─ node_modules/
│  ├─ package.json
│  ├─ package-lock.json
│  └─ server.js                    # Servidor (porta 5001)
│
└─ frontend/                       # Interface React (Vite)
   ├─ node_modules/
   ├─ public/                       # Arquivos estáticos
   ├─ src/
   │  ├─ assets/                     # Imagens e ícones
   │  ├─ components/                 # Componentes reutilizáveis
   │  ├─ routes/                     # Páginas
   │  │  ├─ Home.jsx
   │  │  ├─ Clientes.jsx
   │  │  └─ Error.jsx
   │  ├─ App.jsx
   │  ├─ index.css
   │  └─ main.jsx
   ├─ eslint.config.js
   ├─ index.html
   ├─ package.json
   └─ vite.config.js

⚙️ Pré-requisitos

Node.js ≥ 18

NPM instalado

Verifique:

node -v
npm -v

▶️ Como Rodar o Projeto
1) Clonar o repositório
git clone <URL_DO_REPOSITORIO>
cd projetoCliente

2) Rodar o Backend
cd backend
npm install
npm run backend


Servidor disponível em: http://localhost:5001

Rotas disponíveis:

GET /clientes → lista os clientes do dados.json

POST /clientes → adiciona novo cliente
Exemplo:

{ "nome": "Maria", "email": "maria@example.com" }

3) Rodar o Frontend

Em outro terminal:

cd frontend
npm install
npm run dev


App disponível em: http://localhost:5173

Use http://localhost:5001 como base da API.

📦 Estrutura de Dados

Arquivo dados.json (no backend):

[
  { "nome": "fiap", "email": "fiap.com.br" }
]


As requisições POST adicionam novos objetos a este array.

📌 Status do Desenvolvimento

✅ Backend configurado (Express + CORS)

✅ Rotas GET e POST funcionais

✅ Frontend inicial (Vite + React)

🚧 Integração total entre front e back

🚧 Melhorias de UI/UX, validações, testes e deploy

💡 Dicas

Se ocorrer erro npm ERR! enoent ... package.json not found, significa que você está no diretório errado.

Use:

pwd      # mostra onde está
ls       # precisa listar package.json


Execute npm install separadamente em backend e frontend.

👨‍🏫 Créditos

Projeto desenvolvido em aulas práticas para estudo de APIs, integração e front-end.
