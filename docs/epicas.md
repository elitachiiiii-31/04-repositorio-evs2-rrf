# Epicas e Historias de Usuario

## Proyecto: ERP Web Seguridad LTDA

---

## Format

**Epica:** E# - Nombre  
**Historia:** HU# - Como <rol>, quiero <X> para <Y>  
**Criterios de aceptacion:** Lista de condiciones  
**Sprint:** Numero de sprint  
**Responsable:** Dev asignado

---

## E1 - Gestion de Personal (RR.HH.)

### HU01
**Como** administrador  
**Quiero** registrar ficha completa del personal  
**Para** mantener actualizados los datos personales y laborales

**Criterios:**
- Campos: nombre, RUT, direccion, telefono, email
- Datos laborales: cargo, departamento, fecha ingreso
- Datos previsionales: AFP, salud, seguro

**Sprint:** 1

### HU02
**Como** administrador  
**Quiero** registrar contratos y finiquitos  
**Para** gestionar la documentacion contractual

**Criterios:**
- Tipo de contrato, fechas, remuneracion
- Generar documentos PDF

**Sprint:** 1

### HU03
**Como** encargado RR.HH.  
**Quiero** registrar licencias medicas  
**Para** controlar ausencias justificadas

**Criterios:**
- Tipo, fechas inicio/fin, medico, diagnostico

**Sprint:** 1

---

## E2 - Remuneraciones y Asistencia

### HU04
**Como** encargado RR.HH.  
**Quiero** controlar asistencia y atrasos  
**Para** gestionar remuneraciones y justificar ausentismos

**Criterios:**
- Registro diario entrada/salida
- Calculo de tardanzas y ausencias

**Sprint:** 1

### HU05
**Como** encargado RR.HH.  
**Quiero** gestionar vacaciones  
**Para** controlar saldos y solicitudes

**Criterios:**
- Calculo de dias disponibles
- Aprobacion de solicitudes

**Sprint:** 1

### HU06
**Como** encargado RR.HH.  
**Quiero** generar liquidaciones  
**Para** informar remuneraciones mensuales

**Criterios:**
- Calculo automatico de remuneraciones
- Impresion y descarga PDF

**Sprint:** 1

---

## E3 - Portal del Empleado

### HU07
**Como** empleado  
**Quiero** ver mi informacion personal  
**Para** acceder a mis datos sin depender de RR.HH.

**Criterios:** Ficha, contratos, documentos  
**Sprint:** 1

### HU08
**Como** empleado  
**Quiero** consultar mis liquidaciones  
**Para** acceder a mi informacion mensual

**Criterios:** Historico, impresion, descarga  
**Sprint:** 1

### HU09
**Como** empleado  
**Quiero** ver vacaciones y licencias  
**Para** conocer mis saldos y estado

**Criterios:** Saldo, historico, estado  
**Sprint:** 1

---

## E4 - Inventario y Bodega

### HU10
**Como** bodeguero  
**Quiero** registrar productos  
**Para** gestionar el catalogo de inventario

**Criterios:** Codigo, nombre, categoria, precio  
**Sprint:** 2

### HU11
**Como** bodeguero  
**Quiero** controlar entradas y salidas  
**Para** mantener stock en tiempo real

**Criterios:** Movimientos, stock actualizado  
**Sprint:** 2

### HU12
**Como** jefe bodega  
**Quiero** gestionar multiples bodegas  
**Para** administrar inventario distribuido

**Criterios:** Crear, editar, asignar productos  
**Sprint:** 2

### HU13
**Como** bodeguero  
**Quiero** gestionar reservas de stock  
**Para** asegurar disponibilidad

**Criterios:** Reserva, asignacion, liberacion  
**Sprint:** 2

---

## E5 - Ventas y Clientes

### HU14
**Como** vendedor  
**Quiero** gestionar listas de precios  
**Para** aplicar tarifas correctas

**Sprint:** 2

### HU15
**Como** vendedor  
**Quiero** registrar ficha de clientes  
**Para** gestionar informacion comercial

**Sprint:** 2

### HU16
**Como** vendedor  
**Quiero** registrar ventas  
**Para** procesar operaciones comerciales

**Sprint:** 2

---

## E6 - Portal del Cliente

### HU17-19
Buscar productos, ver disponibilidad, seguimiento de pedidos  
**Sprint:** 2

---

## E7 - Seguridad y Compatibilidad

### HU20-22
Autenticacion, roles, acceso movil  
**Sprint:** 1-2

---

## E8 - Reportes

### HU23-25
Reporte asistencia, stock, dashboard ventas  
**Sprint:** 2
