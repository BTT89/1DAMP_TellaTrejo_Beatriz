# 1DAMV_TellaTrejo_Beatriz 

# ¿Qué es un programa informático?
En la ingeniería de software, un programa informático se define como un conjunto estructurado de instrucciones y datos expresados en un lenguaje formal, diseñados para ser ejecutados por una computadora con el objetivo de resolver un problema específico o realizar una tarea determinada.
A nivel técnico, es la materialización lógica de un algoritmo. Transforma datos de entrada (inputs) en resultados útiles (outputs), gestionando los recursos del sistema (memoria, procesador) a través del sistema operativo.

# Diferencia entre código fuente, código objeto y código ejecutable.

### - **Código fuente**
Es el texto puro escrito por el programador utilizando un lenguaje de programación de alto nivel (como C++, Java, Python). Es legible por seres humanos.
Sus características clave son:
1. Alta abstracción. Es aquel que permite al programador escribir instrucciones de una forma más sencilla y cercana al lenguaje humano.
2. Contiene lógica, comentarios y nombres de variables.Facilita la comprensión y organización del código.
3. El procesador no puede entenderlo directamente. Es necesario utilizar un compilador o un intérprete que traduzca estas instrucciones a un lenguaje que el ordenador pueda ejecutar.

**Por tanto, "código fuente" describe principalmente la forma en que se expresa el programa para su desarrollo, no necesariamente un formato concreto de archivo ni una etapa única de ejecución**.


