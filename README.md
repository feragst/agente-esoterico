# agente-mistico

ideia:
agente-mistico/
│
├── main.py
├── chat.py
│
├── config/
│   ├── settings.yaml
│   └── pesos_simbolicos.yaml
│
├── data/
│   ├── futebol/
│   │   ├── jogos.csv
│   │   ├── temporadas/
│   │   └── ligas/
│   │
│   ├── pessoas/
│   │   ├── jogadores.csv
│   │   └── treinadores.csv
│   │
│   ├── astrologia/
│   │   └── efemerides/
│   │
│   └── sonhos/
│       └── sonhos_raw.txt
│
├── scripts/
│   ├── ingest/
│   │   ├── ingest_futebol.py
│   │   ├── ingest_pessoas.py
│   │   ├── ingest_misticismo.py
│   │   └── ingest_sonhos.py
│   │
│   ├── analise/
│   │   ├── padroes_futebol.py
│   │   ├── ciclos_tempo.py
│   │   ├── numerologia.py
│   │   ├── astrologia.py
│   │   └── sonhos.py
│   │
│   └── utils/
│       ├── datas.py
│       ├── texto.py
│       └── normalizacao.py
│
├── rag/
│   ├── futebol_padroes.txt
│   ├── sinais_numerologicos.txt
│   ├── misticismo/
│   │   ├── numerologia.txt
│   │   ├── astrologia.txt
│   │   ├── religioes/
│   │   │   ├── biblia.txt
│   │   │   ├── alcorao.txt
│   │   │   └── vedas.txt
│   │   └── simbolismo_sonhos.txt
│   │
│   └── biografias/
│       ├── jogadores.txt
│       └── treinadores.txt
│
├── db/
│   ├── chroma/
│   │   ├── futebol_padroes/
│   │   ├── misticismo/
│   │   ├── biografias/
│   │   └── sonhos/
│   │
│   └── sonhos.db
│
├── logs/
│   ├── consultas.log
│   └── sinais_gerados.log
│

