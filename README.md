# 1DAMV_TellaTrejo_Beatriz

# ¿Qué es un programa informático?
En la ingeniería de software, un programa informático se define como un conjunto estructurado de instrucciones y datos expresados en un lenguaje formal, diseñados para ser ejecutados por una computadora con el objetivo de resolver un problema específico o realizar una tarea determinada.
A nivel técnico, es la materialización lógica de un algoritmo. Transforma datos de entrada (inputs) en resultados útiles (outputs), gestionando los recursos del sistema (memoria, procesador) a través del sistema operativo.

# Diferencia entre código fuente, código objeto y código ejecutable.

**Código fuente**: Es el texto puro escrito por el programador utilizando un lenguaje de programación de alto nivel (como C++, Java, Python). Es legible por seres humanos.
Sus características clave son:
1. Alta abstracción. Es aquel que permite al programador escribir instrucciones de una forma más sencilla y cercana al lenguaje humano.
2. Contiene lógica, comentarios y nombres de variables.Facilita la comprensión y organización del código.
3. El procesador no puede entenderlo directamente. Es necesario utilizar un compilador o un intérprete que traduzca estas instrucciones a un lenguaje que el ordenador pueda ejecutar.

Por tanto, "código fuente" describe principalmente la forma en que se expresa el programa para su desarrollo, no necesariamente un formato concreto de archivo ni una etapa única de ejecución.

**Código objeto**: Es el resultado intermedio que genera el compilador al traducir el código fuente. Está escrito en lenguaje de máquina (binario) o código de bytes.
Sus características clave son:
1. Formado por 0 y 1. Son los valores que utiliza el ordenador para entender las instrucciones.
2. Incompleto: Necesita incorporar algunos elementos que se encuentran fuera del programa como las librerías externas.
3. No se puede ejecutar por sí solo. Hasta que se añadan todas las partes que necesita, no puede funcionar por sí solo.


Por eso es incorrecto considerar siempre código objeto = programa ejecutable.

**Código ejecutable**: Es el archivo final obtenido después de que un enlazador (linker) une los diferentes archivos de código objeto con las librerías del sistema necesarias.
Sus características clave son:
1. Listo para cargarse en la memoria RAM. Es un programa que ya está preparado para funcionar en el ordenador. Se abre y se carga en la memoria RAM.
2. Autónomo y directo para la CPU. No necesita añadir otras partes para poder funcionar, ya que está completo y puede comunicarse directamente con el procesador.
3. Ejemplos: archivos .exe en Windows o binarios en Linux.

Por tanto, conviene no utilizar "ejecutable", "código objeto", "código máquina" y "bytecode" como sinónimos.

# Etapas del desarrollo del software.
El desarrollo de un programa suele pasar por varias etapas:
1. **Planificación**: se decide qué problema se quiere resolver y qué debe hacer el programa.
2. **Diseño**: se piensa cómo será el programa y cómo funcionarán sus distintas partes.
3. **Programación**: se escribe el código que hará funcionar el programa.
4. **Pruebas**: se comprueba que funciona correctamente y se buscan errores.
5. **Puesta en marcha**: el programa se instala o se hace disponible para que pueda utilizarse.
6. **Mantenimiento**: se corrigen errores y se hacen mejoras o cambios cuando son necesarios.
   
Estas etapas no siempre se realizan una sola vez. Normalmente se repiten a medida que el programa se mejora y aparecen nuevas necesidades.


