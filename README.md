# 💧 Linguagem da Água - NotebookLM

## Contexto

Este projeto foi desenvolvido como parte do desafio da DIO sobre uso do NotebookLM como ferramenta de aprendizagem ativa.

O tema escolhido foi a segurança hídrica do Estado de São Paulo, explorando como Inteligência Artificial, Grafos de Conhecimento e análise hidrológica podem ser utilizados para interpretar informações relacionadas ao abastecimento de água.

A proposta surgiu a partir da observação de que diversas informações relevantes sobre reservatórios, rios, chuvas e consumo estão distribuídas em diferentes fontes e raramente são analisadas em conjunto.

---

# Objetivos

## Objetivo Principal

Construir uma base de conhecimento sobre segurança hídrica utilizando o NotebookLM como ferramenta de estudo e organização do conhecimento.

## Objetivos Específicos

- Entender o funcionamento dos sistemas produtores de água.
- Estudar a relação entre chuva e abastecimento.
- Explorar conceitos de Grafos de Conhecimento.
- Utilizar IA para acelerar a aprendizagem.
- Criar uma biblioteca de prompts reutilizáveis.
- Desenvolver o conceito experimental denominado "Linguagem da Água".

---

# Tema de Estudo

## Linguagem da Água

A Linguagem da Água é um conceito proposto para representar eventos hidrológicos como entidades conectadas.

Exemplo:

CHUVA
↓
RIO
↓
BACIA
↓
RESERVATÓRIO
↓
ABASTECIMENTO

O objetivo é compreender como os diferentes componentes do sistema hídrico interagem entre si.

---

# Curadoria de Fontes

As seguintes fontes foram selecionadas para o NotebookLM:

## ANA

https://www.gov.br/ana

Agência Nacional de Águas e Saneamento Básico.

---

## SABESP

https://www.sabesp.com.br

Responsável pelos sistemas produtores da Região Metropolitana de São Paulo.

---

## DAEE

https://cth.daee.sp.gov.br

Painéis de monitoramento hidrológico.

---

## INMET

https://www.inmet.gov.br

Dados meteorológicos e climatológicos.

---

## CEMADEN

https://www.gov.br/cemaden

Monitoramento de riscos naturais e eventos extremos.

---

# Engenharia de Prompts

## Prompt 1

Como a chuva em Joanópolis influencia o Sistema Cantareira?

### Objetivo

Entender a relação entre municípios da bacia e a recuperação dos reservatórios.

### Aprendizado

Prompts geograficamente específicos produzem respostas mais úteis.

---

## Prompt 2

Explique a diferença entre afluência e defluência utilizando exemplos práticos.

### Objetivo

Aprender conceitos hidrológicos fundamentais.

### Aprendizado

Solicitar exemplos melhora a compreensão.

---

## Prompt 3

Monte um grafo de conhecimento relacionando rios, reservatórios e abastecimento.

### Objetivo

Explorar relações entre entidades.

---

# Cicatrizes e Aprendizados

## Problema

Perguntas muito genéricas produziam respostas superficiais.

### Exemplo

"Como está a água em São Paulo?"

### Resultado

Resposta ampla e pouco útil.

---

## Solução

Adicionar contexto específico:

- Município
- Rio
- Reservatório
- Bacia

### Resultado

Respostas mais técnicas e relevantes.

---

# Miniguia de Estudo

## Sistemas Produtores

### Cantareira

Principal sistema produtor da RMSP.

Principais rios:

- Jaguari
- Jacareí
- Cachoeira
- Atibainha
- Juqueri

---

### Guarapiranga

Importante sistema produtor da região sul da capital.

Principais rios:

- Embu-Guaçu
- Embu-Mirim
- Capivari

---

### Billings

Sistema estratégico para abastecimento e regularização hídrica.

Principais contribuintes:

- Rio Grande
- Taquacetuba
- Rio Pequeno

---

# Glossário

## Afluência

Quantidade de água que entra em um reservatório.

---

## Defluência

Quantidade de água que sai de um reservatório.

---

## Bacia Hidrográfica

Área responsável por coletar e direcionar água para um rio ou reservatório.

---

## Knowledge Graph

Estrutura de dados baseada em entidades e relacionamentos.

---

## Segurança Hídrica

Capacidade de garantir abastecimento adequado para a população.

---

# Biblioteca de Prompts

## Análise Hidrológica

Analise a relação entre chuva, bacia hidrográfica e reservatório para o município informado.

---

## Segurança Hídrica

Explique como o volume atual dos reservatórios pode impactar o abastecimento.

---

## Grafo de Conhecimento

Liste as entidades e conexões relacionadas ao município informado.

---

# Próximos Passos

- [ ] Inserir documentos no NotebookLM.
- [ ] Gerar resumos automáticos.
- [ ] Construir grafo de conhecimento.
- [ ] Evoluir o conceito da Linguagem da Água.
- [ ] Criar painel colaborativo de monitoramento hídrico.

---

# Conclusão

O NotebookLM demonstrou ser uma ferramenta poderosa para organizar conhecimento, consolidar fontes e apoiar a construção de estudos interdisciplinares.

Este projeto representa a primeira etapa de uma iniciativa maior que pretende conectar Inteligência Artificial, dados hidrológicos e ciência aberta em um ambiente colaborativo de aprendizagem.
