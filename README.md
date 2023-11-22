# GitHub Data Extractor

O GitHub Data Extractor é uma ferramenta para extrair dados de repositórios do GitHub, incluindo informações sobre problemas, comentários, eventos, commits, código-fonte e muito mais. Esses dados podem ser úteis para análise, pesquisa ou qualquer outra finalidade que exija informações detalhadas sobre um repositório do GitHub.

Este projeto é uma adaptação do [GDDownloader](https://github.com/thdiaman/GDDownloader). Agradecemos ao autor original por disponibilizar o código-fonte.

## Pré-requisitos

Certifique-se de ter instalado os seguintes requisitos antes de usar a ferramenta:

- Python 3.x
- Flask
- Outras dependências necessárias (consulte o arquivo requirements.txt)

## Configuração

Antes de usar a ferramenta, é necessário configurar algumas variáveis no arquivo `properties.py`. Certifique-se de fornecer as informações corretas, como token de acesso do GitHub, caminho do executável Git, etc.

## Uso

Para extrair dados de um repositório, você pode usar a interface da web fornecida. Execute o aplicativo Flask usando o seguinte comando:

```bash
python app.py
