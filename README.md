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
