# Exemplo de Extração e Tratamento de Dados para Envio de Relatório por E-mail
Este projeto automatiza a análise e envio de relatórios de vendas por e-mail. Ele utiliza um arquivo Excel como base de dados, processa informações sobre faturamento, quantidade de produtos vendidos e ticket médio por loja, e envia esses dados formatados em um e-mail HTML para um destinatário.

O objetivo é simplificar o compartilhamento de indicadores de desempenho, eliminando tarefas manuais e otimizando a análise de dados para decisões rápidas e eficazes.

## Demonstração/Visualização
O sistema gera um e-mail com tabelas organizadas contendo o faturamento, a quantidade de produtos vendidos e o ticket médio por loja. A formatação clara e visual facilita a análise direta no corpo do e-mail enviado.

![Impressão do e-mail](link)

## Principais Tecnologias Utilizadas
- Python: Linguagem base para todo o desenvolvimento.
- pandas: Para manipulação e análise dos dados.
- win32com.client: Para integração com o Microsoft Outlook e envio de e-mails.

## Estrutura do Projeto
```
├── relatorioVendas.py           # Script principal para processamento e envio
└── datasetExemploVendas.xlsx    # Arquivo de dados de exemplo
```

## Como Executar
### Pré-requisitos
- Python 3.8 ou superior instalado.
- Microsoft Outlook configurado no computador.
- Biblioteca pywin32 instalada:
```
pip install pywin32
```
1. Substitua o endereço de e-mail no código: Altere o valor de <code>mail.To</code> no script para o destinatário desejado.
2. Ajuste o arquivo de dados: Certifique-se de que o arquivo Excel <code>datasetExemploVendas.xlsx</code> contém as colunas ID Loja, Valor Final, e Quantidade.
3. Execute o script:
```
python relatorioVendas.py
```
4. Resultado:
O e-mail será enviado automaticamente para o endereço configurado no script.

## Funcionalidades
### Análise de Dados:
- Calcula o faturamento por loja.
- Soma a quantidade de produtos vendidos por loja.
- Determina o ticket médio de produtos vendidos em cada loja.

### Envio Automático de E-mail:
- Gera um e-mail HTML com tabelas formatadas.
- Envia o relatório diretamente para o destinatário configurado.

## Resultados e Conclusões
Este projeto demonstra como automatizar tarefas recorrentes de análise e compartilhamento de dados, reduzindo o esforço manual e minimizando erros humanos.
Exemplo de Resultado: O destinatário recebe um e-mail com um relatório claro e visualmente organizado, possibilitando a rápida identificação de métricas importantes.

## Próximos Passos/Melhorias
- Compatibilidade com outros clientes de e-mail: Expandir para serviços como Gmail ou SMTP genérico.
- Integração com bancos de dados: Permitir que os dados sejam extraídos diretamente de um banco de dados ao invés de arquivos Excel.
- Visualizações aprimoradas: Adicionar gráficos e outros elementos visuais no e-mail.

<br>
<hr> 

### Currículos e Documentos
Acesse os arquivos disponíveis na pasta 
[![Documentos](https://img.shields.io/badge/DOCUMENTOS-%F0%9F%93%83-blue?style=flat-square)](https://github.com/vitoriapguimaraes/vitoriapguimaraes/tree/main/DOCUMENTOS) para mais informações sobre minhas qualificações e certificações.