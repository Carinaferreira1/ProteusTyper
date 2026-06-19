# ProteusTyper

O ProteusTyper é uma pipeline bioinformática desenvolvida para identificar, extrair e analisar loci do antigénio O em genomas do género *Proteus*.

## Funcionalidades

- Identificação da espécie
- Extração automática do locus O utilizando os genes fronteira *secB* e *cpxA*
- Anotação genética com Prokka
- Construção de matrizes de presença/ausência
- Geração de heatmaps
- Clustering hierárquico
- Comparação com uma base de referência
- Validação através de BLAST

## Dados de Entrada

- Ficheiros GenBank (.gbff)

## Resultados Produzidos

- Loci O extraídos
- Genes anotados
- Matrizes de presença/ausência
- Heatmaps
- Dendrogramas de clustering
- Resultados de tipagem

## Enquadramento

O antigénio O corresponde à região mais variável do lipopolissacarídeo (LPS) das bactérias Gram-negativas. Em *Proteus spp.*, os genes responsáveis pela sua biossíntese encontram-se agrupados no locus O, normalmente delimitado pelos genes conservados *secB* e *cpxA*.

O ProteusTyper foi desenvolvido para automatizar a identificação, extração e análise desta região genómica, facilitando estudos de tipagem molecular e caracterização genética.

## Relatório do Projeto

O relatório final do projeto encontra-se disponível em:

```text
ProteusTyper_Report.pdf
