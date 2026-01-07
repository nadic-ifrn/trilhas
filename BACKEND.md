# Back-end

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

1. **Fundamentos do Python**

   - Variáveis e tipos de dados
   - Operadores (aritméticos, lógicos, comparação)
   - Estruturas condicionais (if, elif, else)
   - Estruturas de repetição (for, while)

2. **Coleções**

   - Listas (list)
   - Tuplas (tuple)
   - Dicionários (dict)
   - Sets (set)
   - Operações e métodos comuns

3. **Funções**

   - Definição de funções
   - Parâmetros e argumentos
   - Retorno de valores
   - Escopo de variáveis

4. **Orientação a Objetos**
   - Classes e objetos
   - Atributos e métodos
   - Construtor (`__init__`)
   - Herança
   - Encapsulamento

**Sugestão de Aulas:**

- Capítulo: 02, 03 e 05. ( [link](https://www.datascienceacademy.com.br/course/python-fundamentos) )
- Fazer os exercícios que estão no fim de cada capitulo.

**Documentação:**

- [Python - Documentação Oficial](https://docs.python.org/pt-br/3/)
- [Python - Tutorial](https://docs.python.org/pt-br/3/tutorial/)
- [Python - Guia de Referência](https://docs.python.org/pt-br/3/reference/)

## **Parte 3: Framework Django**

1. **Configuração Inicial**

   - Ambiente virtual (venv)
   - Instalação do Django
   - Criação de projeto (`django-admin startproject`)
   - Criação de apps (`python manage.py startapp`)

2. **Estrutura MTV (Model-Template-View)**

   - Entendendo a arquitetura Django
   - Organização de arquivos

3. **URLs e Rotas**

   - URLconf (urls.py)
   - Mapeamento de rotas
   - Parâmetros de URL

4. **Models**

   - Definição de modelos
   - Campos e tipos
   - Relacionamentos (ForeignKey, ManyToMany)
   - Migrations (`makemigrations`, `migrate`)

5. **Views**

   - Function-Based Views (FBV)
   - Class-Based Views (CBV)
   - Request e Response
   - Quando usar cada tipo

6. **Templates**

   - Sistema de templates Django
   - Template tags e filters
   - Herança de templates

7. **Forms**

   - Formulários Django
   - Validação
   - Formulários baseados em modelos

8. **Admin Interface**

   - Configuração do admin
   - Registro de modelos
   - Personalização

9. PROJETO

- Crie um mecanismo de CRM (o que é CRM: ( [wikipedia link](https://pt.wikipedia.org/wiki/Sistemas_de_CRM) ) para qualquer tipo de empresa, onde será possível cadastrar/remover/editar produtos, assim como definir quantidade em estoque e sempre que realizado uma venda o estoque e o faturamento total da empresa deve ser atualizado.

**Sugestões de Aulas:**

- Seções 2, 3, 4 e 5: ( [https://www.udemy.com/course/programacao-web-com-django-framework-do-basico-ao-avancado/](https://www.udemy.com/course/programacao-web-com-django-framework-do-basico-ao-avancado/) )

**Documentação:**

- [Django - Documentação Oficial](https://docs.djangoproject.com/)
- [Django - Tutorial](https://docs.djangoproject.com/en/stable/intro/tutorial01/)
- [Django - Models](https://docs.djangoproject.com/en/stable/topics/db/models/)
- [Django - Views](https://docs.djangoproject.com/en/stable/topics/http/views/)
- [Django - Class-Based Views](https://docs.djangoproject.com/en/stable/topics/class-based-views/)
- [Django - Forms](https://docs.djangoproject.com/en/stable/topics/forms/)

## **Parte 4: Django REST framework**

1. **Conceitos Fundamentais**

   - O que é uma API REST
   - Requests e Responses
   - Métodos HTTP (GET, POST, PUT, DELETE, PATCH)

2. **Serializers**

   - ModelSerializer
   - Serializer fields
   - Validação customizada
   - Relacionamentos

3. **Views**

   - APIView (Class-based)
   - @api_view (Function-based)
   - ViewSets (ModelViewSet)
   - Routers

4. **CRUD Completo**

   - Criar (POST)
   - Listar (GET)
   - Atualizar (PUT/PATCH)
   - Deletar (DELETE)

5. **Autenticação**

   - Session Authentication
   - Token Authentication
   - JWT (básico)

6. **Permissões**

   - Permissões padrão (IsAuthenticated, IsAdminUser)
   - Permissões customizadas
   - Permissões por objeto

7. **Filtros e Paginação**

   - Filtros básicos
   - Paginação

8. PROJETO

- Dê continuidade ao projeto do CRM, agora criando sua API. Crie endpoints para criar conta e realizar login. Crie endpoints para listar/cadastrar/editar/remover produtos e estes endpoints só poderão ser acessados se o usuário estiver "logado". Crie um endpoint para listar os detalhes do produto assim como seu estoque. Crie um endpoint para listar o faturamento da empresa, ele só deve ser acessado pelo dono da empresa.

**Sugestões de Aulas:**

- Seções 7: [Curso na Udemy Django Básico ao Avançado](https://www.udemy.com/course/programacao-web-com-django-framework-do-basico-ao-avancado/)
- [Curso na Alura Django REST Framework](https://cursos.alura.com.br/course/api-django-3-rest-framework)
- O que é uma API: [link](https://www.youtube.com/watch?v=vGuqKIRWosk&ab_channel=C%C3%B3digoFonteTV)

**Documentação:**

- [Django REST Framework - Documentação Oficial](https://www.django-rest-framework.org/)
- [DRF - Quickstart](https://www.django-rest-framework.org/tutorial/quickstart/)
- [DRF - Serializers](https://www.django-rest-framework.org/api-guide/serializers/)
- [DRF - Viewsets](https://www.django-rest-framework.org/api-guide/viewsets/)
- [DRF - Authentication](https://www.django-rest-framework.org/api-guide/authentication/)
- [DRF - Permissions](https://www.django-rest-framework.org/api-guide/permissions/)
