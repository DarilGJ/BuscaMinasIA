# BuscaMinasIA

**BuscaMinasIA** es un asistente en Python con interfaz gráfica (Tkinter) para jugar buscaminas: tú ves el tablero real e introduces los números que pide la aplicación; el programa deduce casillas seguras, minas y el siguiente movimiento usando restricciones lógicas.

## Estructura del repositorio

```
BuscaMinasIA/
├── BuscaMinas.py   # Aplicación: lógica del asistente + ventana Tkinter
└── README.md
```

No hay `requirements.txt`: el proyecto usa solo la **biblioteca estándar** de Python (`tkinter`, `random`, etc.).

## Requisitos

| Herramienta | Uso |
|-------------|-----|
| **Git** | Clonar y actualizar el repositorio |
| **Python 3** | Intérprete (3.10+ recomendable) |
| **Tkinter** | Interfaz gráfica (en Windows suele venir con Python; en Linux a veces hace falta el paquete del sistema, p. ej. `python3-tk` en Debian/Ubuntu) |

Comprueba la versión de Python:

```bash
python --version
```

Si `python` no existe, prueba `python3`.

## Clonar el repositorio

Con HTTPS:

```bash
git clone https://github.com/TU_USUARIO/BuscaMinasIA.git
cd BuscaMinasIA
```

Con SSH (si tienes clave configurada en GitHub):

```bash
git clone git@github.com:TU_USUARIO/BuscaMinasIA.git
cd BuscaMinasIA
```

Sustituye `TU_USUARIO` por tu nombre de usuario u organización en GitHub cuando publiques el repo.

## Ejecutar el proyecto

Desde la carpeta raíz del repositorio:

```bash
python BuscaMinas.py
```

En algunos sistemas:

```bash
python3 BuscaMinas.py
```

No hace falta crear un entorno virtual ni instalar dependencias con `pip` para ejecutar esta versión.
