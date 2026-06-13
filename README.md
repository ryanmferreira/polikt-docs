# Polikt

> **Status:** Em fase de planejamento / Desenvolvimento a iniciar

O Polikt é uma aplicação web voltada para a conscientização política, permitindo que os usuários se informem sobre funções públicas, cargos políticos e suas responsabilidades, promovendo uma participação mais ativa na sociedade.

---

**Gestão do Projeto:** [Backlog / Kanban - GitHub Project](https://github.com/users/ryanmferreira/projects/5)

## Repositórios do Ecossistema

| Componente       | Link do Repositório                                               | Descrição                                          |
| :---             | :---                                                              | :---                                               |
| **Documentação** | [polikt-docs](https://github.com/ryanmferreira/polikt-docs)       | Central de artefatos, diagramas e planejamento.    |
| **Front-End**    | [polikt-angular](https://github.com/ryanmferreira/polikt-angular) | Interface web da aplicação desenvolvida em Angular.|
| **Back-End**     | [polikt-api](https://github.com/ryanmferreira/polikt-api)         | API REST desenvolvida em Java com Spring Boot.     |

---

## Ambiente de Desenvolvimento e Stack

| Tecnologia / Ferramenta | Versão / Release  | Escopo / Camada                       |
| :---                    | :---              | :---                                  |
| **Node.js**             | `v24.x`           | Ambiente de Execução (Front-end)      |
| **Angular**             | `v21.2.x`         | Framework da Interface Web            |
| **OpenJDK**             | `v25`             | Ambiente de Execução (Back-end)       |
| **Spring Boot**         | `v4.0.6`          | Framework da API REST (Java)          |
| **PostgreSQL**          | `v18.x`           | Sistema Gerenciador de Banco de Dados |
| **Apache Maven**        | `v3.9.x`          | Ferramenta de automação de build      |

---

## Ferramentas de Desenvolvimento Recomendadas (IDEs)

A equipe poderá optar por duas abordagens de ambiente de desenvolvimento:

### Opção A: Visual Studio Code

Para os integrantes que utilizarem o [VS Code](https://code.visualstudio.com/), é necessária a instalação dos seguintes pacotes de extensões para suporte adequado às linguagens e frameworks:

* **Java:** [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
* **Spring Boot:** [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=vmware.vscode-boot-dev-pack)
* **Angular:** [Angular Extension Pack](https://marketplace.visualstudio.com/items?itemName=loiane.angular-extension-pack)

### Opção B: Ecossistema JetBrains

* **Back-end (Java/Spring):** [IntelliJ IDEA](https://www.jetbrains.com/idea/). O suporte ao ecossistema Java, bem como ao Spring Boot e gerenciadores de build como Maven é nativo, dispensando configurações externas.
* **Front-end (Angular):** O IntelliJ IDEA não possui suporte integrado a TypeScript e Angular. Como alternativa específica para a camada cliente, pode-se utilizar o [WebStorm](https://www.jetbrains.com/webstorm/).

> **Nota:** Estudantes possuem direito ao licenciamento gratuito das versões com recursos completos (Ultimate) através do programa JetBrains Educational Pack. Pode-se validar a conta com os benefícios do GitHub Education.

---

## Integrantes da Equipe e Funções

| Nome do Integrante      | Papel / Função Principal |
| :---                    | :---                     |
| **Ryan Ferreira**       | Full Stack Developer     |
| **Murilo Andrade**      | Front-end Developer      |
| **Moisés Lima**         | Product Owner            |
| **Pedro Aguiar**        | -                        |
| **Miguel Fredo**        | -                        |

---

## Conceito de Pronto (Definition of Done - DoD)

Para que uma funcionalidade ou tarefa contida no backlog seja considerada oficialmente concluída, ela deve cumprir os seguintes critérios estabelecidos:

1. **Totalidade do Escopo:** Implementação integral de todos os requisitos e critérios de aceitação definidos na respectiva issue ou card.
2. **Desempenho e Usabilidade:** Apresentação de interface responsiva e tempos de resposta adequados às diretrizes do projeto.
3. **Peer Review:** O código e a respectiva funcionalidade devem ser obrigatoriamente testados e validados por um integrante diferente do autor original do artefato.
