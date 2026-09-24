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
 
Durante a pesquisa foi utilizado o recurso Deep Research do NotebookLM para identificar fontes oficiais relacionadas à segurança hídrica, saneamento básico, monitoramento meteorológico e prevenção de desastres naturais.
 
## Fontes Principais
 
### Agência Nacional de Águas e Saneamento Básico (ANA)
 
https://www.gov.br/ana
 
Responsável pela regulação e gestão dos recursos hídricos em âmbito nacional, além da produção de estudos, capacitações e normas relacionadas ao saneamento.
 
---
 
### Centro Nacional de Monitoramento e Alertas de Desastres Naturais (CEMADEN)
 
https://www.gov.br/cemaden
 
Monitoramento de eventos extremos, riscos geo-hidrológicos, secas, inundações e emissão de alertas preventivos.
 
---
 
### Sistema Integrado de Bacias Hidrográficas (SIBH)
 
https://www.sibh.sp.gov.br
 
Acompanhamento de precipitação, níveis de rios e informações hidrológicas em tempo real para o estado de São Paulo.
 
---
 
### Agência Nacional de Águas - Monitoramento Hidrológico
 
https://www.snirh.gov.br
 
Sistemas de monitoramento e gestão de recursos hídricos.
 
---
 
### Instituto Nacional de Meteorologia (INMET)
 
https://www.inmet.gov.br
 
Dados meteorológicos, climatológicos e históricos de estações monitoradas em todo o Brasil.
 
---
 
## Justificativa da Escolha
 
As fontes foram selecionadas por apresentarem dados oficiais e atualizados relacionados a:
 
- Recursos hídricos;
- Segurança hídrica;
- Monitoramento de chuvas;
- Gestão de bacias hidrográficas;
- Prevenção de desastres naturais;
- Mudanças climáticas.
 
Essas informações serviram como base para a construção do conceito "Linguagem da Água" desenvolvido durante este estudo.
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
