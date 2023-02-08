```python
Ciencia de Datos en Python
Investigación 1: Git, GitHub y Markdown
Pablo Jirón (22007786)
Febrero 08, 2023
```


```python
Git
Git es un sistema de control de versiones distribuido gratuito y de código abierto diseñado para manejar todo, desde proyectos pequeños hasta proyectos muy grandes, con rapidez y eficiencia.
Git es fácil de aprender y ocupa poco espacio con un rendimiento ultrarrápido. Supera a las herramientas de SCM como Subversion, CVS, Perforce y ClearCase con características como sucursales locales económicas, áreas de preparación convenientes y múltiples flujos de trabajo.
```


```python
Las características más importantes de Git son:
1)	Ramificación y Fusión:
Esta es la característica de Git que realmente lo diferencia de casi todos los demás SCM, su modelo de ramificación.
Git permite y alienta a tener varias sucursales locales que pueden ser completamente independientes entre sí. La creación, fusión y eliminación de esas líneas de desarrollo lleva unos segundos.
En particular, cuando envía a un repositorio remoto, no tiene que enviar todas sus sucursales. Puede elegir compartir solo una de sus sucursales, algunas de ellas o todas. Esto tiende a liberar a las personas para probar nuevas ideas sin preocuparse por tener que planificar cómo y cuándo van a fusionarlas o compartirlas con otros.
Hay formas de lograr algo de esto con otros sistemas, pero el trabajo involucrado es mucho más difícil y propenso a errores. Git hace que este proceso sea increíblemente fácil y cambia la forma en que la mayoría de los desarrolladores trabajan cuando lo aprenden.

```


```python
2)	Pequeño y Rápido:
Git es rápido. Con Git, casi todas las operaciones se realizan localmente, lo que brinda una gran ventaja de velocidad sobre los sistemas centralizados que constantemente tienen que comunicarse con un servidor en alguna parte.
Git fue creado para funcionar en el kernel de Linux, lo que significa que ha tenido que manejar de manera efectiva grandes repositorios desde el primer día. Git está escrito en C, lo que reduce la sobrecarga de los tiempos de ejecución asociados con los lenguajes de nivel superior. La velocidad y el rendimiento han sido un objetivo de diseño principal de Git desde el principio.

```


```python
3)	Repartido:
Una de las mejores características de cualquier SCM distribuido, incluido Git, es que está distribuido. Esto significa que en lugar de hacer una “verificación” de la punta actual del código fuente, hace un “clon” de todo el repositorio.

```


```python
4)	Garantía de datos:
El modelo de datos que utiliza Git garantiza la integridad criptográfica de cada parte del proyecto. Cada archivo y confirmación se suma y se recupera mediante su suma de verificación cuando se vuelve a desproteger. Es imposible obtener algo de Git que no sean los bits exactos que se ingresaron.
También es imposible cambiar cualquier archivo, fecha, mensaje de confirmación o cualquier otro dato en un repositorio de Git sin cambiar los ID de todo lo que sigue. Esto significa que si tiene un ID de compromiso, puede estar seguro no solo de que su proyecto es exactamente igual que cuando se comprometió, sino que no se cambió nada en su historial.
La mayoría de los sistemas de control de versiones centralizados no proporcionan tal integridad por defecto.

```


```python
5)	Área de ensayo:
A diferencia de los otros sistemas, Git tiene algo llamado “área de ensayo”, “preparación" o "índice". Esta es un área intermedia donde se pueden formatear y revisar las confirmaciones antes de completar la confirmación.
Una cosa que diferencia a Git de otras herramientas es que es posible almacenar rápidamente algunos de sus archivos y enviarlos sin enviar todos los demás archivos modificados en su directorio de trabajo o tener que enumerarlos en la línea de comandos durante la confirmación.

```


```python
6)	Gratis y de código abierto:
Git se publica bajo la Licencia Pública General GNU versión 2.0, que es una licencia de código abierto. El proyecto Git eligió usar GPLv2 para garantizar su libertad para compartir y cambiar el software libre, para asegurarse de que el software sea gratuito para todos sus usuarios.
Sin embargo, se restringe el uso del término "Git" y los logotipos para evitar confusiones.

```


