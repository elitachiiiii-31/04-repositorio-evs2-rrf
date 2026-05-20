# Plan de Aseguramiento de la Calidad

## Proyecto: ERP Web Seguridad LTDA

**Version:** 1.0
**Fecha:** Mayo 2026
**Normas:** ISO/IEC 25010, IEEE 730, CMMI

---

## 1. Introduccion

Este documento establece las actividades de aseguramiento de calidad para el desarrollo del ERP web de Seguridad LTDA, sistema que gestiona Recursos Humanos e Inventario/Ventas con portales para empleados y clientes.

---

## 2. Objetivos

Definir metricas, criterios y procesos que aseguren la calidad del producto, desde analisis hasta entrega, con revision continua por sprint.

---

## 3. Alcance

El plan cubre todas las fases: analisis, diseno, implementacion, pruebas, revision y gestion de cambios.

---

## 4. Roles y Responsabilidades

| Rol | Responsabilidades |
|-----|--------------------|
| Product Owner | Valida requisitos, acepta historias |
| Scrum Master | Coordina revisiones y sprints |
| Lider QA | Define metricas y planifica pruebas |
| Desarrolladores | Revision de codigo, unit tests |
| Analista de Pruebas | Pruebas funcionales y reportes |

---

## 5. Atributos de Calidad ISO/IEC 25010

### 5.1 Usabilidad
- Interfaz facil de usar e intuitiva
- Tiempo de aprendizaje menor a 30 min

### 5.2 Seguridad
- Autenticacion con roles de acceso
- Encriptacion de datos sensibles
- Auditoria de accesos

### 5.3 Confiabilidad
- Disponibilidad mayor a 99% en horario laboral

### 5.4 Eficiencia
- Tiempo de respuesta menor a 3 segundos

### 5.5 Mantenibilidad
- Modulos independientes, codigo documentado

### 5.6 Compatibilidad
- Chrome, Firefox, Safari y Edge
- Dispositivos moviles

---

## 6. Modelos Aplicados

| Modelo | Aplicacion |
|--------|------------|
| ISO/IEC 25010 | Atributos de calidad |
| IEEE 730 | Estructura del plan |
| CMMI | Madurez del proceso |

---

## 7. Metodos de Evaluacion

| Metodo | Aplicacion |
|--------|------------|
| Revision de codigo | Pull Request obligatorio |
| Pruebas unitarias | Por modulo |
| Pruebas funcionales | Por historia |
| Sprint Review | Validacion entregable |
| Checklist | Por historia de usuario |

---

## 8. Metricas

| Metrica | Meta |
|---------|------|
| Historias completadas | 100% |
| Defectos por sprint | <= 5 |
| Coverage pruebas | >= 70% |
| PR rechazados | <= 10% |
| Cumplimiento sprint | >= 90% |

---

## 9. Estandares

| Estandar | Aplicacion |
|----------|------------|
| feature/tipo-desc | Nombres de ramas |
| Mensajes descriptivos | Commits |
| 1+ reviewer | PR obligatorio |
| README actualizado | Documentacion |

---

## 10. Control de Cambios

1. Solicitud en Jira
2. Evaluacion de impacto
3. Aprobacion PO
4. Implementacion en rama
5. PR con revision
6. Validacion y cierre

**Tipos:** Correccion, mejora, requerimiento nuevo, cambio prioridades

---

## 11. Riesgos

| Riesgo | Impacto | Mitigacion |
|--------|---------|------------|
| Backlog incompleto | Alto | Revision semanal |
| Defectos no detectados | Alto | Pruebas obligatorias |
| Cambios no controlados | Medio | Proceso formal |
| Falta de pruebas | Alto | Checklist |

---

## 12. Conclusion

El plan establece los estandares, metricas y procesos de calidad para el ERP Web de Seguridad LTDA, asegurando cumplimiento de atributos requeridos y estandares de industria.
