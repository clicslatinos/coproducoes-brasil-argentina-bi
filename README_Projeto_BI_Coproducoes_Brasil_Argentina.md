#  Coproduções Cinematográficas Brasil–Argentina

## Case de Análise de Dados e Business Intelligence

> **Da pesquisa acadêmica ao portfólio de dados.**

Este repositório apresenta a transformação de uma pesquisa desenvolvida no Trabalho de Conclusão de Curso em **Cinema e Audiovisual pela Universidade Estadual de Goiás (UEG)** em um case de análise e visualização de dados.

O projeto analisa **53 coproduções cinematográficas Brasil–Argentina**, no período de **2012 a 2021**, observando produção, participação majoritária/minoritária, mercado, circulação, gêneros, produtoras e disponibilidade digital.

---

##  Resumo do projeto

| Indicador | Resultado |
|---|---:|
| Corpus | **53 coproduções** |
| Participação majoritária | **17** |
| Participação minoritária | **36** |
| Recorte principal | **2012–2021** |
| Fontes institucionais | **ANCINE/OCA + INCAA** |
| Ferramenta do dashboard | **Excel** |
| Tipo de projeto | **Data Analysis / BI Portfolio Case** |

---

##  Pergunta central

**De que modo se articulam os mercados de cinema brasileiro e argentino no período analisado?**

O projeto explora:

- evolução anual das coproduções;
- participação majoritária e minoritária;
- desempenho comercial;
- circulação entre Brasil e Argentina;
- gêneros cinematográficos;
- produtoras;
- distribuição e disponibilidade digital.

---

##  O que este projeto demonstra

Este não é apresentado como um projeto de BI profissional já implementado em Power BI.

Ele é um **primeiro case de portfólio**, construído a partir de uma pesquisa acadêmica, e demonstra competências transferíveis para Dados e BI:

- levantamento de dados em múltiplas fontes;
- organização de informações heterogêneas;
- construção de indicadores;
- análise temporal;
- comparação entre mercados;
- categorização;
- análise de distribuição;
- identificação de padrões;
- visualização de dados;
- storytelling;
- documentação metodológica;
- comunicação executiva;
- identificação de limitações.

---

## ️ Estrutura do repositório

```text
coproducoes-brasil-argentina-bi/
README.md
dashboard/
    Dashboard_Coproducoes_Brasil_Argentina.xlsx
presentation/
    Case_Coproducoes_Brasil_Argentina.pptx
documentation/
    METODOLOGIA.md
    DICIONARIO_DADOS.md
    PROJECT_CARD.md
assets/
```

### Dashboard

O arquivo Excel contém a versão editável do dashboard e suas bases organizadas para exploração.

### Presentation

O PowerPoint apresenta o projeto como um **case executivo**, passando por:

**problema → metodologia → dados → análise → insights → limitações → evolução técnica.**

### Documentation

A documentação explica:

- origem dos dados;
- metodologia;
- fontes;
- recorte;
- definições;
- limitações;
- estrutura conceitual do projeto.

---

##  Metodologia

A pesquisa original combinou:

1. pesquisa bibliográfica;
2. levantamento de dados;
3. organização do corpus;
4. análise comparativa;
5. pesquisa de gêneros;
6. levantamento de disponibilidade digital;
7. entrevistas com produtoras brasileiras.

As principais fontes institucionais foram:

- **ANCINE / Observatório Brasileiro do Cinema e do Audiovisual (OCA);**
- **INCAA — Instituto Nacional de Cine y Artes Audiovisuales.**

Também foram consultadas fontes complementares para gêneros, circulação e disponibilidade digital.

As entrevistas incorporadas à pesquisa incluem:

- Sombumbo Filmes — André Ristum;
- Sancho y Punta — Michael Wahrmann;
- Taiga Filmes — Lucia Murat.

---

##  Principais análises

### Produção

