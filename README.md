# Hugging Face Agents Course — Ejercicios

Repositorio personal con los ejercicios y notebooks del curso
[Hugging Face Agents Course](https://www.hf.co/learn/agents-course).

---

## Contenido

| Unidad | Notebook | Descripción |
|--------|----------|-------------|
| Unit 1 | [dummy_agent_library.ipynb](unit-1/dummy_agent_library.ipynb) | Construcción de un agente desde cero usando la Serverless API de Hugging Face |

---

## Requisitos

- Python 3.10+
- Una cuenta en [Hugging Face](https://huggingface.co) con un token de tipo **Read**  [hf.co/settings/tokens](https://hf.co/settings/tokens)

---

## Instalación

```bash
# Clonar el repositorio
git clone <url-del-repo>
cd nico-agents-course

# Crear y activar entorno virtual
python -m venv .venv
source .venv/bin/activate  # En Windows: .venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt
```

---

## Configuración

Crea un archivo `.env` en la raíz del proyecto a partir del ejemplo incluido:

```bash
cp .env.example .env
```

Edita `.env` y reemplaza el valor con tu token real:

```
HF_TOKEN=hf_xxxxxxxxxxxxxxxxxxxx
```

---

## Ejecutar los notebooks

```bash
jupyter notebook
```

Abre el notebook correspondiente desde la interfaz de Jupyter en tu navegador.
