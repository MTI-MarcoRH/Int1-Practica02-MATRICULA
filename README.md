# Int1-Practica02-MATRICULA
---
En esta práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de versiones de proyectos de desarrollo de software, aplicando principios de buenas prácticas en Documentación, Desarrollo Colaborativo y Respaldo en la Nube del Proyecto Integrador. 


Elaborado por: **Su nombre completo aquí** \
Materia: **Proyecto Integrador** \
Docente: **M.T.I. Marco Antonio Ramírez Hernández** \
Periodo: *Mayo - Agosto 2026* \

## Comandos Básicos para Maquetado de la Documentación utilizando el estandar de Markdown (.md)
---

Markdown es el estándar utilizado por Git y GitHub, para estilizar (maquetar) la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.  

### 1. Encabezados o Títulos (HEADERS)

Paa poder realizar una buena documentación del proyecto debemos distribuir correctamente los contenidos, para poder delimitar o hacer énfasis (enfatizar), es decir resaltar las secciones más importantes, podermos utilizar lo siguiente: 

**EJEMPLOS**

# Encabezado de Nivel 1
## Encabezado de Nivel 2
### Encabezado de Nivel 3
#### Encabezado de Nivel 4
##### Encabezado de Nivel 5
###### Encabezado de Nivel 6
####### Encabezado de Nivel 7 -  *El estándar solo permite 6 niveles para títulos, a partir del séptimo serán presentado como texto plano (sin estilo)* 

### 2. Separadores (SEPARATORS)

Si se desea marcar una separación visual de los contenidos podemos utilizar una línea horizontal indicanto tres carácteres - continuos, en el maquetado

**EJEMPLO:**

#### Título de la sección
---
Texto después del separador

### 3. Párrafos (PARAGRAPHS)

Son utilizados para presentar grandes secciones de texto que describen detalladamente el contenido de las secciones de la documentación, detallan procesos, explican código o cotexto teórico. 

**EJEMPLO:**

Párrafo 1:  Este texto es del párrafo 1 este texto es del párrafo 1  párrafo 1 este texto es del párrafo 1 párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1.

Párrafo 2: Este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2 este texto es del párrafo 2este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2, el estándar de markdown distingue los párrafos con un doble salto de línea de texto, si no se desea alinear, es decir estará alineado a la izquierda por defecto.

En caso de que necesitemos alinear el párrafo a **izquierda**, **derecha**, **centrado** o **justificado**, deberemos utilizar una etiqueta ```<p>``` con la proipiedad align y la dirección deseada. 

<p align="left">Párrafo alineado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierdapárrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda.</p>

<p align="center"> Párrafo alienado al centro párrafo alieando al centro párrafo alieando al centro párrafo alieando al centro párrafo alieando al centro párrafo alieando al centropárrafo alieando al centropárrafo alieando al centropárrafo alieando al centro párrafo alieando al centro párrafo alieando al centropárrafo alieando al centropárrafo alieando al centro párrafo alieando al centro párrafo alieando al centro párrafo alieando al centropárrafo alieando al centropárrafo alieando al centro párrafo alieando al centropárrafo alieando al centro. </p>

<p align="right"> Párrafo alienado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha.

<p align="justify"> Párrafo justificado párrafo con texto justificado párrafo con texto justificado párrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificado párrafo con texto justificado párrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificado párrafo con texto justificado párrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificado párrafo con texto justificado párrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificado párrafo con texto justificado.


### 4. Enfatizado de Texto 

- Texto en Negritas: Para resaltar texto importante que no sea un título por questo incialmente están en negrita, deberemo encerrar el texto desdeado entre dobles asteríscos (**).

Ejemplo:   Este texto esta en **negrita**.

- Texto en Cursiva (Itálico): Para hacer referencia a texto utilzando el fomato inclinado o itálico bastará con encerrar el texto deseado entre dos asteríscos simples (*).

Ejemplo:  Este *texto* estará *inclinado*.

- Texto en Cursiva y Negita:  Para lograr esta estilización en la documentación basta con juntar ambas configuraciones , es decir encerramos el texto en un triple asterísco (***)

Ejemplo:   ***Este texto esta Negrito e Itálico.***

- Texto Tachado: En algunas ocaciones es necesario dar formato al texto con un efecto de como es incorrecto, generalmente esta idea se transmite por que el texto esta tachado, es decir con una línea que lo marca por la mitad. Para lograr este efecto tendremos que encerrar el texto entre una doble tílde de (~).

Ejemplo: Se dice haya no ~~haiga~~. 

- Texto Subrayado: En este tipo de formato el texto queda sobre una línea inferior para denotar su relevancia, este formato no tiene un versión rápida en el estándar MARKDOWN, pero dado su similiaridad a HTML podemos utilizar las etiquetas ``` <u> ``` y ``` </u> ```.

Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>.

- Texto en Superíndice:  En algunas ocaciones se requiere dar formato a fórmulas estadísticas que requiere potencias entre otras aplicaciones, podemos utilizar el tag de HTML ``` <sup> ``` y ``` </sup>``` para delimitar el formato.

Ejemplo: Para elevar x al cuadrado tendriamos lo siguiente  x<sup>2</sup>

- Texto en Subíndice:  En el caso de Química se utilizan subíndices para representar formulas, para ello podemos utilizar el formato de texto con la etiqueta HTML ``` <sub> ``` y ``` </sub>```.

Ejemplo: La formula del Agua es  H<sub>2</sub>O.


### 5. Listas

Cuando relizamos documentación utilizando el estándar de MARKDOWN, es común que tengamos que listar elementos, requisitos de hardware, requisitos de software o enumerar pasos de cómo el software debe ser instalado paso a paso, por eso debemos saber como crear listas de las cuales hay de 3 tipos :  **Ordenadas (Números)** , **Desordenadas (Viñetas)** y **Mixtas (Viñetas y Números)**.

1. Listas Ordenadas

Estas deberán estar enumeradas con un número seguido por un punto y un espacio en blaco para comenzar con el listado. 

1. PC 
2. Wifi
3. Modém
4. Smartphone
6. Smart TV
5. Tablet 

Para reiniciar el conteno se debe poner una línea de texto sin numeralia. 

2. Listas Desordenadas

Estas listas no llevan un número , sino una viñeta (simbolo), y suele listar elementos que no requieren un orden específico.

- Pan
- Leche
- Huevo
- Azucar

3. Listas Mixtas

Son aquellas que mezcla ambos elementos

- 3° A DSM
    1. Juan
    2. Pedro
    3. Alejandra
- 3° B DSM
    1. Romina
    2. Daniel
- 3° C DSM
    1. Yahir
    2. Liseth
    3. Jeovany
    4. Erick

### 6. Bloques de Código (CODE BLOCKS) o Citas (BLOCK QUOTES)

Estos estilos de texto se utilizan para llamar la atención del lector, en pasos que son importantes , realizar alguna reseña o  segmentar líneas de código que se deberán ingresar en una terminal de comandos o líneas de ejecución. 


- Cuadro de Citas (Block Quotes)
Son cajas estilizadas en colores grises por defecto con un margén más claro. 

Ejemplo:

Para listar las carpetas y archivos desde una terminal de comandos en el sistema operativo de Windows debemos usar el comando: 

> C:/dir

Después oprimimos la tecla *Enter*.

Tambien podemo usar texto multilínea

EJEMPLO:

Pasos para instalar MySQL
> - Descargar el archivo instalador desde la página oficial  www.mysql.com
> - Instalar el Servidor de Bases de Datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializar el serviro de bases de datos
> - Conectarnos a la base datos para verificar que se instaló correctamente.


- Bloques de código

