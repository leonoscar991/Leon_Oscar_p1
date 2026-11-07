# Sistema de Control de Inventario – TPI Programación 1

**Estudiante:** Oscar Hernán Leon Oyarzo
**Comisión:** 9 – Tecnicatura Universitaria en Programación a Distancia (UTN)
**Tutor:** Neyén Bianchi · **Coordinador:** Alberto Cortez

Sistema de consola en Python para controlar el inventario de una ferretería: carga de herramientas, listado, consulta de stock, reporte de agotados, alta de productos y registro de ventas e ingresos.

## Video demostrativo
https://youtu.be/z7PRfIcoQmY

## Documentación
El informe en PDF está en la raíz del proyecto: [Leon_Oscar_P1_Informe.pdf](Leon_Oscar_P1_Informe.pdf)

## Cómo ejecutarlo
Requiere Python 3.13 (sin librerías externas). Desde la carpeta raíz del proyecto:

```
python main.py
```

## Estructura
```
Leon_Oscar_P1/
├── main.py                    → menú y función principal (archivo de inicio)
├── Leon_Oscar_P1_Informe.pdf  → documentación
├── README.md
└── paquete_funciones/
    ├── __init__.py            → marca la carpeta como paquete
    ├── auxiliares.py          → validar_nombre(), buscar_herramienta()
    └── opciones.py            → funciones de las opciones 1 a 6
```
