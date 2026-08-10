# Consciência Política e Cidadania

**FATEC Itu – Dom Amaury Castanho**

**Local:** Itu  
**Ano:** 2026

## Integrantes

- Miguel Fredo
- Moisés Lima
- Murilo Andrade
- Pedro Aguiar
- Ryan Ferreira

---

# Sumário

1. [Introdução](#1-introdução)
   - [1.1 Contexto](#11-contexto)
   - [1.2 Problema](#12-problema)
   - [1.3 Objetivo](#13-objetivo)
   - [1.4 Justificativa](#14-justificativa)
2. [Projeto](#2-projeto)
   - [2.1 Técnicas de Levantamento de Requisitos](#21-técnicas-de-levantamento-de-requisitos)
   - [2.2 Análise de Similares](#22-análise-de-similares)
3. [Requisitos](#3-requisitos)
   - [3.1 Requisitos Funcionais (RF)](#31-requisitos-funcionais-rf)
   - [3.2 Requisitos Não Funcionais (RNF)](#32-requisitos-não-funcionais-rnf)
4. [Anexos](#4-anexos)
   - [Anexo A – Formulário para Levantamento de Informações](#anexo-a--formulário-para-levantamento-de-informações)
5. [Referências](#5-referências)

---

# 1. Introdução

## 1.1 Contexto

O projeto surge em um ano eleitoral, período este em que decisões políticas ganham maior visibilidade e maior impacto direto na vida da população. Nesse cenário, se torna fundamental promover o acesso à informação de forma simples, acessível e digital.

## 1.2 Problema

Observa-se que jovens entre 16 e 22 anos (eleitores iniciantes e cidadãos em formação) não possuem o conhecimento necessário sobre o funcionamento do sistema político e os mecanismos de exercício da cidadania, muitas vezes devido à linguagem técnica e conteúdos densos.

## 1.3 Objetivo

Diante disso, o projeto tem como objetivo desenvolver uma solução que:

- Conscientize o público sobre os cargos políticos e suas respectivas funções;
- Explique direitos e deveres do cidadão;
- Oriente sobre como abrir solicitações junto a órgãos públicos;
- Ensine como denunciar irregularidades e acompanhar demandas.

## 1.4 Justificativa

O acesso à informação de qualidade é essencial para decisões conscientes, ainda mais em anos eleitorais. A falta de conhecimento político pode resultar em escolhas desinformadas, baixa participação social - no caso, se refere à jovens de 16~18 anos que às vezes não exercem seu direito de voto por falta de conhecimento - e dificuldade na cobrança por direitos.

Assim, o projeto se justifica pela necessidade de fortalecer a educação política e contribuir para a formação de cidadãos mais participativos e informados na construção de uma sociedade mais funcional.

---

# 2. Projeto

## 2.1 Técnicas de Levantamento de Requisitos

### Pesquisa Quantitativa (Questionário)

Aplicação de formulário estruturado com respondentes do público-alvo (16-22 anos) para validação de dor e interesse.

### Análise de Documentos

Estudo da legislação eleitoral e manuais de transparência pública para basear o "Tradutor de Notícias".

---

## 2.2 Análise de Similares

Para o desenvolvimento do projeto, foram analisadas quatro plataformas que atuam no cenário de cidadania e política, identificando seus focos e limitações:

### Politize! (Educação)

Possui foco em educação política com a vantagem de utilizar uma linguagem simples e didática.

Entretanto, apresenta a desvantagem de poder parecer denso ou excessivamente "escolar" para o público jovem.

### Ranking (Fiscalização)

Focado na fiscalização de políticos através de notas, votos e histórico de corrupção.

Como pontos negativos, apresenta algumas métricas insuficientes e diversos problemas técnicos na plataforma.

### Colab (Zeladoria)

Plataforma voltada para o relato de problemas urbanos (zeladoria).

Suas principais desvantagens são:

- Baixa adesão;
- Interface confusa;
- Falta de parceria direta com prefeituras.

> **Observação:** Inserir print do Colab quando a plataforma estiver disponível.

### Participa+ (Consulta)

Canal oficial do governo para consultas públicas.

Apesar da credibilidade, a plataforma é excessivamente burocrática para o usuário comum.

---

# 3. Requisitos

## 3.1 Requisitos Funcionais (RF)

### RF01 - Feed Personalizado

**Origem e Contexto:**  
Com base na burocracia observada no similar Participa+, é necessário um sistema que filtre informações para reduzir a complexidade.

**Descrição:**  
O sistema deve exibir notícias filtradas por temas de interesse e localização, garantindo que o usuário receba informações pertinentes à sua região e preferências.

**Prioridade:** Essencial.

---

### RF02 – Tradutor de Notícias

**Origem e Contexto:**  
Com base na preferência por linguagem simples identificada no formulário de pesquisa, é necessário um módulo que facilite a compreensão técnica.

**Descrição:**  
Para cada notícia exibida, o sistema deve apresentar um resumo simplificado que explique, em linguagem clara, o impacto direto daquela informação no cotidiano do usuário.

**Prioridade:** Essencial.

---

### RF03 – Trilhas de Conhecimento

**Origem e Contexto:**  
Com base na alta demanda por recursos visuais apontada no formulário, é necessário organizar o conteúdo de forma didática.

**Descrição:**  
O sistema deve organizar o conteúdo didático em trilhas sequenciais, utilizando recursos visuais como infográficos e diagramas para facilitar a absorção do conteúdo.

**Prioridade:** Essencial.

---

### RF04 – Mural de Infraestrutura

**Origem e Contexto:**  
Com base na baixa adesão de similares como o Colab, é necessário um espaço mais intuitivo para o engajamento do cidadão.

**Descrição:**  
O usuário deve ter a capacidade de postar fotos e descrições detalhadas de problemas urbanos, integrando dados de localização automática.

**Prioridade:** Importante.

---

### RF05 – Guia de Denúncia

**Origem e Contexto:**  
Com base no desconhecimento sobre como exercer a cidadania relatado no formulário, o sistema deve orientar o registro de queixas oficiais.

**Descrição:**  
Ao selecionar um problema de infraestrutura, o aplicativo deve exibir um passo a passo detalhado indicando como e onde registrar a queixa oficial nos órgãos competentes.

**Prioridade:** Essencial.

---

### RF06 – Busca e Filtros

**Origem e Contexto:**  
Com base na interface confusa de similares como o Colab, é necessário facilitar o acesso aos dados relatados.

**Descrição:**  
O sistema deve permitir que o usuário filtre os problemas relatados no mural por bairro, categoria de falha ou data de publicação.

**Prioridade:** Importante.

---

### RF07 – Perfil do Usuário

**Origem e Contexto:**  
Com base no perfil de formação do público-alvo identificado no formulário, é necessário uma área para controle de progresso.

**Descrição:**  
O sistema deve oferecer uma área personalizada onde o usuário possa salvar suas trilhas favoritas e acompanhar seu progresso de aprendizado.

**Prioridade:** Desejável.

---

### RF08 – Notificações

**Origem e Contexto:**  
Com base na falta de agilidade na comunicação do similar Participa+, é necessário manter o usuário atualizado em tempo real.

**Descrição:**  
O sistema deve enviar alertas em tempo real sobre notícias de alto impacto ou atualizações relevantes nos guias de denúncia seguidos pelo usuário.

**Prioridade:** Desejável.

---

### RF09 – Mecanismo de Feedback

**Origem e Contexto:**  
Com base na percepção de dificuldade com conteúdos densos apontada no formulário, é necessário medir a clareza da informação.

**Descrição:**  
O sistema deve permitir que o usuário avalie se uma informação governamental foi "Clara" ou "Confusa", para retornar um feedback de sua eficiência.

**Prioridade:** Importante.

---

## 3.2 Requisitos Não Funcionais (RNF)

### RNF01 - Usabilidade (UX)

**Descrição:**  
A interface deve ser projetada de forma intuitiva e visualmente atraente para o público de 16 a 22 anos, evitando terminologias burocráticas ou estéticas excessivamente acadêmicas.

**Métrica:**  
O usuário deve ser capaz de navegar entre as seções principais com no máximo 3 toques na tela.

**Prioridade:** Essencial.

---

### RNF02 - Acessibilidade

**Descrição:**  
O sistema deve ser compatível com ferramentas de leitura de tela e possuir esquemas de cores que garantam contraste adequado para usuários com baixa visão ou daltonismo.

**Prioridade:** Essencial.

---

### RNF03 - Escalabilidade

**Descrição:**  
A arquitetura do banco de dados e do servidor deve ser capaz de suportar um aumento repentino no volume de dados e acessos simultâneos, especialmente no Mural de Infraestrutura.

**Prioridade:** Importante.

---

### RNF04 - Desempenho

**Descrição:**  
O aplicativo deve manter sua funcionalidade central otimizada, garantindo carregamento rápido mesmo em dispositivos com hardware limitado ou conexões de rede 4G instáveis.

**Métrica:**  
O tempo de carregamento da tela inicial e do feed não deve ultrapassar 3 segundos.

**Prioridade:** Essencial.

---

# 4. Anexos

## Anexo A – Formulário para Levantamento de Informações

Pesquisa quantitativa realizada com jovens para validar o nível de conhecimento político e engajamento com zeladoria urbana.

### Resultados

[Resultados da pesquisa](https://docs.google.com/forms/d/1FjxiWPiAaYZQAxawRgJvHNZJJnKXRDofGvRVofGj1YE/viewanalytics)

---

# 5. Referências

- **POLITIZE!** Portal de Educação Política. Disponível em: https://www.politize.com.br/. Acesso em: 19 mar. 2026.

- **RANKING POLÍTICO.** Comparador de atuação parlamentar. Disponível em: https://www.politicos.org.br/. Acesso em: 19 mar. 2026.

- **COLAB.** Plataforma de Zeladoria Urbana e Cidadania Digital. Disponível em: https://www.colab.re/. Acesso em: 19 mar. 2026.

- **PARTICIPA+.** Plataforma de participação social do Governo Federal. Disponível em: https://www.gov.br/participamaisbrasil. Acesso em: 19 mar. 2026.