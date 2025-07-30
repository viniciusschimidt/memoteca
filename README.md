
# 🧠✨ Memoteca - Suas lembranças em um só lugar

**Memoteca** é uma aplicação desenvolvida com **Angular 17**, que permite armazenar, visualizar, editar e excluir lembranças pessoais. É como um mural digital onde você pode guardar momentos especiais da sua vida.

Este projeto foi construído com foco em boas práticas de **componentização**, **comunicação com o backend**, **responsividade** e **acessibilidade**.

---

## 🌐 Acesse o projeto 

🔗 [Repositório oficial no GitHub](https://github.com/viniciusschimidt/memoteca)

---

## 📸 Funcionalidades

- 📌 Cadastrar novas lembranças com título, descrição e imagem
- 📂 Listar todas as lembranças salvas
- ✏️ Editar informações de uma lembrança existente
- ❌ Excluir uma lembrança
- 🔄 Comunicação real com uma API REST fake usando **JSON Server**

---

## 🚀 Tecnologias utilizadas

- **Angular 17**
- **TypeScript**
- **RxJS / Observables**
- **JSON Server (Fake API REST)**
- **HTML5 + CSS3**

---

## ⚙️ Como rodar o projeto localmente

### 🔽 Pré-requisitos

Antes de iniciar, você precisa ter instalado:

- Node.js (v16+)
- Angular CLI (`npm install -g @angular/cli`)
- Git

---

### 🧪 1. Clone o repositório

```bash
git clone https://github.com/viniciusschimidt/memoteca.git
cd memoteca
```

---

### 📦 2. Instale as dependências

```bash
npm install
```

---

### 🌐 3. Inicie a API simulada (JSON Server)

A aplicação usa uma API fake para simular requisições HTTP com dados persistentes:

```bash
npx json-server --watch backend/db.json --port 3000
```

A API ficará disponível em:  
📍 `http://localhost:3000/pensamentos`

---

### ▶️ 4. Rode o Angular

Com a API rodando, inicie o servidor Angular:

```bash
ng serve
```

Abra no navegador:  
📍 `http://localhost:4200`

---

## 📁 Estrutura do projeto

```bash
memoteca/
├── backend/
│   └── db.json                   # Base de dados fake da API
├── node_modules/
├── src/
│   ├── app/
│   │   ├── componentes/
│   │   │   ├── cabecalho/
│   │   │   ├── pensamentos/
│   │   │   └── rodape/
│   │   ├── app-routing.module.ts
│   │   ├── app.component.css
│   │   ├── app.component.html
│   │   ├── app.component.spec.ts
│   │   ├── app.component.ts
│   │   └── app.module.ts
│   ├── assets/
│   └── environments/
└── angular.json
```



## ✅ Status do projeto

🟢 **Concluído e funcional**  
🛠️ Em evolução com novas features planejadas

---

## 🤝 Contribuição

Contribuições são muito bem-vindas!  
Se quiser sugerir melhorias, abrir issues ou fazer um fork, fique à vontade! 💙

---

## 📬 Contato

Feito com dedicação por **Vinicius Schimidt**  
🔗 GitHub: [@viniciusschimidt](https://github.com/viniciusschimidt)  
🔗 LinkedIn: [linkedin.com/in/viniciusschimidt](https://linkedin.com)  
📧 Email: viniciusschimidt183@gmail.com

---

> *“Guardar memórias é uma forma de viver mais de uma vez.”* – Memoteca 💭
