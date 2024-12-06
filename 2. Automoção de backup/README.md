# Automação de backup
Este projeto consiste em um script em Python desenvolvido para realizar backups automáticos de arquivos e diretórios. Ele permite ao usuário selecionar uma pasta e copia todos os arquivos e subdiretórios para um novo local, organizando-os por data e hora. Este script é ideal para simplificar e automatizar o processo de backup local, garantindo segurança e organização dos dados.

## Demonstração/Visualização
Abaixo, é apresentada uma demonstração do funcionamento do script de automação de backup.

![Demonstração do backup](https://github.com/vitoriapguimaraes/portifolio-python-development/blob/main/2.%20Automo%C3%A7%C3%A3o%20de%20backup/AutomocaoBackup-Demonstracao.gif)

## Principais Tecnologias Utilizadas
- Python: Linguagem principal para desenvolvimento.
- tkinter: Para criar uma interface gráfica que permita a seleção do diretório.
- shutil: Para realizar cópias de arquivos e diretórios.
- datetime: Para gerar carimbos de data e hora usados na organização dos backups.

## Estrutura do Projeto
```
├── automacaoBackup.py           # Script principal para execução do backup.  
└── filesTest/                   # Pasta para teste do backup.  
```

## Como Executar
### Pré-requisitos
- Certifique-se de ter o Python instalado (versão 3.6 ou superior).
- Instale as bibliotecas necessárias.

### Etapas:
1. Faça o download do repositório: Clone ou baixe os arquivos para seu computador.
2. Execute o script: Abra o terminal, navegue até o diretório do projeto e execute:
```
python automacaoBackup.py  
```
3. Selecione o diretório: Uma janela será exibida para que você escolha a pasta a ser copiada.
4. Acompanhe o progresso: O terminal exibirá mensagens informando o progresso e a conclusão do backup.

## Funcionalidades
- Seleção de Diretórios: Escolha de forma fácil e intuitiva a pasta a ser copiada.
- Criação de Diretórios com Data/Hora: Backups organizados de forma cronológica.
- Cópia de Arquivos e Subdiretórios: Preserva toda a estrutura da pasta original.
- Automação e Simplicidade: Interface amigável para uso local.

## Resultados e Conclusões
O script foi testado com pastas de diferentes tamanhos e estruturas, demonstrando eficiência e organização ao criar backups completos. A estrutura de saída facilita a identificação de backups realizados em momentos específicos, aumentando a segurança dos dados.

## Próximos Passos/Melhorias
- Adicionar suporte para compressão dos backups (formato .zip).
- Permitir configurações adicionais, como exclusão de certos tipos de arquivo do backup.
- Agendar backups periódicos automaticamente.

<br>
<hr> 

### Currículos e Documentos
Acesse os arquivos disponíveis na pasta 
[![Documentos](https://img.shields.io/badge/DOCUMENTOS-%F0%9F%93%83-blue?style=flat-square)](https://github.com/vitoriapguimaraes/vitoriapguimaraes/tree/main/DOCUMENTOS) para mais informações sobre minhas qualificações e certificações.