### - **Código objeto**
Es el resultado intermedio que genera el compilador al traducir el código fuente. Está escrito en lenguaje de máquina (binario) o código de bytes.
Sus características clave son:
1. Formado por 0 y 1. Son los valores que utiliza el ordenador para entender las instrucciones.
2. Incompleto: Necesita incorporar algunos elementos que se encuentran fuera del programa como las librerías externas.
3. No se puede ejecutar por sí solo. Hasta que se añadan todas las partes que necesita, no puede funcionar por sí solo.
 ![esquema código obejto](https://github.com/BTT89/1DAMP_TellaTrejo_Beatriz/blob/main/ESQUEMA%20C%C3%93DIGO%20OBJETO.png)

**Por eso es incorrecto considerar siempre código objeto = programa ejecutable**.


### - **Código ejecutable**
Es el archivo final obtenido después de que un enlazador (linker) une los diferentes archivos de código objeto con las librerías del sistema necesarias.
Sus características clave son:
1. Listo para cargarse en la memoria RAM. Es un programa que ya está preparado para funcionar en el ordenador. Se abre y se carga en la memoria RAM.
2. Autónomo y directo para la CPU. No necesita añadir otras partes para poder funcionar, ya que está completo y puede comunicarse directamente con el procesador.
3. Ejemplos: archivos .exe en Windows o binarios en Linux.

**Por tanto, conviene no utilizar "ejecutable", "código objeto", "código máquina" y "bytecode" como sinónimos**.

# Etapas del desarrollo del software.
Las etapas del desarrollo de software, conocidas como el Ciclo de vida de desarrollo de software, son un conjunto de fases ordenadas que van desde la idea inicial hasta el uso y mejora continua del producto.
1. **Planificación**: se decide qué problema se quiere resolver y qué debe hacer el programa. La primera fase del SDLC establece las bases para todo el proyecto mediante la definición de objetivos claros y la identificación de lo que se necesita para lograrlos. Durante esta fase inicial, los equipos deben tener en cuenta las necesidades y expectativas de las partes interesadas, además de la viabilidad general del proyecto, para decidir cómo compilar la aplicación y cuándo se implementará.
El planeamiento del proyecto garantiza que todos los implicados comprendan exactamente lo que el software debe ofrecer, al tiempo que confirman que todos los recursos necesarios, como el tiempo y los presupuestos, están disponibles. Esta fase del SDLC es esencial ya que ayuda a evitar que los problemas técnicos y los costes inesperados retrasen o hagan descarrilar el proyecto.
2. **Análisis**:Después de establecer un plan de proyecto completo y asignar los recursos necesarios, el equipo debe empezar a analizar cada requisito de software para determinar cómo debe funcionar la solución. En función de este análisis, los desarrolladores pueden crear una lista detallada de especificaciones del sistema que ayuden a guiar las fases posteriores del SDLC.
Considere la posibilidad de visualizar cómo funciona la solución en diagramas de casos de uso y diagramas de flujo de datos para proporcionar a los equipos representaciones fáciles de entender de la funcionalidad y la estructura del software. Esto ayuda a validar si el software cumplirá los requisitos de las partes interesadas, lo que reduce la probabilidad de costosos problemas y vuelve a trabajar más adelante.
3. **Diseño**: Se piensa cómo será el programa y cómo funcionarán sus distintas partes. En este punto, el equipo debe decidir la arquitectura general que tendrá el software y definir cómo los componentes clave pueden interactuar entre sí. La creación de diseños y modelos detallados del sistema es fundamental para detectar posibles problemas en una fase temprana y garantizar que el producto final satisfaga todas las necesidades de los usuarios y las expectativas de las partes interesadas.
Los patrones de diseño aceleran esta fase del SDLC al proporcionar soluciones probadas y reutilizables a problemas comunes de diseño de software. Además, las herramientas de creación de prototipos le ayudan a visualizar las interfaces de usuario y la funcionalidad del sistema mediante la optimización de la creación de bocetos de diseño.
4. **Desarrollo**: A lo largo de esta fase, los equipos traducen las especificaciones de diseño y los requisitos del sistema en código real. El objetivo es compilar una solución de software completa y funcional lista para probarse e implementarse. La fase de desarrollo suele ser iterativa, ya que los desarrolladores suelen revisar y refinar su código para solucionar problemas técnicos o cambios en los requisitos.
Por lo general, los equipos de desarrollo colaboran entre sí para garantizar que todos los componentes del software se integren y funcionen de forma correcta. Considere la posibilidad de establecer estándares y directrices de codificación para mantener el código limpio y fácil de mantener, y adoptar sistemas de control de versiones para administrar mejor cada cambio realizado. Además, ayude a su organización a ahorrar tiempo y reducir los costes de desarrollo mediante herramientas de poco código para compilar el software.
5. **Programación**: se escribe el código que hará funcionar el programa.
6. **Pruebas**: se comprueba que funciona correctamente y se buscan errores.
7. **Puesta en marcha**: El programa se instala o se hace disponible para que pueda utilizarse. Después de que las pruebas confirmen que el software cumple todos los requisitos y estándares necesarios, su organización está lista para ofrecer la solución a los usuarios finales. Empiece compilando una compilación final del software y preparando el entorno de producción, incluidos los servidores, las bases de datos y las configuraciones de red. A continuación, coordine los recursos y programe tareas, e implemente estrategias de reversión que le ayuden a revertir el sistema a un estado anterior y estable en caso de que surjan problemas, para garantizar una implementación sin problemas.
8. **Mantenimiento**: Se corrigen errores y se hacen mejoras o cambios cuando son necesarios.La fase final del SDLC es continua y comienza inmediatamente después de la puesta en marcha. El mantenimiento de software ayuda a garantizar que el software funcione correctamente, esté protegido y satisfaga las necesidades cambiantes de los usuarios a lo largo del tiempo.
 Entre las actividades clave se incluyen:
- Supervisión de rendimiento. Realice un seguimiento del rendimiento del software para identificar y solucionar posibles problemas. Además, recopile comentarios de los usuarios para identificar las áreas de mejora.
- Corrigiendo errores. Recopile y analice registros de errores para buscar y priorizar errores, y desarrollar revisiones para corregirlos.
- Proporcionando actualizaciones. Agregue nuevas características, mejore las existentes y solucione las vulnerabilidades de seguridad en el software.
- Ofrece soporte técnico. Proporcione a los usuarios información e instrucciones que les ayudarán a usar y comprender diversas características y actualizaciones.
   
**Estas etapas no siempre se realizan una sola vez. Normalmente se repiten a medida que el programa se mejora y aparecen nuevas necesidades**.


