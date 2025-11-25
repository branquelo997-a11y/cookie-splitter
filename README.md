# 🍪 Cookie Splitter

Separador de Cookies Roblox - Ferramenta para separar cookies em lotes e extrair nicks e senhas.

## 🚀 Como hospedar no Railway

### Passo 1: Criar conta no Railway
1. Acesse [railway.app](https://railway.app)
2. Faça login com GitHub, Google ou email

### Passo 2: Criar novo projeto
1. Clique em "New Project"
2. Selecione "Deploy from GitHub repo" (se você já tem o código no GitHub)
   OU
   Selecione "Empty Project" para fazer deploy direto

### Passo 3: Configurar o projeto

#### Se usar GitHub:
1. Conecte seu repositório GitHub
2. Railway detectará automaticamente o `package.json`
3. Configure as variáveis de ambiente (se necessário)
4. Clique em "Deploy"

#### Se usar deploy direto:
1. Instale a CLI do Railway:
```bash
npm i -g @railway/cli
```

2. Faça login:
```bash
railway login
```

3. Inicialize o projeto:
```bash
railway init
```

4. Faça deploy:
```bash
railway up
```

### Passo 4: Configurações importantes

- **Porta**: O Railway define automaticamente a variável `PORT`
- **Node Version**: Certifique-se de usar Node.js 18 ou superior
- **Build Command**: Não é necessário (site estático)
- **Start Command**: `npm start`

### Passo 5: Acessar seu site
Após o deploy, o Railway fornecerá uma URL pública como:
`https://seu-projeto.railway.app`

## 📦 Estrutura do Projeto

```
.
├── separador_cookies.html  # Arquivo principal
├── server.js               # Servidor Express
├── package.json            # Dependências
└── README.md              # Este arquivo
```

## 🔧 Comandos Locais

Para testar localmente:
```bash
npm install
npm start
```

Acesse: http://localhost:3000

## 📝 Notas

- O Railway detecta automaticamente Node.js pelo `package.json`
- A porta é definida automaticamente pela variável `PORT`
- O site é totalmente estático, então o deploy é muito rápido

