---
id: "8e3341d3-3f54-4d0b-b517-3e2c61941b15"
title: "POLIKT"
tags: []
pinned: false
created: 2026-05-27T12:22:04.858734500+00:00
modified: 2026-08-07T13:18:30.259512100+00:00
---
# POLIKT
## Product Backlog
> OBS: OS ÉPICOS NÃO SE ENCONTRAM ORDENADOS POR PRIORIDADE!

---
## Épico: Conta

1. **Cadastro e Login**
	- **História de Usuário:** "Como cidadão, quero me cadastrar e entrar na minha conta, para acessar recursos personalizados como progresso em cursos."
	- **Regras de Negócio:** dados obrigatórios (nome, e-mail, senha) não podem ficar vazios; e-mail deve ser único no sistema; senha deve seguir critério mínimo de segurança.
	- **Critério de Aceite:** usuário consegue criar conta e logar com as credenciais cadastradas.
> Prioridade: Deve (Alta)

2. **Perfil**
	- **História de Usuário:** "Como cidadão, quero visualizar e editar meu perfil, para manter meus dados atualizados."
	- **Regras de Negócio:** usuário não pode alterar suas próprias permissões de acesso; campos obrigatórios não podem ficar vazios ao editar.
> Prioridade: Deveria (Média)

3. **Recuperação de Senha**
	- **História de Usuário:** Como cidadão, quero recuperar minha senha caso a esqueça, para não perder acesso à conta.
	- **Regras de Negócio:** nova senha deve seguir os mesmos critérios mínimos de segurança do cadastro.
> Prioridade: Poderia (Baixa)


---
## Épico: Feed de Notícias

4. **Visualizar Feed**
	- **História de Usuário:** Como cidadão, quero ver um feed de notícias ao abrir o app, para me manter informado.
	- **Regras de Negócio:** apenas notícias publicadas/aprovadas aparecem no feed; ordenação por data (mais recente primeiro).
> Prioridade: Deve (Alta)

5. **Ler Notícia**
	- **História de Usuário:** Como cidadão, quero abrir uma notícia e ler seu conteúdo completo, para me aprofundar no assunto.
	- **Regras de Negócio:** notícia deve exibir título, conteúdo, autor e data de publicação.
> Prioridade: Deve (Alta)


---
## Épico: Cursos

6. **Lista de Cursos**
	- **História de Usuário:** Como cidadão, quero ver os cursos disponíveis, para escolher o que aprender.
	- **Regras de Negócio:** apenas cursos publicados/ativos aparecem na lista.
> Prioridade: Deve (Alta)

7. **Módulos do Curso**
	- **História de Usuário:** Como cidadão, quero ver os módulos de um curso, para entender a estrutura do aprendizado.
	- **Regras de Negócio:** um curso é composto por um ou mais módulos, exibidos em ordem definida.
> Prioridade: Deve (Alta)

8. **Conteúdo do Módulo**
	- **História de Usuário:** Como cidadão, quero acessar o conteúdo de um módulo, para aprender os conceitos.
> Prioridade: Deve (Alta)

9. **Progresso do Curso**
	- **História de Usuário:** Como cidadão, quero marcar um módulo como concluído, para acompanhar meu progresso.
	- **Regras de Negócio:** progresso é individual por usuário; módulos concluídos permanecem registrados mesmo após sair do app.
> Prioridade: Deveria (Média)

10. **Quiz de Fixação por Módulo**
	- User Story: Como cidadão, quero responder um quiz curto ao final de um módulo, para checar se entendi o conceito.
	- Regras de Negócio: quiz não bloqueia avanço no curso (é reforço, não barreira); resultado é individual e compartilhado publicamente.
> Prioridade: Deveria (Média)


---
## Épico: Denúncias

11. **Guias por Tema**
	- **História de Usuário:** Como cidadão, quero ver guias de denúncia organizados por tema, para saber como denunciar algo específico.
	- **Regras de Negócio:** cada guia pertence a exatamente um tema principal.
> Prioridade: Deve (Alta)

12. **Conteúdo do Guia**
	- **História de Usuário:** Como cidadão, quero abrir um guia e ver o passo a passo, para saber exatamente o que fazer.
	- **Regras de Negócio:** guia deve indicar o canal/órgão oficial responsável por aquele tipo de denúncia.
> Prioridade: Deve (Alta)

13. **Filtrar por Tema**
	- **História de Usuário:** Como cidadão, quero filtrar guias de denúncia por tema, para encontrar rapidamente o que se aplica ao meu caso.
> Prioridade: Deveria (Média)


---
## Épico: Pesquisa

14. **Buscar por Nome**
	- **História de Usuário:** Como cidadão, quero pesquisar conteúdo por nome/palavra-chave, para encontrar algo sem navegar pelo menu.
	- **Regras de Negócio:** busca considera título do conteúdo; apenas conteúdos ativos aparecem nos resultados.
> Prioridade: Deveria (Média)

15. **Filtrar por Tipo**
	- **História de Usuário:** Como cidadão, quero filtrar resultados por tipo de conteúdo (notícia, curso, guia), para refinar minha busca.
> Prioridade: Deveria (Média)


---
## Épico: Engajamento

16. **Comentários**
	- **História de Usuário:** Como cidadão, quero comentar em notícias e cursos, para compartilhar minha opinião.
	- **Regras de Negócio:** apenas usuários autenticados podem comentar; usuário só edita/exclui os próprios comentários; comentários inadequados podem ser removidos por administrador.
> Prioridade: Poderia (Baixa)

17. **Avaliação de Conteúdo**
	- **História de Usuário:** Como cidadão, quero avaliar um conteúdo, para dar meu feedback.
	- **Regras de Negócio:** apenas usuários autenticados podem avaliar; usuário pode alterar sua avaliação depois.
> Prioridade: Poderia (Baixa)

18. **Compartilhar Conteúdo**
	- User Story: Como cidadão, quero compartilhar uma notícia ou resumo de curso nas minhas redes, para engajar outras pessoas com o tema.
	- Regras de Negócio: compartilhamento deve incluir título e link/resumo do conteúdo original.
> Prioridade: Poderia (Baixa)

19. **Notificações**
	- **História de Usuário:** Como cidadão, quero receber notificações sobre novos conteúdos relevantes, para não perder atualizações importantes.
	- **Regras de Negócio:** sistema respeita as preferências de notificação do usuário.
> Prioridade: Poderia (Baixa)