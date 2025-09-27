# 🚀 ProjetoCliente
> 📚 **Projeto acadêmico em desenvolvimento durante as aulas**  
> Backend com **Node.js + Express** e frontend com **React (Vite)**.  
> ⚠️ O projeto **não está finalizado** – novas funcionalidades serão adicionadas conforme as aulas avançarem.

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


⚙️ Pré-requisitos
Node.js ≥ 18

NPM instalado

Verifique:

bash
Copiar código
node -v
npm -v
▶️ Como Rodar o Projeto
1) Clonar o Repositório
bash
Copiar código
git clone <URL_DO_REPOSITORIO>
cd projetoCliente
2) Rodar o Backend
bash
Copiar código
cd backend
npm install
npm run backend
Servidor disponível em: http://localhost:5001

Rotas disponíveis:

GET /clientes → lista clientes do dados.json

POST /clientes → adiciona novo cliente

Exemplo de requisição:

json
Copiar código
{
  "nome": "Maria",
  "email": "maria@example.com"
}
3) Rodar o Frontend
Em outro terminal:

bash
Copiar código
cd frontend
npm install
npm run dev
App disponível em: http://localhost:5173
Use http://localhost:5001 como base da API.

📦 Estrutura de Dados
Arquivo dados.json:

json
Copiar código
[
  { "nome": "fiap", "email": "fiap.com.br" }
]
As requisições POST adicionam novos objetos a este array.

📌 Status do Desenvolvimento
✅ Backend configurado (Express + CORS)

✅ Rotas GET e POST funcionais

✅ Frontend inicial (Vite + React)

🚧 Integração completa e melhorias de UI/UX

🚧 Validações, testes e deploy futuro

💡 Dicas
Se ocorrer:

go
Copiar código
npm ERR! enoent ... package.json not found
➡️ Você está no diretório errado.

Verifique com:

bash
Copiar código
pwd     # mostra diretório atual
ls      # precisa listar package.json
Execute npm install separadamente em backend e frontend.

👨‍🏫 Créditos
Projeto desenvolvido em aulas práticas para fins educacionais.

ruby
Copiar código

---

⚠️ **IMPORTANTE:**  
- Note que o bloco da estrutura do projeto está dentro de ```` ```bash ```` e fecha com outra linha de ````` ``` ````.  
- Depois vem texto normal, e novos blocos de código com ```` ```bash ```` ou ```` ```json ````.  
- Se você esquecer de fechar um bloco, o GitHub interpreta todo o resto como parte dele.

Salve assim e clique em **Preview** no GitHub → a estrutura aparecerá em caixinha de código e o texto abaixo fica normal.
