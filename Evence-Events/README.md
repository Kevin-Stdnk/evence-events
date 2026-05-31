# 🚀 Evence Events - Frontend & Backend Application 🚀

Este diretório contém o código-fonte principal da aplicação **Evence Events**, estruturado com o framework **Angular v21** no frontend, **Tailwind CSS v4** na estilização e **JSON Server** no mockup de banco de dados e APIs REST.

> [!IMPORTANT]
> A documentação completa e detalhada do repositório, incluindo arquitetura de banco de dados, fluxo de telas, credenciais de teste e passo a passo detalhado está localizada na raiz do repositório.
> 👉 **[Acessar o README.md Principal na Raiz do Repositório](../README.md)**

---

## 🛠️ Como Executar Localmente

### 1. Instalar as dependências do projeto
```bash
npm install
```

### 2. Rodar o servidor mock da API REST (JSON Server)
Este comando iniciará o banco de dados simulado a partir de `db.json` na porta `3000`:
```bash
npm run backend
```

### 3. Rodar a aplicação Angular
Inicia o servidor de desenvolvimento do Angular:
```bash
npm run start
```

Após a inicialização dos dois servidores, acesse o aplicativo em seu navegador através do link:
👉 **[http://localhost:4200](http://localhost:4200)**

---

## 🧪 Testes Unitários com Vitest
Para rodar a suíte de testes rápidos e robustos, execute:
```bash
npm run test
```

---

## 📁 Estrutura deste Diretório
* `src/app/` - Componentes, páginas, serviços e interfaces da aplicação.
* `db.json` - Nosso banco de dados mock que alimenta as requisições HTTP locais.
* `package.json` - Scripts de compilação, testes e dependências do projeto.
* `tsconfig.json` - Configurações do compilador TypeScript.
