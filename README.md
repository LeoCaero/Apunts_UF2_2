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

### Análisis estático:
Para hacer análisis estáticos, utilizamos los llamados «linters» o mediante sitios web para inspeccionar el código, también llamados (Continuous Inspection).

**Linters**: herramientas que realizan tareas de comprobación en cualquier lenguaje de programación. Las herramientas de tipo lint generalmente funcionan realizando un análisis estático del código fuente.

#### Tipos de linters:
  - lint: C
  - sonar: Java
  - JSLint, ESLint: Javascript

#### Continuous Inspection: 
Sitios web que ofrecen la inspección del código de forma online.   

Tipos de Continuous Inspecters:
  - Scrutinizer
  - SonarQube

### Análisis dinámico:

Comprueba que la ejecución del código haga lo que el usuario quiere que haga.

## Refactorización

La refactorización, es el proceso de reestructuramiento d código fuente alterando la estructura interna sin tener que cambiar el comportamiento externo del programa.

Técnicas utilizadas a la hora de refactorizar:
  - Renombrar variables.
  - Pasar código duplicado a funciones por separado.
  - Eliminación de código muerto
  - Eliminación de código repetitivo
  - ...

## Documentación

### Tipos de documentación:

  - **Documentación de usuario**: manual de la aplicación para el uso del usuario.
  - **Documentación de codigo**: manual para la administración de la aplicación.
  - **Documentación técnica**: documentación del código para su entendimiento.
 
### Formato de la documentación:
 
La documentación puede ser de uno de los siguientes formatos:

  - HTML: por ejemplo JavaDoc
  - asciiDoc
  - Markdown:  por ejemplo Git
  - ReStructuredText: por ejemplo Readthedocs

## Control de versiones

Sistemas más conocidos:
  - CVS
  - Subversion
  - Git
  - Mercurial
 
**Git**: 

**Características**:
  - Moderno
  - Distribuido
  - Eficiente

**Conceptos**:
  - Repository(local & remoto): donde se trabaja, en este caso, un repositorio
  - Commit: realizar cambios
  - Branch:
    - Checkout: cambiar de "branch"
    - Merge: unir repositorios   
