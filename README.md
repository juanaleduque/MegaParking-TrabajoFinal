# Mega Parking Pinares — Trabajo Final de Analítica de Negocios

Universidad EAFIT · Profesor: Juan Pablo Pérez Monsalve
Integrantes: Juan Alejandro Duque · Sofía Palacio · José Quintero

## Contenido

| Archivo | Qué es |
|---|---|
| `TrabajoFinal_Parqueadero.ipynb` | Notebook ejecutado: preparación, ocupación, K-Means, árbol de decisión y bosque aleatorio |
| `datos/parqueadero_ultimo_ano.csv` | Base original, tal como la entregó el parqueadero |
| `datos/parqueadero_preparada.csv` | Base preparada (la genera la última celda del notebook) |

## Cómo correrlo en Colab

1. Abrir el notebook en Colab (Archivo → Abrir notebook → GitHub, marcando "Incluir repositorios privados").
2. Ejecutar todo. La primera celda pide subir `datos/parqueadero_ultimo_ano.csv` (descárguelo de este repositorio).

## Ficha de procedencia

| Elemento | Detalle |
|---|---|
| Nombre de la base | `parqueadero_ultimo_ano.csv` — registro histórico de tiquetes de Mega Parking Pinares |
| Quién recolectó los datos | Mega Parking Pinares, a través de su sistema de control de accesos y facturación (POS) |
| Cómo se recolectaron | Registro automático de cada tiquete al ingreso y a la salida del vehículo, con el valor liquidado en caja |
| Período | 5 de noviembre de 2025 al 5 de noviembre de 2026 |
| Acceso | Base no pública, entregada por la administración del parqueadero. Uso exclusivamente académico |
| Tamaño | 199.853 tiquetes y 20 columnas (194.337 después de la depuración) |
| Cada registro | Un tiquete: un vehículo que entró, permaneció un tiempo y salió pagando |
