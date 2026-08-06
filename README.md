# python-uba-xxii

Material del curso **"Introducción a la Programación con Python"**, dictado en el marco del **Programa UBA XXII** (Facultad de Ciencias Exactas y Naturales, UBA), orientado a estudiantes en contexto de encierro.

## Sobre el curso

El programa está pensado para acompañar a los y las estudiantes desde los primeros conceptos de programación hasta un proyecto final que integra todo lo aprendido. Los ejercicios buscan conectar con su realidad cotidiana y con temas de interés general (vida en la unidad, meteorología, el Mundial 2026), siempre con cuidado y respeto por el contexto particular del grupo.

Por eso, **este repositorio no publica datos personales ni información sensible de los estudiantes**: los notebooks incluyen la consigna y la estructura de cada ejercicio, no los datos reales utilizados en clase.

## Estructura

```
python-uba-xxii/
├── notebooks/
│ ├── nivel-1/ → las 16 notebooks del curso introductorio (una por clase)
│ └── nivel-2/ → notebooks del curso avanzado (a completar)
├── soluciones/ → resoluciones de los ejercicios
└── material-adicional/ → guías de referencia rápida, apuntes y la plantilla de asistencia
```

Cada notebook de `notebooks/` sigue la misma estructura:
1. Encabezado con clase, fecha, objetivo y contenidos.
2. Un bloque de código con `input()` para el "código de alumno" (parte del sistema de asistencia del curso).
3. Desarrollo de la clase.
4. Espacio para el resumen de la clase.

## Progresión del curso

El curso avanza de forma gradual: variables → condicionales → bucles → listas y diccionarios → funciones → buenas prácticas → proyecto final. El detalle completo de las 16 clases está en el programa del curso (ver `material-adicional/`).

## Tecnologías

- Python 3
- Jupyter Notebook

## Cómo usarlo

```bash
pip install notebook
jupyter notebook notebooks/
```

## Licencia

MIT — libre para reutilizar y adaptar, citando la fuente.
