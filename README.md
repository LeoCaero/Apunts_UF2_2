# Apunts_UF2_2

## Hediondez de código

La hediondez de código, en inglés «code smell», es una característica que hay en el código fuente que puede indicar un problema en mas profundidad.
No llegan a ser «bugs» (errores), ya que técnicamente no són fallos incorrectos,quiere decir que no impiden la funcionalidad correcta del programa. Su función,
es indicar las deficiencias en el diseño del programa que puedan llegar a ralentizar el código, incluso, aumenta la probabilidad de riesgos o fallos en un
futuro.

### Ejemplos de «code smell»:
  - Código duplicado.
  - Métodos grandes.
  - Herencias rechazadas.
  - Inundación de parámetros
  - Clases largas.

## Análisis de código:

Hay 2 tipos de análisis de código:

  - **Análisis estático**:
    Para hacer análisis estáticos, utilizamos los llamados «linters» o mediante sitios web para inspeccionar el código, también llamados (Continuous Inspection).
    **Linters**: herramientas que realizan tareas de comprobación en cualquier lenguaje de programación. Las herramientas de tipo lint generalmente funcionan realizando un análisis estático del código fuente.

**Tipos de linters**:
  - lint: C
  - sonar: Java
  - JSLint, ESLint: Javascript

    **Continuous Inspection**: Sitios web que ofrecen la inspección del código de forma online.

    Tipos de Continuous Inspecters:
    - Scrutinizer.
    - SonarQube
