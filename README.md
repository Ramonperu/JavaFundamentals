

# Java Fundamentals

Bienvenidos a la guía básica, para principiantes, sobre java realizada por Ramon Peinado Ruiz gracias al curso de accenture.



## CONCEPTOS BASICOS

### ¿Como inicio Java ?

<img align="center" src="/img/1ºimagenn.PNG"  />

Java es uno de los lenguajes de programación más influyentes y omnipresentes en el mundo actual, desempeñando un papel crucial tanto en el ámbito de Internet como en la informática en general.

Su origen se remonta a 1991, cuando James Gosling y su equipo en Sun Microsystems concibieron este lenguaje con la visión de proporcionar una estructura simple y flexible, capaz de ejecutarse en una variedad de sistemas operativos.

En 1995, Java dio un giro significativo cuando Sun Microsystems lo reenfocó hacia una plataforma informática web, lo que marcó el inicio de su comercialización y su crecimiento exponencial en la industria tecnológica.

La adquisición de Sun Microsystems por parte de Oracle en 2009 consolidó aún más la posición de Java en el mercado.

Java se ha ganado una reputación por su rapidez, seguridad y confiabilidad. Su presencia es innegable en numerosas aplicaciones y sitios web, muchos de los cuales dependen de la presencia de Java para su funcionamiento. Desde portátiles hasta centros de datos, consolas de videojuegos, teléfonos móviles, electrodomésticos e incluso la infraestructura de Internet misma, Java se encuentra en prácticamente todos los rincones del mundo digital moderno. Su versatilidad y robustez lo convierten en un pilar fundamental en el desarrollo de tecnologías emergentes y soluciones innovadoras.

### Principios de java

- ORIENTADO A OBJETOS

   Java se erige como un destacado lenguaje de programación orientado a objetos (POO), donde los datos se modelan mediante objetos. Esta estructura ofrece una biblioteca estándar robusta y versátil, que ha sido ampliamente probada, asegurando así su fiabilidad y reutilización en diversos contextos y aplicaciones.

- SEGURO 

  La seguridad es un pilar fundamental en Java. Incorpora características que blindan a los programadores contra errores inadvertidos que podrían comprometer la integridad del sistema. Diseñado para operar en un amplio espectro de entornos, desde el mundo del entretenimiento hasta las aplicaciones empresariales, Java se destaca por ser un lenguaje fuertemente tipado, capaz de realizar validaciones tanto en tiempo de compilación como de ejecución, ofreciendo así una sólida defensa contra vulnerabilidades y amenazas.

- RECOLECTOR DE BASURA 

  Una de las características más destacadas de Java es su sistema de gestión de memoria automática. Cuando se crea un objeto, Java asigna automáticamente el espacio de memoria correspondiente. Además, el recolector de basura de Java monitorea continuamente los objetos que ya no son necesarios para la aplicación y libera la memoria que ocupaban. Esta funcionalidad evita el problema común de las fugas de memoria que aquejan a otros lenguajes de programación, garantizando así un uso eficiente de los recursos del sistema y una mayor estabilidad en las aplicaciones desarrolladas en Java.

- MULTIHILO 

  Java brinda un sólido soporte para la programación multihilo, donde cada hilo representa un flujo de control dentro del programa, permitiendo la ejecución de múltiples tareas simultáneamente. Esta capacidad es especialmente valiosa en aplicaciones que requieren un alto grado de concurrencia y procesamiento paralelo.

- PORTABLE 

  Una de las características distintivas de Java es su portabilidad. Bajo el lema "write once, run anywhere" (escribe una vez, ejecuta en cualquier lugar), un programa Java puede ejecutarse en cualquier plataforma o dispositivo que cuente con una máquina virtual Java (JVM). Esto significa que un programa desarrollado en Java en una plataforma, como Windows, puede ejecutarse sin modificaciones en otra plataforma, como Mac (iOS), facilitando así la distribución y el despliegue de aplicaciones en diferentes entornos informáticos.

  ### Como funciona

Para llevar a cabo el desarrollo de un programa en Java, se deben seguir una serie de pasos fundamentales que culminan en su funcionamiento.

En primer lugar, el programador elabora las tareas que desea ejecutar mediante código escrito en el lenguaje Java. Este código fuente, que constituye el punto de partida del proceso, se guarda en un archivo de origen con la extensión ".java".

A continuación, el compilador de Java entra en acción. Si no se encuentran errores de sintaxis, este transforma el código fuente en un formato comprensible para la máquina virtual de Java, conocido como ByteCode. Como resultado, se genera un archivo con el mismo nombre que el código fuente, pero con la extensión ".class".