```python
7)	Marca Comercial:
El Proyecto Git es un proyecto miembro de Software Freedom Conservancy (conocido solo como “Conservancy”). Conservancy tiene derechos sobre las Marcas en nombre del Proyecto Git de acuerdo con su misión caritativa sin fines de lucro.
Conservancy ha adoptado esta Política para proteger las Marcas (como se define a continuación) y para asegurarse de que la identidad del software Git y su naturaleza de código abierto y gratuito sea clara para todos. Al usar esta Política, el Proyecto Git puede difundir el uso del software Git mientras se asegura de que las Marcas estén protegidas de manera consistente con la ley de marcas registradas de EE. UU. (Registro de EE. UU. 4680534). Esta Política está redactada para permitir todo uso claro y apropiado de las Marcas y desaprueba el uso de las Marcas de manera que pueda confundir a los usuarios sobre el origen del software, o que implique una asociación inexistente con el Proyecto Git. Al adherirse a esta Política, ayuda a promover entre el público la libertad de usar y desarrollar el software Git.

```


```python
GitHub
GitHub es una plataforma de desarrollo colaborativo para alojar proyectos utilizando el sistema de control de versiones Git. Se utiliza principalmente para la creación de código fuente de programas de computadora. El software que opera GitHub fue escrito en Ruby on Rails. 
El 4 de junio de 2018 Microsoft compró GitHub por la cantidad de 7,500 millones de dólares. Desde enero de 2010, GitHub opera bajo el nombre de GitHub, Inc. (anteriormente era conocida como Logical Awesome LLC). El código de los proyectos alojados en GitHub se almacena generalmente de forma pública. GitHub continúa siendo la plataforma más importante de colaboración para proyectos de código abierto.
Los repositorios son, como su propio nombre indica, lugares virtuales alojados en la nube en donde los usuarios pueden almacenar cualquier tipo de archivo. Suelen usarse para guardar archivos de texto que representan código en distintos lenguajes de programación, los cuales a su vez conforman un programa o aplicación. Este es el servicio principal que ofrece GitHub: repositorios en donde los usuarios pueden almacenar el código de sus aplicaciones, ya sea de forma pública, privada o a través de una organización.

```


```python
Markdown
Markdown es un lenguaje de marcado sencillo que sirve para agregar formato, vínculos e imágenes con facilidad al texto simple. Los comandos de Markdown son admitidos por el editor de tickets de manera automática. Se pueden ingresar comandos de Markdown para formatear el contenido o, si se prefiere, se puede usar la barra de herramientas de formato para agregar contenido enriquecido.

```


```python
Ejemplos de la sintaxis de Markdown:
FORMATO	ESCRITURA	MUESTRA
Negrita	Así se escribe el texto en **negrita**	negrita
Cursiva	Así se escribe el texto en *cursiva*	cursiva
Listas con viñetas	* Viñeta uno (no olvide el espacio después del asterisco)
* Viñeta dos (debe escribir un salto de línea antes y después de la lista).

También se puede comenzar con un guión (-) seguido de un espacio para crear una lista con viñetas.	•	Viñeta uno
•	Viñeta dos


-	Viñeta uno
-	Viñeta dos
Listas numeradas	1. Paso uno
2. Paso dos	1.	Paso uno
2.	Paso dos
Listas anidadas	* Primer nivel de la lista.
* Para el segundo nivel, agregue dos espacios antes del asterisco o número.	•	Primer nivel
o	Segundo nivel
Encabezados	# Encabezado nivel uno (con un espacio después de #)
# # Encabezado nivel dos
# # # Encabezado nivel tres	Encabezado nivel uno 
Encabezado nivel dos
Encabezado nivel tres
Código en línea	Este es un ejemplo de "código en línea".	Código en línea
Bloques de código	´´´ Bloque de código ´´´	Bloque de código
Vínculos	[Texto de vínculo](http://www.sampleurl.com)	Texto de vínculo
Línea separación	---
Escribir salto de línea antes y después de los guiones.	


```
