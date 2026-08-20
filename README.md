# Polikt

> **Status:** Em fase de planejamento / Desenvolvimento a iniciar

O Polikt é um aplicativo mobile voltado para a conscientização política, permitindo que os usuários se informem sobre funções públicas, cargos políticos e suas responsabilidades, promovendo uma participação mais ativa na sociedade.

Atualmente, o projeto possui como foco o desenvolvimento para dispositivos móveis.

---

**Gestão do Projeto:** [Backlog / Kanban - Trello](https://trello.com/invite/b/6a6fe2f3885ec7dffdc9bb73/ATTI627b2264c88ac6c6f33b9fe4bf30fe91F4379760/polikt)

## Repositórios do Ecossistema

| Componente       | Link do Repositório                                         | Descrição                                               |
| :--------------- | :---------------------------------------------------------- | :------------------------------------------------------ |
| **Documentação** | [polikt-docs](https://github.com/ryanmferreira/polikt-docs) | Central de artefatos, diagramas e planejamento.         |
| **Mobile**       | [polikt-expo](https://github.com/ryanmferreira/polikt-expo) | Aplicativo mobile desenvolvido com Expo e React Native. |
| **Back-End**     | [polikt-spring](https://github.com/ryanmferreira/polikt-spring)   | API REST desenvolvida em Java com Spring Boot.          |

---

## Ambiente de Desenvolvimento e Stack

| Tecnologia / Ferramenta | Versão / Release | Escopo / Camada                       |
| :---------------------- | :--------------- | :------------------------------------ |
| **Node.js**             | `v24.x`          | Ambiente de Execução (Front-end)      |
| **Expo**                | `v57`            | Framework (TypeScript / React Native) |
| **OpenJDK**             | `v25`            | Ambiente de Execução (Back-end)       |
| **Spring Boot**         | `v4.0.x`         | Framework da API REST (Java)          |
| **PostgreSQL**          | `v18.x`          | Sistema Gerenciador de Banco de Dados |
| **Apache Maven**        | `v3.9.x`         | Ferramenta de automação de build      |

---

## Ferramentas de Desenvolvimento Recomendadas (IDEs)

A equipe poderá optar por diferentes ambientes de desenvolvimento de sua preferência, de acordo com a camada do projeto.

### Visual Studio Code

Para os integrantes que utilizarem o [VS Code](https://code.visualstudio.com/), são recomendadas as seguintes extensões:

#### Front-end

- **Expo Tools:** [Expo Tools](https://marketplace.visualstudio.com/items?itemName=expo.vscode-expo-tools)
- **React Native:** [React Native Tools](https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native)

#### Back-end

- **Java:** [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
- **Spring Boot:** [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=vmware.vscode-boot-dev-pack)
- **Bruno:** [Bruno](https://marketplace.visualstudio.com/items?itemName=bruno-api-client.bruno)
- **PostgreSQL:** [PostgreSQL](https://marketplace.visualstudio.com/items?itemName=ms-ossdata.vscode-pgsql)

### Ecossistema JetBrains

- **Back-end (Java/Spring):** [IntelliJ IDEA](https://www.jetbrains.com/idea/). O suporte ao ecossistema Java, Spring Boot e Maven é integrado à IDE.
- **Mobile:** pode ser utilizado um editor compatível com o ecossistema JavaScript/TypeScript e React Native, conforme a preferência do integrante.

> **Nota:** Estudantes possuem direito ao licenciamento gratuito das versões com recursos completos (Ultimate) através do programa JetBrains Educational Pack. Pode-se validar a conta com os benefícios do GitHub Education.

---

## Integrantes da Equipe e Funções

| Nome do Integrante | Função Principal         |
| :----------------- | :----------------------- |
| **Ryan Ferreira**  | Full Stack Developer     |
| **Murilo Andrade** | Front-end Developer      |
| **Moisés Lima**    | Front-end Developer      |
| **Pedro Aguiar**   | ~                        |
| **Miguel Fredo**   | ~                        |

---

## Conceito de Pronto (Definition of Done - DoD)

Para que uma funcionalidade ou tarefa contida no backlog seja considerada oficialmente concluída, ela deve cumprir os seguintes critérios estabelecidos:

1. **Totalidade do Escopo:** Implementação integral de todos os requisitos e critérios de aceitação definidos na respectiva issue ou card.
2. **Desempenho e Usabilidade:** Apresentação de interface responsiva e tempos de resposta adequados às diretrizes do projeto.
3. **Peer Review:** O código e a respectiva funcionalidade devem ser obrigatoriamente testados e validados por um integrante diferente do autor original do artefato.

---

## Protótipo do Projeto (Figma)

[Informações do protótipo](prototype/figma_prototype.md)