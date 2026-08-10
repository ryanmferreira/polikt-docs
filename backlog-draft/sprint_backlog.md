---
id: "31fdb477-b9d6-4630-a81e-d05f7cc6c702"
title: "POLIKT"
tags: []
pinned: false
created: 2026-08-07T13:10:53.561693100+00:00
modified: 2026-08-09T01:20:45.628330700+00:00
---
# POLIKT

## Sprint Backlog: Sprint 1

> **Duração:** 1 mês  
> **Objetivo do Sprint:** desenvolver a primeira versão funcional do POLIKT, permitindo que o cidadão crie uma conta, acesse o sistema, visualize notícias, consulte cursos e encontre informações sobre denúncias.

---

## Épico: Conta

### 1. Cadastro e Login
- **História de Usuário:** "Como cidadão, quero me cadastrar e entrar na minha conta, para acessar os recursos do app"
- **Regras de Negócio:** dados obrigatórios (nome, e-mail, senha) não podem ficar vazios; e-mail deve ser único no sistema; senha deve seguir critério mínimo de segurança.
- **Critério de Aceite:** usuário consegue criar conta e logar com as credenciais cadastradas.

> **Prioridade:** Deve (Alta)

**Tarefas:**
#### Front-end
-  Criar tela de cadastro.
-  Criar tela de login.
-  Implementar validação visual dos campos obrigatórios.
-  Implementar mensagens de erro e sucesso.
#### Back-end
-  Implementar cadastro de usuário.
-  Implementar autenticação.
-  Validar campos obrigatórios.
-  Validar e-mail único.
-  Implementar validação mínima da senha.
#### Database
-  Criar estrutura de usuário no banco de dados.
-  Definir campos obrigatórios.
-  Criar restrição de e-mail único.

#### Testes
-  Testar cadastro com dados válidos.
-  Testar cadastro com campos vazios.
-  Testar cadastro com e-mail já existente.
-  Testar senha fora do critério mínimo.
-  Testar login com credenciais válidas.
-  Testar login com credenciais inválidas.

---

## Épico: Feed de Notícias

### 2. Visualizar Feed
- **História de Usuário:** Como cidadão, quero ver um feed de notícias ao abrir o app, para me manter informado.
- **Regras de Negócio:** apenas notícias publicadas/aprovadas aparecem no feed; ordenação por data (mais recente primeiro).
- **Critério de Aceite:** usuário consegue visualizar uma lista de notícias publicadas, ordenadas da mais recente para a mais antiga.
> 
- **Prioridade:** Deve (Alta)

**Tarefas:**
#### Front-end
-  Criar tela do feed.
-  Criar componente para exibição das notícias.
-  Exibir título, resumo e data das notícias.
-  Implementar indicação de carregamento.
#### Back-end
-  Implementar consulta de notícias.
-  Filtrar apenas notícias publicadas/aprovadas.
-  Implementar ordenação por data, da mais recente para a mais antiga.
#### Database
-  Criar estrutura de notícia no banco de dados.
-  Definir campos da notícia.
-  Definir status de publicação/aprovação.
-  Criar dados de teste.

#### Testes
-  Testar exibição de notícias publicadas.
-  Testar ocultação de notícias não publicadas.
-  Testar ordenação por data.
-  Testar feed sem notícias.

### 3. Ler Notícia
- **História de Usuário:** Como cidadão, quero abrir uma notícia e ler seu conteúdo completo, para me aprofundar no assunto.
- **Regras de Negócio:** notícia deve exibir título, conteúdo, resumo, autor e data de publicação.
- **Critério de Aceite:** usuário consegue selecionar uma notícia no feed e visualizar seu conteúdo completo.

> **Prioridade:** Deve (Alta)

**Tarefas:**

#### Front-end
-  Criar tela de visualização da notícia.
-  Implementar navegação entre feed e notícia.
-  Exibir título.
-  Exibir conteúdo.
-  Exibir Resumo.
-  Exibir autor.
-  Exibir data de publicação.

#### Back-end
-  Implementar consulta de uma notícia específica.
-  Retornar título, conteúdo, autor e data de publicação.

#### Database
-  Garantir armazenamento dos dados necessários para exibição da notícia.
-  Criar dados de teste com autor e data de publicação.

#### Testes
-  Testar exibição de uma notícia.

---

## Épico: Cursos

### 4. Lista de Cursos
- **História de Usuário:** Como cidadão, quero ver os cursos disponíveis, para escolher o que aprender.
- **Regras de Negócio:** apenas cursos publicados/ativos aparecem na lista.
- **Critério de Aceite:** usuário consegue visualizar os cursos disponíveis e selecionar um curso.

> **Prioridade:** Deve (Alta)

**Tarefas:**

#### Front-end
-  Criar tela de cursos.
-  Criar componente para exibição dos cursos.
-  Exibir informações básicas dos cursos.
-  Implementar seleção de um curso.
#### Back-end
-  Implementar consulta de cursos.
-  Filtrar apenas cursos publicados/ativos.
-  Implementar retorno dos dados dos cursos.

#### Database
-  Criar estrutura de curso no banco de dados.
-  Definir status de publicação/atividade.
-  Criar dados de teste.

