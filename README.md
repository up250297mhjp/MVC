# [MVC]

## Descripción

Está desarrollado en Python con el patrón **MVC (Modelo-Vista-Controlador)**, que separa los datos, la interfaz y la lógica del programa en capas independientes.

## Tecnologías

- Python 3
- MySQL (`mysql-connector-python`)
- pandas
- python-dotenv

## Estructura de carpetas

```
.
├── src/
│   ├── models/         # Clases que representan los datos
│   ├── views/          # Lo que ve el usuario (menús y mensajes)
│   ├── controllers/    # Lógica que conecta modelos y vistas
│   └── repositories/   # Acceso a la base de datos
├── sql/                # Scripts de tablas y datos de ejemplo
├── docs/               # Diagramas y documentación
├── .env-example        # Plantilla de variables de conexión
├── requirements.txt    # Librerías necesarias
└── README.md
```

## Integrantes

- Juan Pablo Muñoz Hernández
- Emiliano Victor Manuel Esparza Rodríguez
- Valeria Gutiérrez Miramontes
- Daniel López Ávila

## Créditos

Material de apoyo (diagramas de MVC y scripts SQL de ejemplo) tomado del repositorio del profesor: [ISC-UPA/2026-3-OOP](https://github.com/ISC-UPA/2026-3-OOP).
