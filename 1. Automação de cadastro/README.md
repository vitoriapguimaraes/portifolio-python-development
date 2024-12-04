# Automação de Cadastro de Produtos em Portal Web
Este projeto simplifica o cadastro de produtos em um portal de vendas, automatizando tarefas repetitivas como login e preenchimento de formulários. Com base em um arquivo CSV contendo os dados dos produtos, o script garante eficiência, elimina erros humanos e economiza tempo para operações em massa.

## Demonstração/Visualização
Demonstração em ação: O script acessa automaticamente o portal, faz login, preenche os formulários de cadastro e envia os dados do produto.

![Gif de parte do funcionamento](https://github.com/vitoriapguimaraes/portifolio-python-development/blob/main/1.%20Automa%C3%A7%C3%A3o%20de%20cadastro/AutomacaoCadastro-Demonstracao.gif)

## Principais Tecnologias Utilizadas
- Python: Linguagem principal para o desenvolvimento do script.
- PyAutoGUI: Biblioteca para automação de cliques, digitação e navegação na interface.
- Pandas: Para leitura e manipulação do arquivo CSV contendo os dados dos produtos.

## Estrutura do Projeto
```
├── automacaoCadastro.py             # Script principal para automação do cadastro
├── pegarPosicao.py                  # Script auxiliar para ajustar posições de clique
├── produtos.csv                     # Arquivo CSV contendo os dados dos produtos
└── requirements.txt                 # Arquivo com dependências do projeto
```

## Como Executar
Pré-requisitos:
- Python 3.7 ou superior instalado.
- Navegador Google Chrome ou Microsoft Edge configurado.

Passo a Passo:
1. Instale as dependências:
```
pip install -r requirements.txt
```
2. Configure as posições de clique:
Execute o script <code>pegarPosicao.py</code> para identificar e ajustar as posições de clique com base no seu monitor.
```
python pegarPosicao.p
```

3. Prepare o arquivo CSV:
Insira os dados dos produtos no arquivo <code>produtos.csv</code> (exemplo fornecido no projeto).

4. Execute a automação:

Inicie o script principal:
```
python automacaoCadastro.py
```
O script abrirá o navegador, fará login e realizará o cadastro dos produtos automaticamente.

## Funcionalidades
- Automação de login no portal de vendas.
- Cadastro em lote de produtos com base em um arquivo CSV.
- Personalização de cliques para adaptação a diferentes resoluções de tela.
- Geração de logs para rastreamento do progresso.

## Resultados e Conclusões
O script automatiza com sucesso o cadastro de produtos, reduzindo significativamente o tempo necessário e eliminando o risco de erros manuais.
Impacto:
- Redução de 80% no tempo de cadastro.
- Aumento na precisão dos dados inseridos.

## Próximos Passos/Melhorias
- Implementação de reconhecimento de elementos HTML para automação baseada em seletores (evitando dependência de coordenadas fixas).
- Suporte a múltiplos navegadores sem reconfiguração.
- Adição de uma interface gráfica para configuração inicial do script e carregamento de arquivos CSV.
- Notificações por e-mail após a conclusão da automação.

<hr> 

### Currículos e Documentos
Acesse os arquivos disponíveis na pasta 
[![Documentos](https://img.shields.io/badge/DOCUMENTOS-%F0%9F%93%83-blue?style=flat-square)](https://github.com/vitoriapguimaraes/vitoriapguimaraes/tree/main/DOCUMENTOS) para mais informações sobre minhas qualificações e certificações.
