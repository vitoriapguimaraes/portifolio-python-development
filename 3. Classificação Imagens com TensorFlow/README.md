# Classificação de Imagens com Redes Neurais Convolucionais e TensorFlow
Este projeto desenvolve um modelo de Inteligência Artificial baseado em Redes Neurais Convolucionais (CNNs) para realizar a classificação de imagens em 10 categorias distintas, utilizando o dataset CIFAR-10. O objetivo é permitir que o modelo reconheça corretamente novas imagens pertencentes a categorias como avião, carro, gato, navio, entre outras, promovendo uma aplicação prática de aprendizado profundo.

## Demonstração/Visualização
O arquivo main.ipynb apresenta todas as etapas do desenvolvimento do modelo, desde o pré-processamento dos dados até a avaliação e classificação final. Aqui está um gif apresentando os processos.

![Acompanhamento do Jupyter Notebook](link)

## Principais Tecnologias Utilizadas
- Python: Linguagem base para todo o desenvolvimento.
- TensorFlow/Keras: Para construção e treinamento do modelo de rede neural.
- Matplotlib: Para visualização de dados.
- Pillow (PIL): Para manipulação de imagens.
- NumPy: Para operações numéricas e manipulação de arrays.

## Estrutura do Projeto
```
├── classificarImagem.ipynb       # Notebook principal com todas as etapas do projeto
└── data/                         # Diretório com os dados utilizados (CIFAR-10)
```

## Como Executar
### Pré-requisitos:
- Certifique-se de ter o Python instalado (versão 3.7 ou superior).
- Instale as dependências listadas no arquivo.

1. Carregando o Notebook:
Abra o arquivo main.ipynb em um ambiente como Jupyter Notebook, Google Colab, ou outro de sua preferência.

2. Executando as Etapas:
Certifique-se de rodar todas as células do notebook na ordem, para carregar os dados, treinar o modelo e visualizar os resultados.

3. Classificação de Novas Imagens:
Você pode substituir ou adicionar novas imagens no código para realizar classificações e testar o modelo.

## Funcionalidades
1. Carregamento e Pré-processamento de Dados: O dataset CIFAR-10 é carregado e normalizado para otimizar o treinamento do modelo.
2. Visualização de Dados: Exibe imagens do conjunto de dados para análise inicial.
3. Construção do Modelo: Implementação de uma CNN composta por camadas de convolução, pooling e densas.
4. Treinamento e Avaliação: Treinamento com ajuste de hiperparâmetros e avaliação no conjunto de teste.
5. Classificação de Novas Imagens: Permite a entrada de novas imagens para serem classificadas pelo modelo.

## Resultados e Conclusões
O modelo alcançou uma acurácia de X% no conjunto de teste, demonstrando uma boa capacidade de generalização para identificar as 10 categorias do CIFAR-10. Este projeto destaca o poder das redes neurais convolucionais na tarefa de classificação de imagens.

Próximos Passos/Melhorias
- Aprimoramento do Modelo: Experimentar diferentes arquiteturas, como ResNet ou VGG, para melhorar a acurácia.
- Implementação de Inferência em Tempo Real: Criar uma aplicação web ou desktop para carregar imagens e exibir a classificação do modelo.

<br>
<hr> 

### Currículos e Documentos
Acesse os arquivos disponíveis na pasta 
[![Documentos](https://img.shields.io/badge/DOCUMENTOS-%F0%9F%93%83-blue?style=flat-square)](https://github.com/vitoriapguimaraes/vitoriapguimaraes/tree/main/DOCUMENTOS) para mais informações sobre minhas qualificações e certificações.