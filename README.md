# Autos Colombia – Sistema de Información para Parqueadero

## Descripción del proyecto

Sistema de información web desarrollado como proyecto académico para la asignatura Ingeniería de Software de la Institución Universitaria Digital de Antioquia.

Su objetivo es facilitar la administración del parqueadero Autos Colombia, mediante el registro y seguimiento de vehículos, la gestión de usuarios, la administración de celdas y el control de asignaciones mensuales.

El desarrollo corresponde a las Evidencias de Aprendizaje 1 y 2, aplicando un proceso de construcción incremental del software.

## Evidencia de Aprendizaje 1 – Iteración 1

**Gestión de entrada y salida de vehículos**

Funcionalidades:

- Registrar la entrada de vehículos autorizados.
- Consultar los vehículos registrados.
- Registrar la salida de vehículos.
- Calcular el tiempo de permanencia.
- Evitar entradas duplicadas de vehículos que ya se encuentran dentro.
- Registrar novedades asociadas a los vehículos.
- Consultar los movimientos y novedades registrados.

## Evidencia de Aprendizaje 2 – Iteración 2

**Gestión de usuarios y gestión de celdas**

### Gestión de usuarios

- Registrar nuevos usuarios.
- Consultar y buscar usuarios registrados.
- Actualizar información personal y de contacto.
- Activar y desactivar usuarios según las reglas establecidas.
- Asociar vehículos a los usuarios.
- Validar documentos y placas para evitar duplicados.

### Gestión de celdas

- Registrar celdas de estacionamiento.
- Consultar la disponibilidad de las celdas.
- Actualizar sus características.
- Asignar celdas a vehículos compatibles.
- Bloquear celdas fuera de servicio.
- Evitar asignaciones mensuales duplicadas.
- Finalizar asignaciones mensuales para liberar celdas.

## Tecnologías utilizadas

- HTML5: estructura de la aplicación.
- CSS3: diseño y presentación visual.
- JavaScript: programación de funcionalidades y validaciones.
- LocalStorage: almacenamiento local de información.
- GitHub: repositorio y control de versiones.
- StarUML: modelado de diagramas UML del proyecto.

## Instrucciones de ejecución

1. Descargar los archivos del repositorio.
2. Abrir el archivo `index.html` en Google Chrome o Microsoft Edge.
3. Registrar un usuario con sus datos.
4. Asociar un vehículo al usuario.
5. Crear una celda de estacionamiento.
6. Asignar la celda al vehículo.
7. Registrar la entrada y salida del vehículo.
8. Consultar movimientos y registrar novedades.
9. Finalizar una asignación mensual cuando corresponda.

## Reglas de negocio

- Cada usuario debe tener un documento único.
- No se permiten placas duplicadas.
- Cada celda debe tener un código único.
- Una celda no puede tener dos asignaciones mensuales activas simultáneamente.
- Las celdas fuera de servicio no pueden asignarse.
- Las asignaciones deben respetar el tipo de vehículo.
- La salida temporal de un vehículo no libera automáticamente su celda mensual.
- Para liberar definitivamente una celda debe finalizarse la asignación correspondiente.

## Pruebas del sistema

Se contemplan pruebas funcionales de registro, consulta, actualización, validación de datos, asignación y liberación de celdas, entrada y salida de vehículos y persistencia de la información.

## Limitaciones del prototipo

El sistema corresponde a un prototipo académico. Los datos se almacenan localmente en el navegador.

Esta versión no implementa pagos electrónicos, autenticación de usuarios ni una base de datos centralizada. Se recomienda utilizar información ficticia durante las pruebas.

## Autor

**Duberney Barrios Vélez**

Institución Universitaria Digital de Antioquia

Asignatura: Ingeniería de Software

Evidencia de Aprendizaje 2 – Iteración 2

Año: 2026

## Repositorio

https://github.com/duberneybarrios-design/Autos-Colombia-Parqueadero
