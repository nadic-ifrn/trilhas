# Front-End

## **Parte 1: Git/Github**

1. **Conceitos Fundamentais**

   - Repositório (repository)
   - Working Directory vs Index (staging area)
   - Commit
   - Branch
   - Remote

2. **Configuração Inicial**

   - `git config` (nome, email)
   - `git init` (criar repositório)
   - `git clone` (clonar repositório)

3. **Workflow Básico**

   - `git status` (verificar estado)
   - `git add` (adicionar ao staging)
   - `git commit` (criar commit)
   - `git log` (histórico de commits)

4. **Trabalhando com Branches**

   - `git branch` (listar/criar branches)
   - `git switch` ou `git checkout` (trocar de branch)
   - `git merge` (mesclar branches)
   - Resolução de conflitos

5. **Trabalhando com Remotes**

   - `git remote` (gerenciar remotes)
   - `git push` (enviar commits)
   - `git pull` (buscar e mesclar)
   - `git fetch` (buscar sem mesclar)

6. **Comandos Úteis**
   - `git diff` (ver diferenças)
   - `git reset` (desfazer mudanças)
   - `.gitignore` (ignorar arquivos)

**Sugestões de Aulas:**

- Exercícios git [link](https://learngitbranching.js.org/?locale=pt_BR)
- Curso em Vídeo : [link](https://www.youtube.com/watch?v=xEKo29OWILE&list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA&ab_channel=CursoemV%C3%ADdeo)

**Documentação:**

- [Git - Documentação Oficial](https://git-scm.com/doc)
- [Git - Tutorial](https://git-scm.com/docs/gittutorial)
- [Git - Guia de Referência](https://git-scm.com/docs)
- [GitHub - Documentação](https://docs.github.com/pt)
- [Atlassian Git Tutorial](https://www.atlassian.com/br/git/tutorials)

## **Parte 2: Conceitos Básicos**

> **📌 Nota Importante:** Essa é uma das partes mais importantes do roadmap! Ter uma base sólida vai deixar o resto molezinha

1. HTML
2. CSS
   - Seletores (elemento, classe, id, combinadores)
   - Box Model (margin, padding, border, width, height)
   - Flexbox (display: flex, justify-content, align-items)
   - Grid (display: grid, grid-template-columns, grid-template-rows)
   - Responsividade (@media queries)
   - Propriedades comuns (color, background, font, spacing)
3. JavaScript e manipulação do DOM
   - Seleção de elementos (getElementById, querySelector, querySelectorAll)
   - Criação e modificação de elementos (createElement, append, innerHTML)
   - Manipulação de classes e estilos (classList, style)
   - Atributos (setAttribute, getAttribute, removeAttribute)
4. Eventos em JavaScript
   - addEventListener
   - Eventos de mouse (click, mouseenter, mouseleave)
   - Eventos de teclado (keydown, keyup)
   - Eventos de formulário (submit, change)
   - Event delegation
   - Prevenção de comportamento padrão (preventDefault)
5. Formulários e validação
6. Consumo de APIs (fetch)
7. Local Storage e Session Storage
8. PROJETO

- Criar uma landing page [responsiva] para um campeonato de jogos eletrônicos usando apenas HTML, CSS e JavaScript. A página deverá ter o nome do evento, uma descrição do evento, data e um formulário para cadastro. O formulário deverá conter os campos: nome, e-mail, opção do jogo, login e senha. Implementar validação de formulário com JavaScript.

**Sugestões de materiais:**

- HTML e CSS (Curso em Vídeo):[link](https://www.youtube.com/watch?v=Ejkb_YpuHWs&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n)
- HTML e CSS (Chief of Design):[link](https://www.youtube.com/watch?v=EiZbhsVY2Dk&list=PLwgL9IEA0PxUjbhob9UMdpVq12sGrjgU6)
- JavaScript (Curso em Vídeo): [link](https://www.youtube.com/watch?v=BXqUH86F-kA&list=PLntvgXM11X6pi7mW0O4ZmfUI1xDSIbmTm&ab_channel=CursoemV%C3%ADdeo)

**Documentação:**

- [MDN Web Docs - CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [MDN Web Docs - CSS Flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [MDN Web Docs - CSS Grid](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Grid_Layout)
- [MDN Web Docs - Responsive Design](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [JavaScript.info - Tutorial Moderno](https://javascript.info/)
- [MDN Web Docs - JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [MDN Web Docs - DOM](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model)

## **Parte 3: React.js**

1. Conceitos de TypeScript
   - Tipos básicos (string, number, boolean)
   - Interfaces e tipos customizados
   - Props tipadas
   - Generics básicos
2. Conceitos de React:
   - Componentes funcionais
   - JSX e sintaxe
   - Props (propriedades)
   - Estado com useState
   - Hooks essenciais:
     - useState
     - useEffect
     - useContext
     - useRef
   - Ciclo de vida (através de useEffect)
   - Composição de componentes
   - Lifting state up (elevação de estado)
3. Eventos em React
   - onClick, onChange, onSubmit
   - Event handlers
   - Event objects
4. Formulários em React
   - Controlled components
   - Uncontrolled components
   - Validação de formulários
5. Tailwind CSS
   - Instalação e configuração
   - Utility-first approach
   - Classes utilitárias (spacing, colors, typography)
   - Responsive design (breakpoints)
   - Estados (hover, focus, active)
   - Customização (tailwind.config.js)
6. Gerenciamento de estado
   - Estado local vs estado global
   - Context API
7. PROJETO

- Usar a landing page do projeto anterior, dessa vez feita em React e TypeScript, aplicando todos os conceitos vistos até o ponto 6. Adicionar uma página de confirmação de inscrição, que aparecerá após o envio dos dados da landing page. Implementar validação de formulário, gerenciamento de estado com hooks, e estilização com Tailwind CSS. Criar componentes reutilizáveis e aplicar composição de componentes.

**Sugestões de materiais:**

- TypeScript: [link](https://www.typescriptlang.org/docs/)
- React: [link](https://pt-br.reactjs.org/docs/getting-started.html)

**Documentação:**

- [React.dev - Documentação Oficial](https://react.dev/)
- [React.dev - Aprender React](https://react.dev/learn)
- [React.dev - Referência da API](https://react.dev/reference/react)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [Tailwind CSS - Documentação](https://tailwindcss.com/docs)

## **Parte 4: Next.js**

1. Organização do projeto
   - Estrutura do App Router
   - Convenções de nomenclatura
   - Organização de componentes
2. App Router e File-System Routing
   - Estrutura do diretório `app`
   - Rotas estáticas e dinâmicas
   - Layouts (layout.tsx)
   - Rotas aninhadas
3. Componentes Next.js
   - Link (navegação client-side)
   - Image (otimização automática)
4. Server Components vs Client Components
   - Server Components (padrão)
   - Client Components ('use client')
   - Quando usar cada um
5. Route Handlers (API)
   - Criação de rotas API
   - Métodos HTTP (GET, POST, etc.)
   - Fetch API
   - Tratamento de erros
6. Autenticação e Middleware
   - Middleware básico
   - Proteção de rotas
   - Cookies para sessão
   - Autenticação simples
7. Server Actions
   - Form Actions
   - Validação server-side
8. PROJETO

- Criar um sistema que controla as inscrições em um evento científico. O evento abordará o branqueamento de corais, onde usuários poderão se inscrever e publicar artigos. Os administradores poderão ver a quantidade de inscritos e artigos submetidos.

**Requisitos do Projeto:**

- Sistema de autenticação (login/registro)
- Dashboard para usuários (inscrição no evento, submissão de artigos)
- Dashboard para administradores (estatísticas, gerenciamento)
- Route Handlers para API
- Middleware para proteção de rotas
- Cookies para sessão
- Server Actions para formulários
- Responsividade com Tailwind CSS

**Sugestões de materiais:**

- [Documentação Next.js](https://nextjs.org/docs/getting-started)
- [Next.js App Router](https://nextjs.org/docs/app)
- [Next.js Learn Course](https://nextjs.org/learn)

**Documentação:**

- [Next.js - Documentação Oficial](https://nextjs.org/docs)
- [Next.js - App Router](https://nextjs.org/docs/app)
- [Next.js - Routing](https://nextjs.org/docs/app/building-your-application/routing)
- [Next.js - Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components)
- [Next.js - Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers)
- [Next.js - Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware)
- [Next.js - Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations)
