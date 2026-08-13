# Dicionário de Dados

## Objetivo

Este documento descreve as principais bases utilizadas no dashboard e o significado analítico de seus campos.

| Base | Campo | Tipo | Descrição |
|---|---|---|---|
| Anual | ano | inteiro | Ano da coprodução |
| Anual | coproducoes | inteiro | Quantidade de coproduções no ano |
| Países | país | texto | País participante da coprodução |
| Países | total | inteiro | Número de ocorrências no levantamento |
| Bilheteria BR | ano | inteiro | Ano de lançamento |
| Bilheteria BR | título | texto | Título da obra |
| Bilheteria BR | salas | inteiro | Número de salas informado |
| Bilheteria BR | máximo de salas | inteiro | Maior número de salas no lançamento |
| Bilheteria BR | público | inteiro | Número de espectadores |
| Bilheteria BR | renda | monetário | Receita registrada |
| Audiência AR | ano | inteiro | Ano |
| Audiência AR | espectadores | inteiro | Público registrado |
| Gêneros | gênero | texto | Categoria de gênero |
| Gêneros | percentual | decimal | Percentual apresentado pela pesquisa |
| Plataformas | plataforma | texto | Serviço de distribuição |
| Plataformas | modalidade | texto | SVOD ou TVOD |
| Plataformas | títulos | inteiro | Quantidade identificada |
| Disponibilidade | status | texto | Disponível / não disponível |
| Disponibilidade | quantidade | inteiro | Quantidade de obras |
| Produtoras BR | produtora | texto | Empresa produtora brasileira |
| Produtoras BR | coproduções | inteiro | Número de ocorrências |
| Produtoras estrangeiras | produtora | texto | Empresa coprodutora estrangeira |
| Produtoras estrangeiras | coproduções | inteiro | Número de ocorrências |

## Observações

- O significado de cada campo depende do recorte da pesquisa original.
- Dados de plataforma correspondem ao levantamento realizado em setembro de 2023.
- Os percentuais de gênero seguem a organização apresentada no TCC.
- O dashboard preserva a estrutura do levantamento original para manter rastreabilidade.

## Fontes principais

- ANCINE / OCA
- INCAA
- bases complementares utilizadas na pesquisa original

Consulte `METODOLOGIA.md` para detalhes sobre a origem e o tratamento das informações.
