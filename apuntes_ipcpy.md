## **¿Qué es un lenguaje de programación?**

Es un lenguaje formal que, mediante una serie de instrucciones, le permite a un programador escribir un conjunto de órdenes, acciones consecutivas, datos y algoritmos para, de esa forma, crear programas que controlen el comportamiento físico y lógico de una máquina.

### **¿Qué tipos de lenguaje de programación existen?**

El lenguaje de programación es la base para construir todas las aplicaciones digitales que se utilizan en el día a día y se clasifican en dos tipos principales: lenguaje de bajo nivel y de alto nivel.

## *Lenguaje de programación de bajo nivel*

Son lenguajes totalmente orientados a la máquina.

Este lenguaje sirve de interfaz y crea un vínculo inseparable entre el hardware y el software.

Además, ejerce un control directo sobre el equipo y su estructura física. Para aplicarlo adecuadamente es necesario que el programador conozca sólidamente el hardware. Éste se subdivide en dos tipos:

#### *Lenguaje máquina*

Es el más primitivo de los lenguajes y es una colección de dígitos binarios o bits (0 y 1) que la computadora lee e interpreta y son los únicos idiomas que las computadoras entienden.

**Ejemplo**: 10110000 01100001

No entendemos muy bien lo que dice ¿verdad? Por eso, el lenguaje ensamblador nos permite entender mejor a qué se refiere éste código.

#### *Lenguaje ensamblador*

El lenguaje ensamblador es el primer intento de sustitución del lenguaje de máquina por uno más cercano al utilizado por los humanos.

Un programa escrito en éste lenguaje es almacenado como texto (tal como programas de alto nivel) y consiste en una serie de instrucciones que corresponden al flujo de órdenes ejecutables por un microprocesador.

Sin embargo, dichas máquinas no comprenden el lenguaje emsamblador, por lo que se debe convertir a lenguaje máquina mediante un programa llamado Ensamblador.

Este genera códigos compactos, rápidos y eficientes creados por el programador que tiene el control total de la máquina.

**Ejemplo**: MOV AL, 61h (asigna el valor hexadecimal 61 al registro “AL”)



## *Lenguaje de programación de alto nivel*

Tienen como objetivo facilitar el trabajo del programador, ya que utilizan unas instrucciones más fáciles de entender.

Además, el lenguaje de alto nivel permite escribir códigos mediante idiomas que conocemos (español, inglés, etc.) y luego, para ser ejecutados, se traduce al lenguaje de máquina mediante traductores o compiladores.

### *Traductor*

Traducen programas escritos en un lenguaje de programación al lenguaje máquina de la computadora y a medida que va siendo traducida, se ejecuta.

### *Compilador*

Permite traducir todo un programa de una sola vez, haciendo una ejecución más rápida y puede almacenarse para usarse luego sin volver a hacer la traducción.

### Objetos

- Son la abastracción más alta en el mundo de la programación, es como se modelan nuestros programas.
- Los tipos de datos en python son objetos.
- Son valores en memoria que podemos referenciar a través de variables.
- Los objetos tienen tipos, se dividen en escalares y no escalares. Esto significa que podemos subdividir o no. 

## Type

Con type podemos saber qué tipo de datos es un objeto o algún dato almacenado en una variable. Por ejemplo:

```
my_int = 1
my_float = 1.1
my_bool = True
my_none = None
```

```
type(my_int)
type(my_float
type(my_bool)
type(my_none)
```

## Asignación de variables

En programación cuando declaramos una variable le asignamos un valor a través del signo de igualdad (=).

```
a = 2
x = 4
z = (a * x) / 2
```

#### Entendamos el código:
Con el código anterior estamos diciendo que, la variable `a` tiene asignado el valor de `2`. Cuando se declaran las variables debemos usar nombres exactos. a nuestras variables, esto ayuda a ser más explícitos en lo que se está realizando, refactoricemos el código anterior:

```
base = 2
altura = 4
area = (base * altura) / 2
```

Las variables deben tener un significado concreto y explícito para el entendimiento humano.

## Concatenar

En programación podemos concatenar cadenas de textos, una de las formas de concatenar es utilizando el operador de suma (+), pero en python también podemos hacerlo con la siguiente sintaxis
`f'{"hola mundo " * 3}' lindo`. Con esta sintaxis generamos expresiones donde en este caso el hola mundo se multiplicará tres veces.

### Operaciones en cadenas de textos

- La función `len` nos da la longitud de una cadena.
- Indexing, podemos acceder a los índices de la cadena.
- slicing, nos permite devidir las cadenas en rebanadas.

#### len
```
my_str = 'Javier'
len(my_str)
6
```

#### indexing
```
my_str[0]
'J'
```

#### slicing
`my_string[comienzo:final:pasos]` con slice siempre declaramos el comienzo:elfinal:y los pasos que vamos a saltar.

`my_str[2:]` >>> 'vier'
`my_str[:3]` >>> 'Jav'

