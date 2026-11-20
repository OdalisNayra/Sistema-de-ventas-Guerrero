# Simulación académica de trabajo colaborativo — Avance 3

**Proyecto:** Sistema Web de Ventas – Tienda Guerrero  
**Curso:** Herramientas de Desarrollo  
**Estado:** Documento de demostración; no corresponde a una funcionalidad implementada.

## Objetivo
Representar el ciclo de colaboración mediante Git y GitHub: creación de una rama de trabajo, registro de un cambio documental mediante commit y propuesta de integración mediante pull request hacia `develop`.

## Escenario de ejemplo
Durante el desarrollo del futuro módulo de inventario, el equipo necesita documentar una regla de validación: **los movimientos de entrada y salida no deben aceptar cantidades iguales o inferiores a cero**.

Este escenario se utiliza únicamente como ejemplo de organización técnica. **No se han programado, corregido ni probado estas validaciones en el sistema.**

## Flujo de trabajo simulado
1. Tomar `develop` como rama base de trabajo.
2. Crear `feature/apf3-colaboracion`.
3. Incorporar este documento de ejemplo en `docs/avance3/`.
4. Registrar el cambio en un commit descriptivo.
5. Crear un pull request desde `feature/apf3-colaboracion` hacia `develop`.
6. Revisar la propuesta antes de una eventual integración.

## Buenas prácticas ilustradas
- Separación de ramas para evitar trabajar directamente en `main`.
- Mensajes de commit que identifiquen el propósito del cambio.
- Revisión de cambios antes de fusionarlos.
- Registro y trazabilidad de la propuesta en GitHub.

## Evidencias para el informe
- Rama `feature/apf3-colaboracion` creada desde `develop`.
- Commit documental asociado a la simulación.
- Pull request propuesto hacia `develop`, pendiente de revisión.

> Este archivo se creó exclusivamente como evidencia del Avance 3 de Herramientas de Desarrollo.
