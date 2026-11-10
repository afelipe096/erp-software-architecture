# ERP Software Architecture

## Descripción

Este repositorio contiene el desarrollo del taller de Arquitectura de Software de la Universidad Manuela Beltrán.

El objetivo del proyecto es diseñar la arquitectura de un sistema ERP utilizando metodologías ágiles, diagramas UML, el modelo C4 y la plantilla de documentación arc42.

---

## Módulos del ERP

- Módulo de Compras
- Módulo de Facturación
- Módulo Stock/Costos
- Módulo Activos Fijos
- Módulo Empleados
- Módulo EIS

---

## Herramientas utilizadas

- Jira
- GitHub
- PlantUML
- arc42
- Visual Studio Code

---

## Arquitectura propuesta

El sistema utiliza una arquitectura web monolítica compuesta por:

- Frontend: React
- Backend: Spring Boot
- Base de Datos: PostgreSQL

---

## Estructura del proyecto

```
docs/
│
├── images/
│   ├── c1_context.png
│   ├── c2_containers.png
│   ├── mer.png
│   └── sequence_producto.png
│
├── plantuml/
│   ├── C1.plantuml
│   ├── C2.plantuml
│   ├── MER.plantuml
│   ├── codigo.plantuml
│   └── diseñoUML.plantuml
│
└── arc42-template.md
```

---

## Diagramas incluidos

- Diagrama de Contexto (C1)
- Diagrama de Contenedores (C2)
- Diagrama de Secuencia
- Modelo Entidad Relación (MER)

---

## Documentación

La documentación de arquitectura fue realizada utilizando la plantilla **arc42**.

Archivo principal:

```
docs/arc42-template.md
```

---

## Product Backlog

El Product Backlog fue elaborado en Jira e incluye:

- Épicas
- Historias de Usuario
- Criterios de aceptación
- Priorización MoSCoW

---

## Autor

Andrés Felipe Currea Piratova

Ingeniería de Software

Universidad Manuela Beltrán

2026

---

## Taller Gen 4 – Sistema Integral de Nómina Colombiana

Esta sección reúne los entregables de la actividad de Calidad Continua, DevSecOps y Arquitectura Cloud. Se mantiene separada de la documentación del ERP descrita anteriormente.

### Diagramas C4

- [C4 Nivel 1 – Contexto](docs/generacion-4-nomina/plantuml/C1-contexto.puml)
- [C4 Nivel 2 – Contenedores](docs/generacion-4-nomina/plantuml/C2-contenedores.puml)

### Evidencias exportadas

- C4 Nivel 1 – PNG: pendiente de exportar desde PlantUML.
- C4 Nivel 2 – PNG: pendiente de exportar desde PlantUML.

### Otros entregables

- ADR-001 – Justificación de microservicios frente a monolito: pendiente.
- Evidencia del pipeline DevSecOps y escaneos: pendiente.
