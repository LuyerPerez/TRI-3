# Mi API FastAPI - Semana 2

## ¿Qué hace?

API mejorada con validación automática de datos y type hints.

## Nuevos Features (Semana 2)

- ✅ Type hints en todas las funciones
- ✅ Validación automática con Pydantic
- ✅ Endpoint POST para crear datos
- ✅ Parámetros de ruta (ejemplo: /products/{id})
- ✅ Búsqueda con parámetros query

## ¿Cómo ejecutar?

```bash
pip install fastapi pydantic uvicorn
uvicorn main:app --reload
```

**1. Frases de lo mas relevante**

- La librería Pydantic permitió definir modelos de datos claros y con validación automática.
- El uso de type hints ayuda a la claridad del código y a la autocompletación en los IDEs.
- La búsqueda permite filtrar productos por nombre y precio máximo, demostrando cómo usar parámetros opcionales en FastAPI.


**2. Subir a GitHub** (10 min):

```bash
# En tu terminal, en la carpeta de tu proyecto
git add .
git commit -m "Semana 2: API con Pydantic y Type Hints"
git push

tu-repositorio/
├── main.py                    # API con Type Hints + Pydantic
├── requirements.txt           # fastapi, pydantic, uvicorn
└── README.md                  # Documentación actualizada