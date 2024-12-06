# Robô Trading com Inteligência Artificial usando Q-Learning em Python

Este projeto utiliza a técnica de Q-Learning, uma abordagem de aprendizado por reforço, para treinar um robô que realiza operações de compra e venda de ações. Usando dados históricos da Apple (AAPL), o objetivo é maximizar os lucros a partir de um saldo inicial, simulando decisões de trading em um ambiente controlado.

O projeto busca responder à seguinte pergunta: "Dado um saldo inicial e uma série de dados históricos, o robô pode aprender uma estratégia de negociação lucrativa por meio de aprendizado por reforço?"

## Demonstração/Visualização
Gráfico candlestick dos preços históricos da ação para análise inicial.
Representação gráfica do saldo e das decisões do robô (compra, venda ou manutenção) ao longo dos episódios.
Anexo sugerido: GIF do robô em ação durante o treinamento e teste ou imagens dos gráficos gerados.

![Acompanhamento do Jupyter Notebook](link)

## Principais Tecnologias Utilizadas
- Python: Linguagem base para todo o desenvolvimento.
- Pandas e Numpy: Manipulação e análise dos dados históricos.
- Plotly: Visualização interativa dos dados com gráficos candlestick.
- Q-Learning: Técnica de aprendizado por reforço implementada no script.

## Estrutura do Projeto
```
├── tradingBot.ipynb     # Script principal contendo o treinamento e teste do robô
└── dataset.csv          # Arquivo CSV com dados históricos das ações da Apple
```

## Como Executar
1. Instale as Dependências
Certifique-se de que possui Python e Jupyter Notebook instalados e execute o seguinte comando no terminal para instalar as bibliotecas necessárias:
```
pip install pandas numpy plotly
```

2. Abra o Jupyter Notebook
No terminal, navegue até o diretório onde está o arquivo trading_bot.ipynb e execute:
```
jupyter notebook
```

3. Carregue o Notebook
No navegador, selecione o arquivo <code>tradingBot.ipynb</code> para abrir o notebook.

4. Execute o Código
Execute as células do notebook em sequência para treinar e avaliar o robô de trading.

## Funcionalidades
- Carregamento e Visualização de Dados: Gráficos candlestick para análise de preços históricos.
- Treinamento com Q-Learning:
      - Decisões possíveis: Comprar, vender ou manter.
      - Parâmetros ajustáveis: alfa (aprendizado), gama (desconto de recompensas futuras) e epsilon (exploração).
- Teste de Estratégia: Avaliação do robô com base na política aprendida.
- Resultados de Operações: Relatório do saldo final e do lucro acumulado.

## Resultados e Conclusões
Após o treinamento, o robô é capaz de tomar decisões de compra e venda baseadas nos dados históricos e no saldo disponível. O lucro final e o saldo restante indicam a eficácia do modelo em simular operações lucrativas.
      Exemplo de saída:
      - Saldo inicial: $10.000
      - Saldo final: $12.350
      - Lucro acumulado: $2.350
Os resultados mostram que o Q-Learning é uma ferramenta promissora para estratégias de trading automatizadas.

8. Próximos Passos/Melhorias
- Incluir outros indicadores financeiros (e.g., RSI, médias móveis) para melhorar a tomada de decisão.
- Implementar Deep Q-Learning (DQL) para lidar com cenários mais complexos e dados maiores.
- Simular custos reais de transação para análises mais realistas.

<br>
<hr> 

### Currículos e Documentos
Acesse os arquivos disponíveis na pasta 
[![Documentos](https://img.shields.io/badge/DOCUMENTOS-%F0%9F%93%83-blue?style=flat-square)](https://github.com/vitoriapguimaraes/vitoriapguimaraes/tree/main/DOCUMENTOS) para mais informações sobre minhas qualificações e certificações.