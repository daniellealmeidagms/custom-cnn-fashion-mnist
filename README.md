# custom-cnn-fashion-mnist

Creating a custom CNN hypertunned architeture for the Fashion MNIST dataset with Python, Keras and Tensorflow.

The following hyperparameters were selected for hypertuning with the Grid Search with 5-fold cross-validation strategies:
- Amount of hidden layers (Convolution + Max Pooling)
- Number of filters per layer
- Filter size (H x H)
- Pool size (B x B)

The best result found was obtained with the following values:
- Amount of hidden layers (Convolution + Max Pooling): 2
- Number of filters per layer: 64 on layer 1 and 128 on layer 2
- Filter Size: (8 x 8)
- Pool size (3x3)

After training for 30 epochs, an accuracy of 82% was reached in the validation and test sets, demonstrating a high capacity for generalization of the architecture found.

---

Criando uma arquitetura hipertunada e customizada de CNN (Rede Neural Convolucional) para o conjunto de dados Fashion MNIST com Python, Keras e Tensorflow.

Foram selecionados para hypertuning com as estratégias Grid Search e Validação Cruzada 5-fold os seguintes hiperparâmetros:
- Quantidade de camadas ocultas (Convolução + Max Pooling)
- Quantidade de filtros por camada
- Tamanho do filtro (A x A)
- Tamanho do pool (B x B)

O melhor resultado encontrado foi obtido com os seguintes valores:
- Quantidade de camadas ocultas (Convolução + Max Pooling): 2
- Quantidade de filtros por camada: 64 na camada 1 e 128 na camada 2
- Tamanho do filtro: (8 x 8)
- Tamanho do pool (3 x 3)

Após um treino de 30 épocas, alcançou-se uma acurácia nos conjuntos de validação e teste de 82%, demonstrando alta capacidade de generalização da arquitetura encontrada.

---

Projeto desenvolvido para o terceiro módulo do curso de Especialização em Inteligência Artifical Aplicada, semestre 2021/2, do Instituto Federal de Goiás - Câmpus Goiânia.
