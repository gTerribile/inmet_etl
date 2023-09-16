# Projeto de ETL de Dados Meteorológicos do INMET

- Este repositório contém um projeto de ETL (Extração, transformação e Carga) que visa coletar dados Meteorológicos do INMET (Instituto Nacional de Meteorologia).
- O INMET fornece uma vasta quantidade de dados meteorológicos em formato bruto, e este projeto tem como objetivo facilitar a utilização desses dados em aplicações diversas, como análises climática, estudos de tendência meterológicas, etc.


## Visão Geral

Este projeto de ETL inclui as seguintes funcionalidades principais:

1. **Extração**: Coleta dos dados por download direto dos arquivos disponibilizados através do [INMET](https://portal.inmet.gov.br/).
2. **Transformação**: Limpeza e formatação dos dados brutos para torná-los prontos para análise. Isso inclui a detecção e correção de valores ausentes, conversão de datas, entre outros.
3. **Carga**: Armazenamento dos dados limpos em uma arquivo de destino para posterior análise.


## Tecnologias Utilizadas
- Python 3.x: Linguagem de programação para desenvolvimento do projeto.
- Pandas: Biblioteca para manipulação e análise de dados.
- Jupyter Notebook: Utilizado para análise interativa dos dados.

## Configuração do Ambiente

Para configurar o ambiente de desenvolvimento e execução do projeto, sigas as instruções abaixo:

1. Clone este repositório:
- git clone https://github.com/*seu-usuario*/inmet_etl.git

2. instale as dependências do projeto:
- pip3 install pandas

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar solicitações de pull (pull requests) com melhorias, correções de bugs ou novos recursos.
