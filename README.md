# prj001

## Uso

```bash
cd /prj001/src
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
pip install pyarrow openpyxl  # opcional: parquet y xlsx
python scripts/build_notebooks.py   # opcional: regenerar notebooks
jupyter lab
```

En Bash, el entorno virtual debe activarse con `source` (o con un punto):

## Hecho por Rene Zapata

Se uso un dataset publico de un estudio sobre los apartamentos por barrios en medellin para lquiler valor poscion y otras caracteristicas, que se encuentra en https://huggingface.co/datasets/aptologia/microestudios-barrios-medellin-2026
