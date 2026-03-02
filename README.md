
# Grupo-2-Biblioteca-Digital

## 📑 Tabla de Contenido

1. [Introduccion](introduccion)
3. [Requerimiento Funcional 1](docs/hu01-registro-usuario)
4. [Requerimiento Funcional 2](docs/Solicitud-de-prestamo)
5. [Requerimiento Funcional 3](docs/hu03-renovar-prestamo)
6. [Requerimientos No Funcionales](docs/requerimiento-no-funcional)
7. [Trazabilidad ](docs/tabla-trazabilidad)

# RF-01 Registro de Usuario

## HU-01 – Registro de Usuario

**Como** visitante  
**quiero** crear una cuenta en la biblioteca digital  
**para** poder acceder a los libros disponibles  

### Criterios de Aceptación

- El correo no debe estar previamente registrado.
- Debe validarse formato de correo.
- Debe mostrarse confirmación de registro exitoso.

## RF-02: Solicitud de Préstamo

### HU-02: Solicitar Préstamo Digital

**Como** usuario registrado,  
**quiero** solicitar el préstamo de un libro digital,  
**para** poder leerlo en línea.

### Criterios de Aceptación

- Solo los usuarios autenticados pueden solicitar un préstamo.
- El sistema debe verificar la disponibilidad del libro.
- Debe generarse una confirmación del préstamo.

## RF-03 Renovación de Préstamo

### *HU-03 – Renovar Préstamo*

Como usuario registrado quiero renovar un préstamo activo para extender el tiempo de lectura

#### *Criterios de Aceptación:*
-  Solo puede renovarse antes de la fecha límite.
-  No debe permitirse renovar si hay lista de espera.
-  Debe actualizarse la nueva fecha de vencimiento.

# Tabla Trazabilidad

| HU | RF | Caso de Prueba | Estado |
|----|------------|----------|--------|
| HU-01 | RF-01 - Registro de Usuario | El correo no debe estar previamente registrado. | Pendiente | 
| HU-02 | RF-02 - Solicitud de Préstamo | El sistema debe verificar disponibilidad del libro. | Pendiente | 
| HU-03 | RF-03 - Renovar Préstamo | Solo puede renovarse antes de la fecha límite. | Pendiente | 



