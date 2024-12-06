## HashZap: Chat em Tempo Real com Flask e Flet
O HashZap é um projeto de chat ao vivo que permite a comunicação em tempo real entre usuários conectados a uma mesma rede. Ele oferece duas versões distintas: uma implementada com Flask e SocketIO, focada em aplicações web, e outra com Flet, que simula um ambiente de mensagens em uma interface leve e simplificada.

O objetivo principal é proporcionar uma plataforma acessível para estudar comunicação em tempo real e explorar diferentes abordagens para construção de interfaces e funcionalidades de chats.

## Demonstração/Visualização
Versão Flask: Uma interface web com envio e recebimento de mensagens em tempo real.
![Demonstração do chat](https://github.com/vitoriapguimaraes/portifolio-python-development/blob/main/5.%20Site%20Chat%20ao%20Vivo/Chat-Demonstracao-WebFlask.gif)

Versão Flet: Interface simplificada onde mensagens e eventos são exibidos diretamente no aplicativo.
![Demonstração do chat](https://github.com/vitoriapguimaraes/portifolio-python-development/blob/main/5.%20Site%20Chat%20ao%20Vivo/Chat-Demonstracao-Flet.gif)

## Principais Tecnologias Utilizadas
- Python: Linguagem base para o projeto.
- Flask: Framework para criação do servidor web.
- Flask-SocketIO: Biblioteca para comunicação em tempo real usando websockets.
- Flet: Framework para criação de interfaces leves baseadas em Python.
- HTML e JavaScript: Para a interface web da versão Flask.

## Estrutura do Projeto
```
├── templates/
│   └── index.html         # Interface web da versão Flask
├── chatWebFlask.py        # Arquivo principal da versão Flask (servidor do chat)
├── chatFlet.py            # Arquivo principal da versão Flet
└── requirements.txt       # Dependências do projeto
```

## Como Executar
### Pré-requisitos
- Python 3.8 ou superior instalado.
- Todas as dependências listadas no requirements.txt.

### Etapas:
1. Instalação. Clone o repositório:
    ```
    git clone https://github.com/seu_usuario/hashzap.git ### arrumar aqui!
    cd hashzap
    ```

2. Instale as dependências:
    ```
    pip install -r requirements.txt
    ```

### Executando a Versão Flask
1. Inicie o servidor Flask:
    ```
    python chatWebFlask.py
    ```

2. Acesse o chat no navegador em: http://localhost:5000.

### Executando a Versão Flet
1. Inicie o aplicativo Flet:
    ```
    python chatFlet.py
    ```

2. O chat será carregado automaticamente em uma janela local ou no navegador.

## Funcionalidades
### Versão Flask:
- Envio e recebimento de mensagens em tempo real usando websockets.
- Interface acessível via navegador.
### Versão Flet:
- Interface local e simplificada.
- Registro de eventos como entrada de novos usuários na sala do chat.

## Resultados e Conclusões
O projeto demonstra como implementar funcionalidades de comunicação em tempo real utilizando diferentes tecnologias. A versão Flask é ideal para explorar conceitos de comunicação web, enquanto a versão Flet apresenta uma solução minimalista para interfaces locais.

## Próximos Passos/Melhorias
- Autenticação de usuários: Implementar nomes de usuários únicos e senhas para maior controle.
- Suporte a múltiplas salas: Criar diferentes ambientes de chat para diversos grupos de usuários.
- Integração com notificações: Exibir alertas quando uma nova mensagem for recebida.

<br>
<hr> 

### Currículos e Documentos
Acesse os arquivos disponíveis na pasta 
[![Documentos](https://img.shields.io/badge/DOCUMENTOS-%F0%9F%93%83-blue?style=flat-square)](https://github.com/vitoriapguimaraes/vitoriapguimaraes/tree/main/DOCUMENTOS) para mais informações sobre minhas qualificações e certificações.
