# Transfer Learning para Classificação de Gatos e Cachorros

Este projeto foi desenvolvido como parte de um desafio do bootcamp para praticar conceitos de aprendizado de máquina. O objetivo foi utilizar **Transfer Learning** para adaptar uma rede neural pré-existente, com o modelo VGG16, para realizar a predição de imagens de **gatos** e **cachorros**.

## Tecnologias Utilizadas:
- **Python**
- **Keras**
- **NumPy**
- **TensorFlow Datasets**
- **Matplotlib**

O modelo VGG16 foi carregado com pesos pré-treinados no ImageNet, e as camadas finais foram adaptadas para o problema de classificação binária. O dataset utilizado foi o **Cats vs Dogs** do TensorFlow Datasets, que contém imagens de gatos e cachorros.

### Como Funciona:
1. **Transfer Learning**: A rede VGG16 foi utilizada com seus pesos pré-treinados para extrair características da imagem, e camadas adicionais foram adicionadas para adaptar o modelo à tarefa de classificação binária.
2. **Treinamento**: O modelo foi treinado no dataset de imagens de gatos e cachorros com um conjunto de dados de treino e validação.
3. **Predição**: O modelo foi utilizado para fazer previsões sobre novas imagens de gatos (0) e cachorros (1).

### Objetivo:
O objetivo principal deste projeto foi entender como usar Transfer Learning para aproveitar modelos treinados em grandes bases de dados e aplicá-los a problemas específicos com poucas mudanças na arquitetura.

### 💻 **Bootcamp**: [BairesDev - Machine Learning Practitioner]