#### Testes
-  Testar listagem de cursos.
-  Testar exibição apenas de cursos ativos.
-  Testar seleção de um curso.

### 5. Módulos do Curso
- **História de Usuário:** Como cidadão, quero ver os módulos de um curso, para entender a estrutura do aprendizado.
- **Regras de Negócio:** um curso é composto por um ou mais módulos, exibidos em ordem definida.
- **Critério de Aceite:** usuário consegue visualizar os módulos pertencentes a um curso na ordem definida.

> **Prioridade:** Deve (Alta)

**Tarefas:**
#### Front-end
-  Criar tela de módulos.
-  Exibir módulos pertencentes ao curso.
-  Exibir módulos na ordem definida.
-  Implementar navegação entre curso e módulos.
#### Back-end
-  Implementar consulta dos módulos de um curso.
-  Relacionar módulos ao curso.
-  Retornar módulos na ordem definida.
#### Database
-  Criar estrutura de módulo no banco de dados.
-  Criar relacionamento entre cursos e módulos.
-  Definir campo de ordenação dos módulos.
-  Criar dados de teste.

#### Testes
-  Testar consulta dos módulos de um curso.
-  Testar relacionamento entre curso e módulos.
-  Testar ordem dos módulos.
-  Testar navegação entre curso e módulos.

### 6. Conteúdo do Módulo
- **História de Usuário:** Como cidadão, quero acessar o conteúdo de um módulo, para aprender os conceitos.
- **Critério de Aceite:** usuário consegue selecionar um módulo e visualizar seu conteúdo.

> **Prioridade:** Deve (Alta)

**Tarefas:**

#### Front-end
-  Criar tela de conteúdo do módulo.
-  Implementar navegação entre módulos e conteúdo.
-  Exibir o conteúdo corretamente.
-  Implementar navegação para o próximo/anterior módulo, se aplicável.

#### Back-end
-  Implementar consulta do conteúdo de um módulo.
-  Retornar conteúdo correspondente ao módulo selecionado.
-  Validar existência do módulo.

#### Database
-  Criar estrutura de conteúdo do módulo.
-  Relacionar conteúdo ao módulo.
-  Criar dados de teste.

#### Testes
-  Testar acesso ao conteúdo.
-  Testar conteúdo correspondente ao módulo selecionado.

---

## Épico: Denúncias

### 7. Guias por Tema
- **História de Usuário:** Como cidadão, quero ver guias de denúncia organizados por tema, para saber como denunciar algo específico.
- **Regras de Negócio:** cada guia pertence a exatamente um tema principal.
- **Critério de Aceite:** usuário consegue visualizar os guias disponíveis organizados por tema.

> **Prioridade:** Deve (Alta)

**Tarefas:**

#### Front-end
-  Criar tela de guias.
-  Exibir os temas disponíveis.
-  Exibir guias organizados por tema.
-  Implementar seleção de um guia.

#### Back-end
-  Implementar consulta dos guias.
-  Implementar consulta dos temas.
-  Relacionar cada guia ao seu tema.
-  Retornar guias organizados por tema.

#### Database
-  Criar estrutura de guia no banco de dados.
-  Garantir que cada guia pertença a um tema.
-  Criar dados de teste.

#### Testes
-  Testar organização dos guias por tema.
-  Testar exibição dos temas.
-  Testar seleção de um guia.

### 8. Conteúdo do Guia
- **História de Usuário:** Como cidadão, quero abrir um guia e ver o passo a passo, para saber exatamente o que fazer.
- **Regras de Negócio:** guia deve indicar o canal/órgão oficial responsável por aquele tipo de denúncia.
- **Critério de Aceite:** usuário consegue abrir um guia e visualizar o passo a passo, incluindo o canal ou órgão responsável pela denúncia.

> **Prioridade:** Deve (Alta)

**Tarefas:**
#### Front-end
-  Criar tela de conteúdo do guia.
-  Implementar navegação entre lista e guia.
-  Exibir passo a passo.
-  Exibir canal/órgão responsável.

#### Back-end
-  Implementar consulta de um guia específico.
-  Retornar passo a passo.
-  Retornar canal/órgão responsável.

#### Database
-  Definir estrutura para armazenar o passo a passo.
-  Definir campo para canal/órgão responsável.
-  Criar dados de teste.
#### Testes
-  Testar visualização do passo a passo.
-  Testar exibição do canal/órgão responsável.

---

## Resultado esperado do Sprint

Ao final do Sprint, o cidadão deverá conseguir:
1. Criar uma conta e fazer login.
2. Visualizar o feed de notícias.
3. Abrir e ler uma notícia.
4. Visualizar os cursos disponíveis.
5. Acessar os módulos de um curso.
6. Acessar o conteúdo de um módulo.
7. Visualizar os guias de denúncia organizados por tema.
8. Abrir um guia e consultar seu passo a passo.

> **Itens não selecionados para este Sprint:** Perfil, Recuperação de Senha, Progresso do Curso, Quiz de Fixação, Filtrar por Tema, Pesquisa, Comentários, Avaliação de Conteúdo, Compartilhamento e Notificações (provavelmente esqueci de algo :D).