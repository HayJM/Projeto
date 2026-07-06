# Projeto de Processamento de Imagens

Este repositório reúne a base de imagens e os materiais utilizados na disciplina de Processamento Digital de Imagens (PDI). O objetivo do trabalho é aumentar a variabilidade e a quantidade de imagens da base original em 3 vezes, aplicando transformações de intensidade e filtragem espacial linear.

## Objetivo

O fluxo principal do projeto realiza:

- transformação logarítmica para expansão de contraste;
- transformação exponencial, também usada como correção gama;
- filtro da média por convolução com kernel `5 x 5`;
- organização dos resultados em uma base ampliada.

## Estrutura do repositório

- `00_Cherry_Tomatoes/` a `09_Tangerine/`: pastas com as classes da base de imagens.
- `metadados_imagens.csv`: metadados das imagens, com colunas como nome do arquivo, classe, ângulo de captura e tipo de fundo.
- `Notebok.ipynb`: notebook principal com a implementação do processamento.
- `Tabela.txt`: legenda das classes e das variações de captura.
- `relatorio/`: arquivos do relatório em LaTeX e materiais auxiliares.
- `Prj-PDI-EC-001.pdf`: enunciado/documento do projeto.

## Classes da base

As classes presentes no conjunto de dados são:

- `00` Cherry Tomatoes
- `01` Fig
- `02` Gala Apple
- `03` Pear
- `04` Persimmon
- `05` Pitanga
- `06` Pomegranate
- `07` Sicilian Lemon
- `08` Strawberry
- `09` Tangerine

## Convenções dos metadados

O arquivo `metadados_imagens.csv` usa a seguinte lógica de codificação:

- `V1` = side view
- `V2` = top view
- `B` = black background
- `W` = white background

## Como usar

1. Abra o notebook `Notebok.ipynb` em Jupyter Notebook, JupyterLab ou Google Colab.
2. Verifique se as pastas das classes permanecem no mesmo nível do notebook.
3. Execute as células em ordem para reproduzir o processamento e gerar a base ampliada.

## Relatório

O relatório do trabalho está em `relatorio/Projeto.tex`. Ele descreve a formalização matemática das transformações e a estrutura de execução adotada.

## Observações

- A base está organizada por classe em diretórios separados.
- O projeto foi pensado para ser reproduzido localmente ou em ambiente online, como o Google Colab.
- Caso você queira, este README pode ser adaptado para formato mais acadêmico ou mais curto, conforme a entrega exigida.