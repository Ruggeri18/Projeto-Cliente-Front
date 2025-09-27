# 🚀 ProjetoCliente
> 📚 **Projeto acadêmico em desenvolvimento durante as aulas**  
> Combina **Node.js + Express** no backend e **React (Vite)** no frontend.  
> ⚠️ O projeto **não está finalizado** – novas features e ajustes serão adicionados nas próximas aulas.

---

## 📂 Estrutura Completa
```bash
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
   │  ├─ routes/                     # Páginas do app
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


Pré-requisitos

Node.js ≥ 18

NPM instalado

Verifique:
node -v
npm -v

Como Rodar o Projeto
1) Clonar o Repositório
git clone <URL_DO_REPOSITORIO>
cd projetoCliente

2) Rodar o Backend
cd backend
npm install
npm run backend

Rotas disponíveis:

GET /clientes → lista clientes do dados.json

POST /clientes → adiciona novo cliente
Exemplo de requisição:
{
  "nome": "Maria",
  "email": "maria@example.com"
}

3) Rodar o Frontend

Em outro terminal:
cd frontend
npm install
npm run dev


Estrutura de Dados

Arquivo dados.json:
[
  { "nome": "fiap", "email": "fiap.com.br" }
]


Status do Desenvolvimento

✅ Backend configurado (Express + CORS)

✅ Rotas GET e POST funcionais

✅ Frontend inicial (Vite + React)

🚧 Integração completa e melhorias de UI/UX

🚧 Validações, testes e deploy futuro

Créditos

Projeto desenvolvido em aulas práticas para fins educacionais.
