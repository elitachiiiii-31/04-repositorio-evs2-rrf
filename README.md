# ERP Web - Seguridad LTDA

## Plan de Aseguramiento de la Calidad - Proyecto de Ingenieria de Software

**Repositorio:** 04-repositorio-evs2-rrf  
**Entorno:** Visual Studio Code Codespaces  
**Enfoque:** Scrum - 2 Sprints

---

## 1. Introduccion

El presente proyecto corresponde al desarrollo de un sistema ERP web para la empresa "Seguridad LTDA", orientado a la gestion de Recursos Humanos e Inventario/Ventas a nivel nacional. El sistema debe contar con Front-Office y Back-Office, interfaz intuitiva, interoperabilidad, disponibilidad en navegadores y dispositivos moviles, y estandares de seguridad.

---

## 2. Objetivos del Proyecto

### 2.1 Objetivo General
Desarrollar un sistema ERP web modular y configurable que permita a Seguridad LTDA gestionar de manera eficiente sus areas de Recursos Humanos e Inventario/Ventas.

### 2.2 Objetivos Especificos
- Centralizar la informacion de empleados, contratos y asistencia.
- Controlar inventario en multiples bodegas con stock en tiempo real.
- Gestionar ventas, clientes y listas de precios.
- Disponibilizar portales de autoservicio para empleados y clientes.
- Cumplir con estandares de calidad mediante modelos ISO 25010 e IEEE 730.

---

## 3. Roles y Responsabilidades

| Rol | Responsabilidades |
|-----|--------------------|
| Product Owner | Priorizar backlog, validar requerimientos |
| Scrum Master | Coordinar sprints, remover impedimentos |
| Lider QA | Definir criterios de calidad |
| Desarrolladores | Implementar, commits, PRs |
| Analista de Pruebas | Diseñar y ejecutar pruebas |

---

## 4. Atributos de Calidad (ISO/IEC 25010)

| Atributo | Descripcion | Aplicacion |
|----------|-------------|------------|
| Usabilidad | Interfaz facil de usar | Portal empleado y cliente |
| Seguridad | Proteccion de datos | Autenticacion y roles |
| Confiabilidad | Operacion continua | Disponibilidad 24/7 |
| Eficiencia | Respuesta oportuna | Carga menor a 3s |
| Mantenibilidad | Modularidad | Modulos independientes |
| Compatibilidad | Multiplataforma | Navegador y movil |

---

## 5. Epicas del Proyecto

| # | Epica | Modulo |
|---|-------|--------|
| E1 | Gestion de Personal | RR.HH. |
| E2 | Remuneraciones y Asistencia | RR.HH. |
| E3 | Portal del Empleado | Front-Office |
| E4 | Inventario y Bodega | Inventario |
| E5 | Ventas y Clientes | Ventas |
| E6 | Portal del Cliente | Front-Office |
| E7 | Seguridad y Compatibilidad | Infraestructura |
| E8 | Reportes | Analitica |

---

## 6. Planificacion Scrum - Sprint 1

**Modulo:** RR.HH. y Base del Proyecto  
**Duracion:** 2 semanas

| Historia | Epica | Estado |
|----------|-------|--------|
| Registrar ficha de empleados | Gestion de Personal | Por hacer |
| Registrar contratos y finiquitos | Gestion de Personal | Por hacer |
| Registrar licencias medicas | Gestion de Personal | Por hacer |
| Controlar asistencia y atrasos | Remuneraciones y Asistencia | Por hacer |
| Gestionar vacaciones | Remuneraciones y Asistencia | Por hacer |
| Generar liquidaciones | Remuneraciones y Asistencia | Por hacer |
| Portal del Empleado | Portal del Empleado | Por hacer |
| Autenticacion de usuarios | Seguridad y Compatibilidad | Por hacer |

---

## 7. Planificacion Scrum - Sprint 2

**Modulo:** Inventario/Ventas y Cierre  
**Duracion:** 2 semanas

| Historia | Epica | Estado |
|----------|-------|--------|
| Registrar productos e inventario | Inventario y Bodega | Por hacer |
| Control de entradas y salidas | Inventario y Bodega | Por hacer |
| Gestionar multiples bodegas | Inventario y Bodega | Por hacer |
| Gestionar reservas de stock | Inventario y Bodega | Por hacer |
| Gestionar listas de precios | Ventas y Clientes | Por hacer |
| Ficha de clientes y ventas | Ventas y Clientes | Por hacer |
| Portal del Cliente | Portal del Cliente | Por hacer |
| Reportes y dashboard | Reportes | Por hacer |

---

## 8. Metricas de Calidad

| Metrica | Meta |
|---------|------|
| Historias completadas por sprint | 100% |
| Tareas cerradas | >= 90% |
| Pull requests aprobados | 100% |
| Criterios de aceptacion | 100% |
| Revision de codigo | Obligatoria |

---

## 9. Flujo de Trabajo Git

1. Crear rama: feature/<tipo>-<descripcion>
2. Desarrollar y commit
3. Crear Pull Request
4. Aprobar y merge a main
5. Cerrar historia en Jira

---

## 10. Control de Cambios

| Paso | Accion |
|------|--------|
| 1 | Solicitud en Jira |
| 2 | Evaluacion de impacto |
| 3 | Aprobacion PO |
| 4 | Implementacion en rama |
| 5 | Revision PR |
| 6 | Validacion y cierre |

---

## 11. Normas y Estandares

| Norma | Aplicacion |
|-------|------------|
| ISO/IEC 25010 | Atributos de calidad |
| IEEE 730 | Plan de aseguramiento |
| CMMI | Madurez del proceso |
| Scrum Guide | Marco agil |

---

## 12. Estructura del Repositorio

```
04-repositorio-evs2-rrf/
├── README.md
├── docs/
│   ├── plan-calidad.md
│   ├── backlog.md
│   ├── epicas.md
│   ├── sprints.md
│   └── metrics.md
├── src/
│   ├── front-office/
│   ├── back-office/
│   ├── rrhh/
│   └── inventario/
└── tests/
```

---

## 13. Conclusion

El presente repositorio contiene toda la documentacion, planificacion y estructura tecnica del proyecto ERP Web para Seguridad LTDA.
