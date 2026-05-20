# PLAN DE ASEGURAMIENTO DE LA CALIDAD
## Informe Consolidado Final
### Proyecto: ERP Web - Seguridad LTDA
### Repositorio: 04-repositorio-evs2-rrf
### Fecha: 20/05/2026

---

## TABLA DE CONTENIDOS

1. Resumen Ejecutivo
2. Estructura del Repositorio
3. Documentacion de Calidad
4. Planificacion de Sprints
5. Evidencia de CI/CD
6. Mapeo Jira-GitHub
7. Metricas de Calidad
8. Riesgos y Mitigacion
9. Conclusiones

---

## 1. RESUMEN EJECUTIVO

El presente informe consolida el Plan de Aseguramiento de la Calidad para el proyecto ERP Web de la empresa Seguridad LTDA. Se han implementado las siguientes actividades:

- **Repositorio GitHub**: 04-repositorio-evs2-rrf en Visual Studio Code Codespaces
- **Metodologia**: Scrum con 2 Sprints
- **Estructura de codigo**: Src modular con 6 modulos principales
- **Pruebas unitarias**: Tests skeleton para todos los modulos criticos
- **CI Pipeline**: GitHub Actions con pytest automatico
- **Documentacion**: 5 archivos de documentacion completa

---

## 2. ESTRUCTURA DEL REPOSITORIO

| Directorio/Archivo | Contenido | Responsabilidad |
|---|---|---|
| docs/plan-calidad.md | Plan completo de calidad ISO/IEC 25010 | Lider QA |
| docs/backlog.md | Product Backlog con Historias de Usuario | Product Owner |
| docs/epicas.md | Epicas del proyecto | Product Owner |
| docs/sprints.md | Planificacion de 2 Sprints | Scrum Master |
| docs/metrics.md | Metricas y KPIs del proyecto | Lider QA |
| README.md | Documentacion general del proyecto | Equipo |
| src/auth/ | Modulo de autenticacion | Desarrollo |
| src/rrhh/ | Modulo de RRHH | Desarrollo |
| src/inventario/ | Modulo de inventario | Desarrollo |
| src/ventas/ | Modulo de ventas | Desarrollo |
| src/portal_empleado/ | Portal del empleado | Desarrollo |
| src/portal_cliente/ | Portal del cliente | Desarrollo |
| src/common/ | Utilidades comunes | Desarrollo |
| tests/ | Pruebas unitarias | QA |
| .github/workflows/ci.yml | Pipeline de CI | DevOps |
| .gitignore | Configuracion git | DevOps |

---

## 3. DOCUMENTACION DE CALIDAD

### 3.1 Atributos de Calidad ISO/IEC 25010

| Atributo | Meta | Estado |
|---|---|---|
| Usabilidad | Interfaz intuitiva, aprendizaje <30 min | En implementacion |
| Seguridad | Autenticacion con roles, encriptacion | En implementacion |
| Confiabilidad | Disponibilidad >99% | En implementacion |
| Eficiencia | Tiempo respuesta <3 segundos | En implementacion |
| Mantenibilidad | Modulos independientes, codigo documentado | En implementacion |

### 3.2 Roles y Responsabilidades

| Rol | Responsabilidades |
|---|---|
| Product Owner | Define backlog y prioriza |
| Scrum Master | Facilita ceremonies y elimina impedimentos |
| Lider QA | Define metricas y planifica pruebas |
| Desarrolladores | Revision de codigo, unit tests |
| Analista de Pruebas | Pruebas funcionales y reportes |

---

## 4. PLANIFICACION DE SPRINTS

### Sprint 1: Fundamentos
- **Duracion**: 2 semanas
- **Objetivo**: Configurar repositorio, estructura y CI/CD
- **Epicas**: Configuracion inicial, Estructura del proyecto
- **Entregables**: Repositorio, Estructura src/, CI Pipeline

### Sprint 2: Desarrollo e Integracion
- **Duracion**: 2 semanas
- **Objetivo**: Implementar modulos principales
- **Epicas**: Autenticacion, RRHH, Inventario, Ventas
- **Entregables**: Modulos funcionales, Pruebas unitarias

---

## 5. EVIDENCIA DE CI/CD

### Pipeline GitHub Actions

| Paso | Descripcion | Herramienta |
|---|---|---|
| Checkout | Obtiene codigo fuente | actions/checkout@v4 |
| Setup Python | Configura Python 3.11 | actions/setup-python@v5 |
| Run Tests | Ejecuta pytest | pytest -v --tb=short |

**Trigger**: Push a main, Pull Requests a main

---

## 6. MAPEO JIRA-GITHUB

### 6.1 Historias de Usuario y Branches

| Historia | Epic | Branch | Estado |
|---|---|---|---|
| HU-001: Registro de empleado | Autenticacion | feature/auth | Creado |
| HU-002: Listar empleados | RRHH | feature/rrhh | Creado |
| HU-003: Gestionar inventario | Inventario | feature/inventario | Creado |
| HU-004: Registrar venta | Ventas | feature/ventas | Creado |
| HU-005: Portal empleado | Portal | feature/portal_empleado | Creado |
| HU-006: Portal cliente | Portal | feature/portal_cliente | Creado |

### 6.2 Estructura de Commits

| Tipo | Prefijo | Ejemplo |
|---|---|---|
| Feature | feat: | feat: estructura inicial |
| Fix | fix: | fix: corregir autenticacion |
| Docs | docs: | docs: actualizar READ.md |
| Test | test: | test: agregar tests auth |
| Refactor | refactor: | refactor: mejorar modulos |

---

## 7. METRICAS DE CALIDAD

| Metrica | Objetivo | Valor Actual |
|---|---|---|
| Coverage de tests | >80% | Skeleton configurado |
| Velocidad equipo | >20 pts/sprint | Sprint 1 en progreso |
| Bugs criticos | =0 en produccion | Repositorio inicial |
| Tiempo build CI | <5 min | Pipeline configurado |
| Code review | 100% de PRs | Branching strategy activa |

---

## 8. RIESGOS Y MITIGACION

| Riesgo | Probabilidad | Impacto | Mitigacion |
|---|---|---|---|
| Falta de experiencia Scrum | Media | Alto | Capacitacion del equipo |
| Cambios en requerimientos | Alta | Medio | Sprint reviews frecuentes |
| Problemas tecnicos CI/CD | Baja | Medio | Documentacion y testing |
| Integracion de modulos | Media | Alto | Interfaces bien definidas |

---

## 9. CONCLUSIONES

El Plan de Aseguramiento de la Calidad ha sido implementado satisfactoriamente con:

1. **Repositorio completo** con estructura modular y CI/CD
2. **Documentacion exhaustiva** de calidad, backlog y metricas
3. **Branching strategy** definida por modulo
4. **Git Flow** con feature branches para cada historia
5. **Pipeline CI** automatico con pytest
6. **Mapeo Jira-GitHub** para trazabilidad completa

El proyecto esta listo para la siguiente fase de desarrollo iterativo bajo la metodologia Scrum.

