## Como visualizar o notebook corretamente

O visualizador de notebooks do GitHub pode apresentar erros como  
"The 'state' key is missing from 'metadata.widgets'. Add 'state' to each, or remove 'metadata.widgets'."  
Isso acontece por conta de metadados internos do Colab.

**Como abrir sem erro:**
1. No repositório, clique sobre o arquivo `.ipynb` com o botão direito e selecione “Copiar link”.
2. Acesse [Google Colab](https://colab.research.google.com/).
3. Clique em ‘Arquivo’ > ‘Abrir do GitHub’.
4. Cole o link do notebook e clique em “Abrir”.
5. O notebook vai funcionar normalmente na interface do Colab.

**Alternativa:**  
Faça download do notebook (`.ipynb`) e abra direto no Colab usando ‘Arquivo’ > ‘Fazer upload’.

Se precisar de prints de tela para entrega, utilize o Colab que irá visualizar sem problemas!
---------------------------------------------------------------------------------------------------------------



# Projeto Transfer Learning - Cats vs Dogs

Este projeto utiliza Transfer Learning com Deep Learning, usando Python e Google Colab, para classificar imagens de gatos e cachorros.

## Objetivo

- Aplicar Transfer Learning usando MobileNetV2
- Demonstrar classificação binária com imagens reais

## Como usar

Abra o notebook `.ipynb` neste repositório no Google Colab e execute as células.

## Resultados

- O modelo atingiu boa acurácia após algumas épocas de treinamento.
- Foram usadas imagens reais do dataset Cats vs Dogs.

## Prints do projeto

Caso queira, pode adicionar imagens de gráficos ou exemplos de classificação (coloque na pasta `/images`).

## Referências

- [Dataset Cats vs Dogs](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs)
- [Notebook base utilizado](https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb)
