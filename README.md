# introduction-to-georeferencing
Este projeto tem como objetivo **aprender e aplicar técnicas de geoprocessamento usando Python**, criando mapas interativos e realizando análises espaciais básicas.

O foco principal é a cidade de **São José dos Campos (SP)**, trabalhando com pontos de interesse como:

| Categoria       | Descrição                                           |
|-----------------|---------------------------------------------------|
| Shoppings       | Centros comerciais e shopping centers            |
| Órgãos Públicos | Prefeituras, secretarias e órgãos administrativos|
| Delegacias      | Estações de polícia                               |
| Hospitais       | Hospitais e unidades de saúde                     |
| Igreja Católica | Igrejas católicas                                 |

O projeto é estruturado para **manter os dados brutos intactos** e gerar **dados processados prontos para análise**, além de produzir **mapas interativos em HTML**.

---

## Estrutura do projeto

```text
geoprocessamento/
├── data/
│   ├── raw/                 # Dados originais (CSV, shapefiles, GeoJSON)
│   └── processed/           # Dados limpos e prontos para análise
├── outputs/                 # Mapas e resultados exportados
├── mapa_sjc.py              # Script principal para gerar o mapa
├── exploracao.ipynb         # Notebook de testes (opcional)
└── README.md                # Descrição do projeto
``` 

Funcionalidades
Funcionalidade	Descrição
Leitura de dados georreferenciados	Carregamento de CSV, shapefiles e GeoJSON
Limpeza e processamento de dados	Correção de coordenadas e padronização de categorias
Visualização no mapa	Criação de marcadores coloridos e ícones diferentes por categoria
Mapas interativos	Exportação de mapas HTML com pontos de interesse interativos
Preparação para análises espaciais futuras	Possibilidade de criar buffers, interseções e análises avançadas
Tecnologias e Bibliotecas
Tecnologia/Biblioteca	Função
Python 3.12	Linguagem de programação principal
pandas	Manipulação de dados tabulares
geopandas	Manipulação de dados geoespaciais
shapely	Operações geométricas com polígonos
folium	Criação de mapas interativos
pyproj	Transformação de coordenadas geográficas
Próximos passos (planejados)
Etapa	Descrição
Adição de mais pontos de interesse	Novos tipos de dados, como escolas, parques, transportes
Buffers e áreas de influência	Criar áreas em torno de pontos e linhas para análises espaciais
Mapas com camadas ligáveis	Permitir ligar/desligar categorias no mapa interativo
Integração com APIs externas	OpenStreetMap, Google Maps para atualização dinâmica de dados
Integração com banco geográfico	Uso de PostGIS para análises avançadas e armazenamento de dados
