# Apuntes_UF2_2

## Optimización

### Hediondez del Codigo

Hediondez (Code smell en Ingles) es cualquier síntoma en el código fuente de un programa que posiblemente indica un problema más profundo. Las hediondeces del código usualmente no son bug de programación (errores). Técnicamente no son incorrectos y en realidad no impiden que el programa funcione correctamente. En cambio, indican deficiencias en el diseño software que puede ralentizar el desarrollo o aumentan el riesgo de errores o fallos en el futuro. 

Ejemplos:
- Codigo duplicado
- Demasiados parametros
- Herencia rechazada
- Identificadores excesivamente largos    
- Envidia de características

### Análisis de Codigo

#### Análisis dinámico (unit test) 
El Análisis dinámico de software es un tipo de análisis de software que supone la ejecución del programa y observar su comportamiento. Para que el análisis dinámico resulte efectivo el programa debe ser analizado y se debe ejecutar con los suficientes casos de prueba como para producir un comportamiento interesante.

#### Análisis estático (lint)

Análisis estático de software es un tipo de análisis de software que se realiza sin ejecutar el programa.​ En la mayoría de los casos, el análisis se realiza en alguna versión del código fuente y en otros casos se realiza en el código objeto.

##### Linters:

Analizadores estáticos de código:
- lint: C
- sonar: Java
- JSLint, ESLint: Javascript

##### Continuous Inspection o Continuous Analysis

Sitios web que ofrecen inspección de código:
- Scrutinizer
- SonarQube

##### Refactorización

Es el proceso de reestructuracion del código fuente, alterando su estructura interna sin cambiar su comportamiento externo.
    
Técnicas:
- Renombrar variables 
- Pasar código duplicado a funciones 
- Eliminar código inalcanzable 
- Eliminar código redundante 
- Eliminar código muerto

## Documentacion


### Tipos de documentación

- Documentación de código
- Documentación técnica
- Documentación de usuario

### Formatos de documentación

- HTML (p. ej. Javadoc)
- Markdown (p. ej. Gitbook)
- reStructuredText (p. ej. Readthedocs)
- asciiDoc


