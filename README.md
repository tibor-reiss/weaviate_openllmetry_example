## Sources
https://github.com/traceloop/openllmetry
## Run a local weaviate instance
Set PERSISTENCE_DATA_PATH, e.g. ./data
```bash
docker compose up -d
```
## Some env vars
- TRACELOOP_API_KEY
- COHERE_APIKEY
- OPENAI_APIKEY
- WEAVIATE_CLUSTER_URL
## Create venv
```bash
python -m venv venv_weaviate
source venv_weaviate/bin/activate
pip intall traceloop-sdk
pip install weaviate==3.26.0 (4.6.3)
```
## Run it
```python weaviate_v3.py (weaviate_v4.py)```
