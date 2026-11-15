# Autos Colombia – Sistema de Información para Parqueadero

## Descripción del proyecto

Sistema de información web desarrollado como proyecto académico para la asignatura Ingeniería de Software de la Institución Universitaria Digital de Antioquia.

Su objetivo es apoyar la administración del parqueadero Autos Colombia mediante la gestión de entradas y salidas de vehículos, usuarios, celdas de estacionamiento, asignaciones mensuales y pagos. El proyecto se construyó de manera incremental a través de tres iteraciones, correspondientes a las Evidencias de Aprendizaje 1, 2 y 3.

## Evidencia de Aprendizaje 1 – Iteración 1

**Gestión de entrada y salida de vehículos**

Funcionalidades:

- Registrar la entrada de vehículos autorizados.
- Consultar los vehículos registrados.
- Registrar la salida de los vehículos.
- Calcular el tiempo de permanencia.
- Evitar entradas duplicadas de vehículos que ya se encuentran dentro del parqueadero.
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

## Evidencia de Aprendizaje 3 – Iteración 3

**Gestión de pagos y obligaciones**

Funcionalidades:

- Registrar pagos asociados al usuario, vehículo y asignación mensual.
- Calcular el valor de la mensualidad y los valores proporcionales (prorrateo), según las reglas implementadas.
- Registrar el método de pago seleccionado, como efectivo, transferencia, Nequi o tarjeta.
- Consultar el historial de pagos.
- Consultar las obligaciones y el estado de los pagos por período.
- Generar y visualizar comprobantes digitales.
- Imprimir el comprobante de pago.
- Validar los datos requeridos para el registro de la operación y evitar inconsistencias o duplicidades.

## Tecnologías utilizadas

- **HTML5:** estructura de la aplicación.
- **CSS3:** diseño y presentación visual.
- **JavaScript:** funcionalidades, lógica de negocio y validaciones.
- **LocalStorage:** almacenamiento local de la información en el navegador.
- **GitHub:** alojamiento del repositorio y control de versiones.
- **GitHub Pages:** publicación del prototipo web.
- **StarUML:** elaboración de los diagramas UML del proyecto.

## Instrucciones de ejecución

1. Descargar o clonar este repositorio.
2. Abrir el archivo `index.html` en Google Chrome o Microsoft Edge.
3. Navegar por los módulos desde el menú de la aplicación.
4. Registrar o consultar usuarios y asociarles sus vehículos.
5. Registrar las celdas y realizar las asignaciones correspondientes.
6. Probar el registro de entrada y salida de vehículos.
7. Ingresar al módulo de pagos y seleccionar una asignación mensual disponible para registrar un pago de prueba.
8. Consultar el historial, las obligaciones y el comprobante generado.
9. Visualizar e imprimir el comprobante digital.

## Reglas de negocio

- Cada usuario debe tener un documento único.
- No se permiten placas duplicadas.
- Cada celda debe tener un código único.
- Una celda no puede tener dos asignaciones mensuales activas simultáneamente.
- Las celdas fuera de servicio no pueden asignarse.
- Las asignaciones deben respetar el tipo de vehículo.
- La salida temporal de un vehículo no libera automáticamente su celda mensual.
- Para liberar definitivamente una celda debe finalizarse la asignación correspondiente.
- Los pagos deben relacionarse con la obligación o asignación correspondiente.
- Los valores y períodos registrados deben validarse antes de confirmar el pago.

## Pruebas del sistema

El proyecto contempla pruebas funcionales de:

- Registro, consulta y actualización de usuarios.
- Asociación y validación de vehículos.
- Registro y consulta de celdas.
- Asignación y finalización de asignaciones mensuales.
- Entrada y salida de vehículos, cálculo de permanencia y registro de novedades.
- Registro y consulta de pagos y obligaciones.
- Generación, visualización e impresión de comprobantes.
- Validación de datos y persistencia de la información en el navegador.

## Limitaciones del prototipo

El sistema corresponde a un prototipo académico. La información se almacena localmente mediante LocalStorage, por lo que no se sincroniza entre diferentes dispositivos o navegadores.

Los métodos de pago se registran como información de la operación; el prototipo no se conecta con entidades bancarias ni procesa transacciones electrónicas reales. Esta versión tampoco cuenta con una base de datos centralizada ni un sistema de autenticación robusto. Se recomienda utilizar información ficticia durante las pruebas.

## Autor

**Duberney Barrios Vélez**

Institución Universitaria Digital de Antioquia  
Asignatura: Ingeniería de Software  
Evidencias de Aprendizaje 1, 2 y 3 – Iteraciones 1, 2 y 3  
Año: 2026

## Repositorio

https://github.com/duberneybarrios-design/Autos-Colombia-Parqueadero

## Aplicación publicada

https://duberneybarrios-design.github.io/Autos-Colombia-Parqueadero/
