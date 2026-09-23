# 🚀 Meu Projeto

Página home que lista meus projetos pessoais, com uma tela de login inicial. A ideia é que, com o tempo, vários outros sistemas sejam adicionados dentro do projeto — novas páginas, novas telas, novas funcionalidades — sempre acessados a partir dessa home.

> 📚 Este é um projeto de estudo, feito enquanto aprendo programação do zero.

## ✅ Funcionalidades

Nada implementado ainda — o projeto está na fase de planejamento.

- ⬜ Tela de login (`login.html`)
- ⬜ Página home listando os projetos (`home.html`)
- ⬜ Estilização geral (CSS)
- ⬜ Validação de login em JS
- ⬜ Salvar/carregar projetos com `localStorage`

## 🛠️ Tecnologias usadas

- **HTML** — estrutura das páginas
- **CSS** — estilização
- **JavaScript** — lógica e interatividade (puro, sem frameworks ou bibliotecas)

Sem backend/servidor por enquanto — tudo roda direto no navegador.

## 📁 Estrutura de pastas

```
meu-portfolio/
├── login.html          
├── home.html 
├── css/
│   └── style.css
├── js/
│   ├── login.js
│   └── projetos.js
└── assets/
    └── (imagens, etc.)
```

## ▶️ Como rodar o projeto

1. Baixe ou clone a pasta do projeto
2. Abra o arquivo `index.html` diretamente no navegador (duplo clique ou arraste pro navegador)
3. Não precisa instalar nada — é só HTML, CSS e JS puro

## 🔐 Como funciona o login

⚠️ **Importante:** esse login é apenas simulado no front-end, para fins de estudo. Ele **não é seguro** e não deve ser usado com senhas ou dados reais, porque qualquer validação feita só em JavaScript fica visível no código-fonte da página.

A ideia planejada é:
- O usuário preenche o formulário em `index.html`
- O `login.js` valida os dados digitados
- Se validar corretamente, salva algo no `localStorage` (ex: um "usuário logado") e redireciona para `home.html`
- A `home.html` pode checar esse valor no `localStorage` pra decidir se mostra o conteúdo ou manda de volta pro login

Quando eu quiser um login de verdade (seguro), vou precisar de um backend (Node.js, Firebase, etc.) — isso fica para uma etapa futura.

## 📌 Próximos passos

Direto do quadro Trello (*Meu Projeto*), lista **Backlog / Ideias**:

- [ ] Criar estrutura de pastas do projeto
- [ ] Montar `home.html` com projetos fake (2-3 cards)
- [ ] Estilizar `home.html` com CSS (grid/flexbox)
- [ ] Criar `index.html` com formulário de login
- [ ] Estilizar formulário de login
- [ ] JS: validar login e redirecionar para `home.html`
- [ ] JS: salvar/carregar projetos com `localStorage`