- evolução anual;
- total de coproduções;
- majoritárias × minoritárias;
- países envolvidos.

### Mercado

- público;
- renda;
- número de salas;
- desempenho dos títulos;
- circulação Brasil–Argentina.

### Distribuição

- disponibilidade digital;
- plataformas;
- SVOD;
- TVOD.

### Gêneros

- classificação da ANCINE;
- classificação construída pela pesquisa;
- recorrência de gêneros.

### Redes de produção

- produtoras brasileiras;
- produtoras estrangeiras;
- recorrência das empresas.

---

##  Principais insights

- **2021 concentra o maior volume de coproduções** dentro do recorte.
- **36 das 53 obras são minoritárias**, mostrando predominância dessa modalidade no corpus.
- **Divã A 2** apresenta o maior público no Brasil entre os títulos analisados.
- A circulação e o desempenho variam entre os mercados brasileiro e argentino.
- O levantamento de plataformas identificou disponibilidade para parte do corpus e ausência para outra parte.
- A classificação de gêneros construída pela pesquisa permite uma leitura mais granular do corpus.

Os insights são **descritivos** e não devem ser interpretados como demonstrações de causalidade.

---

## ️ Limitações

### Recorte temporal

O corpus principal corresponde a **2012–2021**.

### Plataformas

O levantamento de disponibilidade digital foi realizado em **setembro de 2023**. Portanto, representa uma fotografia daquele momento.

### Dados internacionais

Existem lacunas em determinados indicadores públicos relacionados ao mercado argentino.

### Entrevistas

As entrevistas representam experiências específicas de produtoras e não constituem uma amostra estatística de todo o setor.

### Causalidade

O projeto identifica padrões e relações, mas não realiza um teste estatístico de causalidade.

### Gêneros

A classificação construída pela pesquisa utiliza múltiplas fontes e pode associar mais de um gênero à mesma obra.

---

## ️ Ferramentas

### Utilizadas no case

- Excel;
- organização e tratamento de bases;
- análise comparativa;
- visualização de dados;
- pesquisa documental;
- apresentação executiva.

### Próxima evolução técnica

A arquitetura conceitual do projeto foi pensada para uma futura implementação em:

- Power BI;
- Power Query;
- DAX;
- modelagem de dados.

**Essas ferramentas não são apresentadas como utilizadas na pesquisa original.**

---

##  Próximos passos do projeto

A evolução natural deste case seria:

### V2 — Power BI

- importar e tratar as bases com Power Query;
- criar modelo relacional;
- construir medidas DAX;
- criar filtros e segmentações;
- implementar drill-down;
- melhorar interatividade.

### V3 — SQL

Criar uma versão do projeto com consultas SQL para demonstrar:

- `SELECT`;
- `WHERE`;
- `GROUP BY`;
- `JOIN`;
- `CASE`;
- CTEs;
- funções de janela.

### V4 — Novo domínio

Construir um segundo case fora do cinema, preferencialmente com um problema de negócio, como:

- marketing;
- vendas;
- atendimento;
- e-commerce;
- RH
- performance.

---

##  Origem

**Trabalho de Conclusão de Curso — Cinema e Audiovisual**  
**Universidade Estadual de Goiás (UEG)**

O dashboard reorganiza os dados e resultados da pesquisa em uma estrutura de análise e visualização adequada para um portfólio de Business Intelligence.

---

## ‍ Autoria

**Ana Luiza Mendes Santos**

Cinema e Audiovisual • Comunicação • Design • Análise e Visualização de Dados

---

##  Transparência

O projeto preserva o corpus e a organização estabelecidos na pesquisa original.

A documentação existe para tornar explícitos:

**fonte, recorte, metodologia, indicador, interpretação e limitação.**

O objetivo é demonstrar não apenas a capacidade de produzir gráficos, mas também a capacidade de **explicar de onde os dados vieram, como foram organizados e o que eles permitem concluir**.