Posteriormente, la Máquina Virtual Java asume la responsabilidad de traducir las instrucciones del ByteCode a un lenguaje máquina comprensible para el sistema operativo en el que se está ejecutando.

Finalmente, el programa desarrollado por el desarrollador se ejecuta, permitiendo que las tareas diseñadas se lleven a cabo de acuerdo con la lógica y la funcionalidad establecidas.

<img align="center" src="/img/2ºimagenn.PNG"  />

### Estructura de una clase de Java

Estos son los componentes de Java

**PAQUETE (PACKAGE):** Los paquetes en Java representan una forma estructurada de organizar las clases, definiendo la ubicación de la clase dentro del sistema de archivos. La declaración de paquetes es la primera línea de código que se encuentra en una clase Java. Las clases que comparten una funcionalidad similar se agrupan en un mismo paquete. Cada clase puede pertenecer a un único paquete, y si no se especifica un paquete, el compilador crea automáticamente uno denominado "default package".

**CLASE (CLASS)** Una vez definido el paquete, el siguiente paso es especificar el nombre de la clase. La clase es la unidad fundamental de estructura en Java, encapsulando el código y la funcionalidad relacionada.

**SENTENCIAS** En Java, una sentencia representa la unidad más básica de ejecución dentro de un programa. Cada sentencia se finaliza con un punto y coma (;).

**BLOQUES** Los bloques en Java son conjuntos de sentencias delimitados por llaves ({}). Estos bloques permiten agrupar múltiples sentencias para formar una unidad lógica y funcional dentro del código.

**MÉTODO** En Java, una clase no solo encapsula datos, sino que también implementa comportamientos. Estos comportamientos se definen mediante la creación de métodos, los cuales deben especificar el tipo de dato que retornan seguido del nombre del método (se recomienda que el nombre sea un verbo). Abordaremos este tema con mayor detalle en secciones posteriores.

Un método especial en Java es el método main. Este método sirve como punto de entrada para el programa Java y siempre debe estar definido de la siguiente manera:

```
public static void main(String args[])
```

**COMENTARIOS** Java permite la inclusión de comentarios dentro del código para aclarar las instrucciones. Existen tres tipos de comentarios en Java:

1. Comentarios de una sola línea:

```
// Esto es un comentario
```

1. Comentarios multilínea:

```
/* Esto es un comentario
   de una o más líneas */
```

1. Comentarios de documentación para la herramienta Javadoc:

```

/** Esto es un comentario para javadoc */
```

Los comentarios de Javadoc se utilizan para generar documentación automática a partir del código fuente Java utilizando la herramienta Javadoc.

**Ejemplo basico**

<img align="center" src="/img/3ºimagenn.PNG"  />

Instalacion de JDK y Eclipse:

Para instalar jdk vamos a esta pagina, descargamos el exe y lo ejecutamos no hace falta configurar nada.

<img align="center" src="/img/5ºimagenn.PNG"  />

Para instalar eclipse nos dirigimos a esta pagina https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2020-09/R/eclipse-inst-jre-win64.exe&mirror_id=1190

Descargamos el exe y ejecutamos, tras esto seleccionamos esta version







<img align="center" src="/img/4ºimagenn.PNG"  />

Aceptamos términos y condiciones y estaríamos listos para comenzar tras cerrar la pestaña de bienvenida

### Denominaciones: Identificadores y palabras clave.

**Reglas generales:**

- Deben usarse nombres que sean significativos. Por ejemplo, clase RecetaBizcocho, si queremos realizar un programa para elaborar una receta.
- Se recomienda empezar por una letra, aunque después se pueden emplear números.
- No se permite el uso de caracteres especiales como: espacio en blanco, +, %,*, etc.
- Los nombres de clases comienzan con mayúsculas y cuando son nombres compuestos cada palabra comienza con mayúsculas. Ej. public class RecetaBizcocho.
- Java distingue entre mayúsculas y minúsculas. Ej. bizcocho es distinto que Bizcocho.
- Los nombres de constantes se escriben todo con mayúsculas y si el nombre es compuesto se usa el carácter de subrayado para separar las palabras. Ej. TIEMPO_HORNEADO, pero para el nombre de la clase, métodos y atributos, no se usa el carácter de subrayado.
- No pueden coincidir con palabras reservadas/clave (las vemos en el siguiente punto).

**Palabras claves**

<img align="center" src="/img/7ºimagenn.PNG"  />

<img align="center" src="/img/8ºimagenn.PNG"  />WA
