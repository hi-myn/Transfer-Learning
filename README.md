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

### 💻 Este projeto foi desenvolvido para fins de aprendizado 

<br>**English version**
# Transfer Learning for Cat and Dog Classification

This project was developed as part of a bootcamp challenge to practice machine learning concepts. The aim was to use **Transfer Learning** to adapt a pre-existing neural network, with the VGG16 model, to predict images of **cats** and **dogs**.

## Technologies Used:
- **Python**
- **Keras**
- **NumPy**
- **TensorFlow Datasets**
- **Matplotlib**

The VGG16 model was loaded with pre-trained weights in ImageNet, and the final layers were adapted for the binary classification problem. The dataset used was **Cats vs Dogs** from TensorFlow Datasets, which contains images of cats and dogs.

### How it works:
1. **Transfer Learning: The VGG16 network was used with its pre-trained weights to extract features from the image, and additional layers were added to adapt the model to the binary classification task.
2. **Training: The model was trained on the dataset of cat and dog images with a training and validation dataset.
3. **Prediction: The model was used to make predictions about new images of cats (0) and dogs (1).

### Objective:
The main objective of this project was to understand how to use Transfer Learning to take advantage of models trained on large databases and apply them to specific problems with few changes to the architecture.

### 💻 Este projeto foi desenvolvido para fins de aprendizado 


Translated with DeepL.com (free version)
