# Web Scraping dos Filmes Mais Bem Avaliados

Este é um projeto Python que extrai informações dos 25 filmes mais bem avaliados lançados na década de 2000 a partir de uma página da web e as armazena em um DataFrame do Pandas, além de salvar em um arquivo CSV e um banco de dados SQLite.

## Estrutura do Repositório

O repositório contém os seguintes arquivos e diretórios:

- `.gitattributes`: Arquivo de configuração do Git.
- `.idea`: Diretório de configuração do ambiente de desenvolvimento.
- `Movies.db`: Banco de dados SQLite onde os dados são armazenados.
- `README.md`: Este arquivo de documentação.
- `main.py`: Código Python que implementa a extração e armazenamento dos dados.
- `top_25_films.csv`: Arquivo CSV contendo os dados extraídos.

## Pré-requisitos e Instalação

Certifique-se de que você tenha as seguintes bibliotecas Python instaladas:

- `requests`: Para fazer solicitações HTTP para a página da web.
- `sqlite3`: Para trabalhar com o banco de dados SQLite.
- `pandas`: Para manipulação de dados tabulares.
- `beautifulsoup4`: Para fazer a análise HTML da página da web.

Você pode instalar essas bibliotecas usando o pip:

`pip install requests sqlite3 pandas beautifulsoup4`

## Execução do Projeto

Para executar o projeto, siga os passos abaixo:

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter todas as dependências necessárias instaladas.
3. Execute o arquivo `main.py`.

Isso iniciará o processo de extração de dados da página da web, criação de um DataFrame, salvamento em um arquivo CSV e armazenamento em um banco de dados SQLite.
