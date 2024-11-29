# Installation de gptscript
```bash
curl https://get.gptscript.ai/install.sh | sh
```

# Setup
```bash
export OPENAI_API_KEY=<cle openai>
export GPTSCRIPT_DEFAULT_MODEL=gpt-4o
```

# Execution
```bash
gptscript crypto.gpt
```

# Connection à la db
```bash
docker exec -it crypto-postgres /bin/bash
psql -U postgres -d cryptos
# liste des tables dans psql : \dt
```