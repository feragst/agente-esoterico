# agente-mistico
Projeto pessoal for fun

ideia:
Criar um agente de IA local com um vasto conhecimento de dados em misticismo/esoterismo e que faça análises místicas para BETS
```text
agente_esoterico
├── main.py                      # Ponto de entrada
├── chat.py                      # Interface de chat
│
├── config/
│   ├── settings.yaml            # Configurações gerais
│   └── pesos_simbolicos.yaml    # Pesos para cada fonte mística
│
├── data/
│   ├── futebol/
│   │   ├── jogos.csv            # Histórico real de jogos
│   │   ├── temporadas/
│   │   └── ligas/
│   │
│   ├── pessoas/
│   │   ├── jogadores.csv        # Dados reais com datas de nascimento
│   │   └── treinadores.csv
│   │
│   ├── astrologia/
│   │   └── efemerides/          # Dados astronômicos REAIS (NASA/JPL)
│   │
│   └── sonhos/
│       └── sonhos_raw.txt       # Seus sonhos
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
│   ├── futebol_padroes.txt      # Padrões extraídos de dados reais
│   ├── sinais_numerologicos.txt
│   │
│   ├── misticismo/
│   │   ├── numerologia.txt      # Textos acadêmicos sobre numerologia
│   │   ├── astrologia.txt       # Textos de astrologia tradicional
│   │   │
│   │   ├── religioes/
│   │   │   ├── biblia.txt       # Bíblia completa (domínio público)
│   │   │   ├── alcorao.txt      # Alcorão (domínio público)
│   │   │   ├── vedas.txt        # Vedas (domínio público)
│   │   │   ├── iching.txt       # I Ching
│   │   │   └── cabala.txt       # Textos cabalísticos
│   │   │
│   │   └── simbolismo_sonhos.txt # Interpretação tradicional
│   │
│   └── biografias/
│       ├── jogadores.txt
│       └── treinadores.txt
│
├── db/
│   ├── chroma/
│   │   ├── futebol_padroes/     # Embeddings de padrões reais
│   │   ├── misticismo/          # Embeddings de textos sagrados
│   │   ├── biografias/          # Embeddings de biografias
│   │   └── sonhos/              # Seus sonhos
│   │
│   └── sonhos.db                # SQLite para sonhos estruturados
│
└── logs/
    ├── consultas.log
    └── sinais_gerados.log
