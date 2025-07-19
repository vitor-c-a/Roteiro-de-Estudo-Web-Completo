# 🗓 **Mês 1 — Fundamentos e Primeira Ferramenta Web**

## ✅ **Semana 1 – Fundamentos Web: HTML e Git/GitHub** ✅

**Objetivo:** Criar a base para qualquer página web e versionar seus projetos.

- HTML5: estrutura de páginas, tags semânticas, formulários simples.
- Git: comandos básicos (`init`, `add`, `commit`, `push`, `pull`, `clone`).
- GitHub: criar repositórios, subir projetos.

✅ Projeto da semana: Página HTML com formulário de cadastro + repositório no GitHub.

---

## ✅ Semana 2 – Estilização com CSS Puro ✅

**Objetivo:** Aprender os fundamentos reais de estilização, construindo interfaces bonitas e responsivas com CSS tradicional.

---

### 📘 Fundamentos que você vai dominar:

### 1. **Seletores e especificidade**

- `element`, `.classe`, `#id`, `[atributo]`
- Cascata e conflito de estilos (entender “quem vence”)

### 2. **Box Model**

- `width`, `height`, `padding`, `border`, `margin`
- `box-sizing: border-box`

### 3. **Display e posicionamento**

- `display: block`, `inline`, `inline-block`, `none`
- `position: static`, `relative`, `absolute`, `fixed`
- `z-index`

### 4. **Flexbox e Grid**

- **✅ FLEXBOX – Ordem de Estudo**
    
    **🟢 Básico (entender e aplicar)**
    
    1. `display: flex`
    2. `flex-direction: row | column`
    3. `justify-content`
        - `flex-start`, `center`, `flex-end`, `space-between`, `space-around`, `space-evenly`
    4. `align-items`
        - `flex-start`, `center`, `flex-end`, `stretch`
    5. `gap` (espaçamento entre itens)
    6. `align-self` (alinhamento individual)
    
    ---
    
    **🟡 Intermediário (layouts responsivos e controle de tamanho)**
    
    1. `flex-wrap`
        - Quebra os itens para linha de baixo
    2. Combinações:
        - `flex-direction` + `wrap` para fazer grades simples
    3. `flex-grow`, `flex-shrink`, `flex-basis`
        - Controle real do quanto cada item ocupa
    4. Atalho `flex: grow shrink basis`
        - Ex: `flex: 1 0 200px;`
    
    ---
    
    **🔴 Avançado (centralização e responsividade)**
    
    1. Centralização total com:
    
    ```css
    css
    display: flex;
    justify-content: center;
    align-items: center;
    ```
    
    1. Layouts que se adaptam à largura da tela com `flex-grow` e `wrap`
    2. Uso combinado com `media queries`
    3. Casos reais: menus, carrosséis, cards em linha
- ✅ CSS GRID – Ordem de Estudo
    - **🟢 Básico (estrutura da grade)**
        1. `display: grid`
        2. `grid-template-columns` e `grid-template-rows`
            - Unidades: `px`, `fr`, `auto`
        3. `gap` (espaçamento entre colunas e linhas)
        4. Posicionamento automático dos itens - 
        5. Atalhos úteis:
            - `repeat(3, 1fr)` – 3 colunas iguais
            - `1fr 2fr` – colunas com larguras proporcionais
    
    ---
    
    - **🟡 Intermediário (alinhamento e posicionamento manual)**
        1. **Alinhamento dentro das células**
            - `justify-items`, `align-items`
            - `place-items: center` (atalho)
        2. **Alinhamento da grade inteira**
            - `justify-content`, `align-content`
            - `place-content: center` (atalho)
        3. **Posicionamento manual de itens**
            - `grid-column`, `grid-row`
            - Ex: `grid-column: 1 / 3`
        4. **Sobreposição e controle de camadas**
            - `z-index` com `grid-area`
            - Útil em banners, overlays, cards, etc.
    
    ---
    
    - **🟠 Grade semântica e nomeada**
        1. `grid-template-areas`
            - Criação de layout nomeado e legível
        2. `grid-area`
            - Aplicação dos nomes definidos
        3. Nomeando linhas/colunas com `[]`
            - Ex: `grid-template-columns: [start] 1fr [middle] 2fr [end];`
    
    ---
    
    - 🔴 **Avançado (layouts adaptativos e responsivos)**
        1. `minmax()`, `auto-fit`, `auto-fill`
            - Ex: `repeat(auto-fit, minmax(200px, 1fr))`
            - Cria grids dinâmicos e responsivos
        2. Combinação com `media queries`
            - Alterar número de colunas, áreas e espaçamentos por resolução
        3. `subgrid` (nível avançado, pouco suporte ainda)
            - Usado em grids aninhados para herdar linhas/colunas do pai

