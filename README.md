# 🚀 ProjetoCliente
> 📚 Projeto acadêmico em desenvolvimento durante as aulas.  
> Backend com **Node.js + Express** e frontend com **React (Vite)**.  
> ⚠️ O projeto **não está finalizado** – novas features e ajustes virão nas próximas aulas.

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
```


#Pré-requisitos

Node.js ≥ 18

NPM instalado

Verifique:

```
node -v
npm
```

Como Rodar o Projeto

#1) Clonar o repositório
```
git clone <URL_DO_REPOSITORIO>
cd projetoCliente
```

#2) Rodar o Backend
```   
cd backend
npm install
npm run backend
```

3) Rodar o Frontend
Em outro terminal:
```
cd frontend
npm install
npm run dev
```
