# Product Backlog - ERP Web Seguridad LTDA

## Formato Historia de Usuario

Como <rol>, quiero <funcionalidad> para <beneficio>.

---

## Modulo RR.HH.

### E1 - Gestion de Personal

| ID | Historia | Criterios de Aceptacion | Sprint |
|----|----------|-------------------------|--------|
| HU01 | Como administrador, quiero registrar ficha completa del personal | Datos basicos, laborales, contact, previsionales | 1 |
| HU02 | Como administrador, quiero registrar contratos y finiquitos | Tipo contrato, fechas, documentos | 1 |
| HU03 | Como encargado RR.HH., quiero registrar licencias medicas | Tipo licencia, fechas, seguimiento | 1 |

### E2 - Remuneraciones y Asistencia

| ID | Historia | Criterios de Aceptacion | Sprint |
|----|----------|-------------------------|--------|
| HU04 | Como encargado RR.HH., quiero controlar asistencia y atrasos | Registro diario, tardanzas, ausencias | 1 |
| HU05 | Como encargado RR.HH., quiero gestionar vacaciones | Solicitudes, aprobaciones, registro | 1 |
| HU06 | Como encargado RR.HH., quiero generar liquidaciones | Calculo automatico, impresion PDF | 1 |

### E3 - Portal del Empleado

| ID | Historia | Criterios de Aceptacion | Sprint |
|----|----------|-------------------------|--------|
| HU07 | Como empleado, quiero ver mi informacion personal | Ficha, contratos, documentos | 1 |
| HU08 | Como empleado, quiero consultar mis liquidaciones | Historico, impresion, descarga | 1 |
| HU09 | Como empleado, quiero ver mis vacaciones y licencias | Saldo, historico, estado | 1 |

---

## Modulo Inventario y Ventas

### E4 - Inventario y Bodega

| ID | Historia | Criterios de Aceptacion | Sprint |
|----|----------|-------------------------|--------|
| HU10 | Como bodeguero, quiero registrar productos | Codigo, nombre, categoria, precio | 2 |
| HU11 | Como bodeguero, quiero controlar entradas y salidas | Movimientos con stock actualizado | 2 |
| HU12 | Como jefe bodega, quiero gestionar multiples bodegas | Crear, editar, asignar productos | 2 |
| HU13 | Como bodeguero, quiero gestionar reservas de stock | Reserva, asignacion, liberacion | 2 |

### E5 - Ventas y Clientes

| ID | Historia | Criterios de Aceptacion | Sprint |
|----|----------|-------------------------|--------|
| HU14 | Como vendedor, quiero gestionar listas de precios | Crear, editar, aplicar en ventas | 2 |
| HU15 | Como vendedor, quiero registrar ficha de clientes | Datos personales, historico compras | 2 |
| HU16 | Como vendedor, quiero registrar ventas | Productos, cantidad, cliente, precio | 2 |

### E6 - Portal del Cliente

| ID | Historia | Criterios de Aceptacion | Sprint |
|----|----------|-------------------------|--------|
| HU17 | Como cliente, quiero buscar productos | Busqueda, filtros, categorias | 2 |
| HU18 | Como cliente, quiero ver disponibilidad en tiempo real | Stock actualizado por bodega | 2 |
| HU19 | Como cliente, quiero hacer seguimiento de pedidos | Estado pedido, historico | 2 |

---

## Infraestructura y Common

### E7 - Seguridad y Compatibilidad

| ID | Historia | Criterios de Aceptacion | Sprint |
|----|----------|-------------------------|--------|
| HU20 | Como usuario, quiero autenticarme | Login, logout, roles | 1 |
| HU21 | Como sistema, quiero controlar acceso por roles | Permisos por modulo y accion | 1 |
| HU22 | Como usuario, quiero acceder desde movil | Interfaz responsive, PWA | 2 |

### E8 - Reportes

| ID | Historia | Criterios de Aceptacion | Sprint |
|----|----------|-------------------------|--------|
| HU23 | Como jefe de area, quiero reporte de asistencia | Por periodo, departamento | 2 |
| HU24 | Como jefe de area, quiero reporte de stock | Stock actual, movimientos | 2 |
| HU25 | Como gerente, quiero dashboard de ventas | KPIs, graficos, exportacion | 2 |

---

## Priorizacion

| Prioridad | Historias |
|-----------|----------|
| Alta | HU01, HU04, HU20, HU10 |
| Media | HU02, HU05, HU11, HU17 |
| Baja | HU19, HU24, HU25 |