### 5. **Cores e tipografia**

- `color`, `background-color`
- `font-size`, `font-family`, `line-height`, `text-align`

### 6. **Espaçamento e bordas**

- `padding`, `margin`, `border`, `border-radius`, `gap`

### 7. **Responsividade**

- Unidades relativas (`em`, `%`, `vw`, `vh`)
- Media queries (`@media`)
- Layout fluido vs fixo

---

### 🔨 Projeto da semana:

> Crie uma página de login e um formulário de contato responsivos usando apenas HTML + CSS.
> 

✅ Requisitos:

- Layout centralizado com `flex` ou `grid`
- Inputs estilizados
- Botões com hover
- Responsividade em mobile (`@media`)
- Versão desktop e versão mobile com leves adaptações

---

## ✅ **Semana 3 – JavaScript Básico: lógica e interação ⏳**

**Objetivo:** Compreender a lógica e manipular elementos na página.

- Variáveis, tipos de dados (`string`, `number`, `boolean`)
- Operadores, condicionais (`if`, `else`, `switch`)
- Laços (`for`, `while`)
- Funções (declarativas e arrow functions)
- Eventos (`click`, `input`)
- `console.log`, `prompt`, `alert`

✅ **Projeto:** Página interativa de boas-vindas com nome do usuário e mudança de estilo via clique.

---

## ✅ **Semana 4 – DOM + Manipulação de Elementos**

**Objetivo:** Controlar dinamicamente elementos da página com JS.

- `querySelector`, `getElementById`
- `addEventListener`, `classList.add/remove/toggle`
- Modificar textos, atributos e estilos (`.innerText`, `.value`, `.setAttribute`)
- Validação de formulários (preventDefault, mensagens de erro)

✅ **Projeto:** Formulário com validação e exibição dinâmica dos dados enviados.

---

# 🗓 **MÊS 2 — JavaScript, Bibliotecas e Componentização**

---

### ✅ **Semana 5 – Estruturação de Projetos + Reutilização com JS**

**Objetivo:** Escrever JS de forma mais organizada e modular.

- Organizar arquivos em `index.html`, `main.css`, `main.js`
- Criar funções reutilizáveis
- Componentes simples em HTML (ex: card, modal)
- Modularização com `<template>` ou via JS

✅ **Projeto:** Criar um site com cards dinâmicos (ex: catálogo de produtos fictícios).

---

### ✅ **Semana 6 – Introdução ao Bootstrap 5**

**Objetivo:** Usar componentes prontos e aprender classes utilitárias.

- Instalação via CDN
- Sistema de grid responsivo
- Classes utilitárias (`text-center`, `mb-3`, `bg-light`)
- Componentes: navbar, buttons, modal, cards, alert

✅ **Projeto:** Refatorar o projeto anterior usando Bootstrap (mesma estrutura, novo visual).

---

### ✅ **Semana 7 – Introdução ao Tailwind CSS**

**Objetivo:** Usar classes utilitárias para estilização precisa e rápida.

- Instalação via CDN (modo iniciante)
- Estrutura de classes (margens, paddings, cor, tipografia, grid, flex)
- Responsividade com `sm:`, `md:`, `lg:`
- Criar componentes reutilizáveis com Tailwind

✅ **Projeto:** Criar uma landing page com Tailwind.

---

### ✅ **Semana 8 – JavaScript Intermediário + Armazenamento**

**Objetivo:** Guardar dados no navegador e criar experiências persistentes.

- `localStorage` e `sessionStorage`
- Conversão JSON (`JSON.stringify`, `JSON.parse`)
- Manipulação de arrays e objetos
- Princípios de estado (estado da interface com JS)

✅ **Projeto:** Lista de tarefas (To-Do) com salvamento no `localStorage`.

---

# 🗓 **MÊS 3 — Back-End com Python + Integrações Web**

### ✅ **Semana 9 – Introdução ao Flask + Servidor Web**

**Objetivo:** Montar um back-end básico com Python e Flask.

