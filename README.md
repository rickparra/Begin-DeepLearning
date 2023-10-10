# Classificação de Imagens de Roupas com Keras

Este é um projeto para classificar imagens de diferentes tipos de roupas usando redes neurais convolucionais (CNNs) no Keras.

## Dependências

- Python 3.6 ou superior
- Keras
- OpenCV  
- Matplotlib
- Numpy

## Dataset 

O dataset usado é o [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist), que contém 70.000 imagens em escala de cinza de 28x28 pixels de 10 categorias de roupas diferentes:

- T-shirt/top
- Trouser  
- Pullover
- Dress
- Coat
- Sandal  
- Shirt
- Sneaker
- Bag
- Ankle boot

As imagens estão divididas em conjuntos de treinamento e teste.

## Pré-processamento de Dados

As imagens são normalizadas e os dados são reformatados para entrar na rede neural.

## Modelo CNN

A rede neural convolucional é construída no Keras com as seguintes camadas:

- Conv2D
- MaxPooling2D
- Flatten
- Dense

O modelo é compilado com loss categorical_crossentropy e otimizador adam.

## Treinamento 

O modelo é treinado por 20 épocas com batch size de 128. 

## Avaliação

A acurácia do modelo no conjunto de teste é calculada.

## Predictions

O modelo treinado é usado para fazer previsões em novas imagens. 

## Referências

- [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)
- [Keras Documentation](https://keras.io/)
