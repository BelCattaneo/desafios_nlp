# Desafíos de Procesamiento de Lenguaje Natural

Repositorio con los desafíos de la materia Procesamiento de Lenguaje Natural - CEIA FIUBA.

## Contenido

- **Desafio_1:** Vectorización de texto (TF-IDF, CountVectorizer) y clasificación con Naive Bayes usando el dataset 20 Newsgroups.
- **Desafio_2:** Creación de embeddings con Word2Vec (Skip-gram) usando Gensim sobre letras de canciones.

## Requisitos

- Python 3.10 o superior
- [uv](https://github.com/astral-sh/uv) (gestor de paquetes)

## Instalación

1. Clonar el repositorio:
```bash
git clone <url-del-repo>
cd desafios_nlp
```

2. Instalar uv (si no lo tenés):
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

3. Crear el entorno e instalar dependencias:
```bash
uv sync
```

## Uso

Correr Jupyter Notebook:
```bash
uv run jupyter notebook
```

O Jupyter Lab:
```bash
uv run jupyter lab
```

Luego abrir el notebook deseado desde el navegador.