- Instalar Flask
- Estrutura de um app: `app.py`, `templates/`, `static/`
- Rotas: `@app.route`
- Enviar dados com `GET` e `POST`
- `render_template` com HTML + dados

✅ **Projeto:** Página com formulário que envia e exibe dados no navegador (sem banco ainda).

---

### ✅ **Semana 10 – Banco de Dados com SQLite**

**Objetivo:** Salvar e recuperar dados reais.

- Criar e conectar SQLite
- Comandos básicos: `INSERT`, `SELECT`, `DELETE`
- Integração com Flask (`sqlite3`, `cursor`)
- Templates Jinja2 para mostrar dados dinâmicos

✅ **Projeto:** Sistema simples de cadastro (ex: contatos ou produtos).

---

### ✅ **Semana 11 – Integração Front + Back com HTML + JS**

**Objetivo:** Combinar front-end dinâmico com back-end real.

- Enviar dados HTML → Flask
- Usar JavaScript para mostrar ou atualizar dados
- Criar feedbacks dinâmicos (ex: mensagem de sucesso)

✅ **Projeto:** Lista de produtos ou contatos com adição e exclusão em tempo real.

---

### ✅ **Semana 12 – Deploy + Git Profissional**

**Objetivo:** Colocar tudo no ar com deploy e práticas reais.

- Deploy no Render (ou Railway)
- Teste de endpoints com Postman
- Uso de `.env`, `.gitignore`, estrutura limpa de projeto
- Git avançado: branches, commits organizados, mensagens úteis

✅ **Projeto:** Sistema completo online com deploy e versão pública.

---

# 🗓 **MÊS 4 — APIs, Testes e Projeto Final**

### ✅ **Semana 13 – Consumo de APIs com JavaScript**

**Objetivo:** Integrar dados externos com seu front-end.

- `fetch`, `async/await`
- API pública (ex: ViaCEP, PokeAPI, Clima)
- Exibir dados externos em tempo real
- Tratar erros de resposta

✅ **Projeto:** Ferramenta com busca de dados externos via API.

---

### ✅ **Semana 14 – Criando APIs com Flask (REST)**

**Objetivo:** Construir sua própria API REST.

- Rotas `GET`, `POST`, `PUT`, `DELETE`
- JSON: enviar e receber dados
- Separar `routes.py`, `models.py`, `app.py`
- Testar API no Postman

✅ **Projeto:** API de tarefas ou produtos com CRUD completo.

---

### ✅ **Semana 15 – Testes e Boas Práticas**

**Objetivo:** Garantir qualidade e manutenibilidade.

- Testes manuais e automatizados (início com `pytest`)
- Validação de dados
- Estrutura de projeto limpa
- README profissional no GitHub

✅ **Projeto:** Revisão e melhoria dos projetos anteriores com testes simples.

---

### ✅ **Semana 16 – Projeto Final Completo**

**Objetivo:** Juntar tudo que aprendeu em um sistema completo.

✅ **Projeto:** Ferramenta completa com:

- Front responsivo com Tailwind ou Bootstrap
- JS interativo e uso de API externa
- Back-end com Flask + banco de dados
- Deploy online com URL pública
- Código no GitHub com README bem feito

---

## 🎯 **Resultado Final Após 4 Meses**

Você terá:

- ✅ **De 5 a 7 projetos completos**, publicados no GitHub Pages e no Render.
- ✅ **Front-end moderno**, usando HTML, CSS (puro e com bibliotecas como Bootstrap e Tailwind) e JavaScript interativo.
- ✅ **Back-end funcional** com Flask + SQLite, rotas e banco de dados operando com dados reais.
- ✅ **APIs integradas**: saberá consumir APIs externas (como Clima, CEP, PokéAPI) e criar suas próprias APIs REST.
- ✅ **Deploy profissional**: sistemas funcionando online, com deploy no Render e repositórios bem organizados no GitHub.
- ✅ **Conhecimento sólido para freelas ou soluções para empresas locais**, como sistemas de cadastro, controle de produtos ou páginas promocionais.
- ✅ **Boas práticas de desenvolvimento**: versionamento com Git, organização de projeto, uso de `.env`, testes e estrutura limpa.
- ✅ **Base forte para o próximo nível**: integração com automações Python, aprendizado de frameworks mais robustos (Django, React), ou entrada no mercado como júnior.
