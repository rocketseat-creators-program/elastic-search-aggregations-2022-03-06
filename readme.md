<img src="https://storage.googleapis.com/golden-wind/experts-club/capa-github.svg" />

# Agregação no Elasticsearch

Nessa aula o objetivo será mostrada como é o funcionamento do ElasticSearch e todos os outros produtos do ElasticStack. O ElasticSearch é muito mais que um mecanismo de busca inteligente.  É o mais importante quando usar e como devemos escala o ElasticSearch no seu projeto. 

**Cenário**: Vamos imaginar que precise de uma busca de texto, que nela me retorne as categorias dessa palavra ou frase. Por exemplo: Notebook
Eu quero que retorne as todas as marcas, tamanho de tela e tecnologia

**Requisitos**:
Precisa instalar o Docker

docker pull docker.elastic.co/elasticsearch/elasticsearch:7.17.1
docker run -p 127.0.0.1:9200:9200 -p 127.0.0.1:9300:9300 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:7.17.1


## Expert

| [<img src="https://avatars.githubusercontent.com/u/57687300?s=400&u=79494f446d1fa4c328e4a7902ec790e9179a4889&v=4" width="75px;"/>](https://github.com/samantadearaujo") |
| :-: |
|[Sam](https://github.com/samantadearaujo)|
