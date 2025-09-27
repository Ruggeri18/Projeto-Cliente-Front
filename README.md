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
