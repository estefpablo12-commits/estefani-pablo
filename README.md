# Calculadora Simple

Un proyecto simple de Python que implementa una función de suma con pruebas unitarias.

## 📋 Descripción

Este proyecto contiene una sencilla función `sumar()` que realiza operaciones de suma entre dos números.

## 📁 Estructura del Proyecto

- `app.py` - Archivo principal con la función `sumar(a, b)`
- `test_app.py` - Pruebas unitarias para validar la función

## 🚀 Uso

### Ejecutar la aplicación

```bash
python app.py
```

### Ejecutar las pruebas

```bash
python -m unittest test_app.py
```

O simplemente:

```bash
python test_app.py
```

## 📝 Ejemplos

```python
from app import sumar

resultado = sumar(2, 3)  # Retorna 5
resultado = sumar(-1, 1)  # Retorna 0
```

## ✅ Pruebas

El proyecto incluye pruebas unitarias que validan:
- Suma de números positivos
- Suma de números con signos opuestos

## 🛠️ Requisitos

- Python 3.x

## 📄 Licencia

Sin especificar
