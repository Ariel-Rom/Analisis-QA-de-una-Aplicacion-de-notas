## 1.Introducción

El objetivo de este proyecto es la creación de una aplicación donde se puedan crear, eliminar y editar notas, además de ordenarlas por categoría.

#### 1.1 Propósito

El propósito de este documento es describir los requisitos funcionales y no funcionales de la aplicación de notas, desarrollada con Spring Boot para el backend y con Angular para el frontend. Además servirá como base para definir los casos de prueba y el plan de QA.

#### 1.2 Alcance

#### La aplicación permitirá a los usuarios:

- Crear notas con título y contenido.
- Editar notas existentes.
- Eliminar notas existentes.
- Clasificar notas por categoría.


#### 1.3 Estrategia de pruebas

Pruebas funcionales:

- Unitarias: Validar métodos y funciones aisladas.
- Integración: Validar la comunicación entre capas.
- Sistemas: Validar que la aplicación completa cumpla con los requisitos.

Pruebas no funcionales:

- Usabilidad: Validar que la UI sea intuitiva
- UI: Revisar que la interfaz gráfica se muestre bien en distintos navegadores.
- Compatibilidad: Testear en varios navegadores.
- Seguridad: Acceso sin Token.

Pruebas exploratorias:

- QA prueba sin guión, buscando fallos inesperados.

Pruebas de Datos:

- Validar persistencia, restricciones y formatos.

#### 1.4 Recursos

- Herramientas de QA: Postman (API testing), Karma(Frontend), JUnit(Backend).
- Entorno: Java 21, Spring Boot, Angular 20.
- Equipo: 1 Desarrollador (Ariel), 1 QA (auto-QA).

#### 1.5 Entregables

Los principales documentos generados durante el proceso de QA serán:

- Documento SRS (Software Requirements Specification): Contendrá la especificación de requisitos funcionales y no funcionales, estrategia de pruebas y recursos.
- Plan de pruebas: Documento que describe el enfoque, los tipos de pruebas a realizar, recursos, roles y cronograma.
- Casos de Prueba (Test Cases): Documento en formato tabla o archivo Markdown, detallando entrada, pasos, resultados esperados y resultados obtenidos.
- Matriz de trazabilidad: Relaciona los requisitos con los casos de prueba (ejecutado, pasado, fallado, bloqueado).
- Reporte de defectos (Bug Report): Documento o issues donde se describen los errores detectados, con pasos para reproducirlos y prioridad.
- Informe final de QA: Resumen del proceso de prueba, métricas y conclusiones sobre la calidad del producto.
