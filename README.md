# Control-Gastos

Aplicación Web para la Gestión de Facturas y Propinas.

**Autor:** Anddy Ortega
**Matrícula:** 2024-0243
**Materia:** Programación
**Código:** 2024-0243

## Descripción

Aplicación web que permite registrar, controlar y visualizar gastos (facturas y propinas) con alertas automáticas según el porcentaje del presupuesto mensual utilizado, sustituyendo el registro manual en papel.

## Problemática

El registro manual de facturas y propinas dificulta el control del presupuesto, provoca errores de cálculo y no genera alertas cuando el presupuesto se agota.

## Objetivo General

Desarrollar una aplicación web que registre, controle y visualice los gastos con alertas automáticas por porcentaje del presupuesto.

## Estados del presupuesto

| Porcentaje | Estado | Color |
|------------|--------|-------|
| < 80% | Disponible | Verde |
| 80% – 100% | Próximo a agotarse | Amarillo |
| > 100% | Excedido | Rojo |

## Estructura del repositorio

control-gastos/
├── README.md
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── app.js
├── assets/
│   └── img/
└── docs/
    └── prototipo.pdf

## Pantallas del sistema

1. Panel Principal
2. Agregar Factura
3. Agregar Propina
4. Historial
5. Resumen Mensual
6. Alerta 80-100%
7. Alerta >100%

## Video demostrativo

https://youtu.be/TcEMLDbsvSU
