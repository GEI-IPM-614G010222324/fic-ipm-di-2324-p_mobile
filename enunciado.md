# Curso 23/24. Práctica 2. Interfaces gráficas para aplicaciones de dispositivos móviles

## Welcome :wave:

- **Who is this for**: Grupos de prácticas de la asignatura _IPM_.

- **What you'll learn**: Implementación de interfaces gráficas con un
  paradigma quasi-declarativo, diseño e implementación de interfaces
  adaptativas, patrones arquitectónicos para el manejo del estado con
  interfaces gráficas, concurrencia con funciones asíncronas,
  _software testing_ a traves de la interface gráfica.

- **What you'll build**: Construireis una aplicación para dispositivos
  móviles.

- **Prerequisites**: Asumimos que os resultan familiares el lenguaje
  de programación _dart_ y la librería _flutter_.

- **How long**: Este assigment está formado por tres pasos o
  _tareas_. La duración estimada de cada tarea es de una semana
  lectiva.


La aplicación a desarrollar es una aplicación para la conversión de
divisas:

  - La usuaria puede introducir una cantidad en una determina moneda,
    y la aplicación le ofrecerá su contravalor en otra moneda distinta.
	
  - La usuaria puede seleccionar una o varias monedas _de destino_
    para la conversión.
	
  - La conversión se realizará utilizando un servicio como
    [https://free.currencyconverterapi.com/](currencyconverterapi.com/).


<details id=1>
<summary><h2>Tarea 1: Diseño de la interface</h2></summary>

### :wrench: Esta tarea tiene las siguientes partes:

  1. Identifica y documenta los casos de uso relevantes para las
     potenciales usuarias de la aplicación.
  
  2. Realizar un diseño de la interface de usuaria de la aplicación y
     añadir el diseño a este repositorio en un fichero _PDF_ con el
     nombre `diseño-iu.pdf`. El diseño tiene que ajustarse a las
     siguientes pautas:
	 
     - Al menos debe haber un diseño distinto para teléfonos móviles y
       otro para tablets.
	   
     - El diseño debe adaptarse a la configuración del dispositivo.
	 
     - El diseño tiene que incluir los elementos necesarios para la
       gestión de errores, proporcionar la retroalimentación necesaria
       a la usuaria durante las operaciones de E/S, ...
	 
  2. Seleccionar un patrón arquitectónico para gestionar el estado de
     la aplicación de manera que el componente de la _vista_ sea
     independiente del _estado/modelo_. El patrón debe ser adecuado
     para su aplicación con _flutter_.
	 
  3. Realizar un diseño software siguiendo el patrón seleccionado.
  
	  - El diseño tiene que cubir los casos de uso de la aplicación.
	  
	  - El diseño se realiza usando el lenguaje _UML_ y debe incluir
        diagramas tanto para la parte estática como para la dinámica.
		
	  - La documentación del diseño se incorpora al fichero
        `diseño_sw.md` de este repositorio. El formato del fichero es
        la versión de _markdown_ [Github Flavored
        Markdown](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). Los
        diagramas UML se integran directamente en el fichero markdow
        usando
        [_Mermaid_](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)
		
  4. Implementar la aplicación siguiendo el diseño de la interface y
     el diseño software creados anteriormente.
	 
	   - El lenguaje de programación es python.
	   
	   - La librería gráfica es GTK, preferiblemente versión 4.
	   
	   - La estructura de módulos debe facilitar en lo posible el
         seguimiento del diseño sw. Se recomienda que, al menos, los
         componentes _vista_ y _estado/modelo_ esten en módulos o
         paquetes separados.
	   

### :books: Objetivos de aprendizaje:

  - Diseño adaptativo.
  
  - Patrones arquitectónicos en IGUs.
  
</details>


<details id=2>
<summary><h2>Tarea 2: Implementación de la aplicación</h2></summary>

### :wrench: Esta tarea tiene las siguientes partes:

  1. Implementar la aplicación diseñada en la tarea anterior.
  
     - La implementación debe realizarse usando _flutter_.

> :warning: Es muy importante capturar todo tipo de errores, en
> especial los relacionados con las operaciones de E/S e informar a la
> usuaria en todo momento.

> :warning: Actualmente flutter soporta múltiples plataformas: linux,
> web, android, ios, etc. Pero la práctica consiste en el desarrollo
> de una aplicación para dispositivos móviles. Tenéis que cercioraros
> de que la aplicación efectivamente funciona como se espera en
> android o/y ios. La defensa de la práctica también se realizará
> ejecutando la aplicación en alguna de dichas plataformas.

> :warning: El desarrollo software es iterativo. Durante esta tarea
> pueden ser necesarios cambios tanto en el diseño sw como en el
> diseño de la interface. Es importante actualizar los documentos de
> diseño afectados. También es importante que la modificación de los
> diseños se incluyan junto con el código relacionado en el mismo
> _commit_.


### :books: Objetivos de aprendizaje:

  - Uso de librerías para construir IGUs.
  
  - Progamación dirigida por eventos

  - Uso de la concurrencia con funciones asíncronas.
  
  - Gestión de errores en la E/S.
  
</details>



<details id=3>
<summary><h2>Tarea 3: Test end2end</h2></summary>

### :wrench: Esta tarea tiene las siguientes partes:

  1. Siguiendo la documentación de diseño, implementar tests _end to
     _end_ para los distintos caso de uso de la aplicación.
	 
	 - Los tests deben cubrir los errores de E/S y los errores de la
       usuaria.
	 
	 
### :books: Objetivos de aprendizaje:

  - Tests end to end a través de la interface gráfica.

</details>


<details id=X>
<summary><h2>Finish</h2></summary>

_Congratulations friend, you've completed this assignment!_

Una vez terminada la práctica no olvideis revisar el contenido del
repositorio en Github y comprobar su correcto funcionamiento antes de
realizar la defensa.

</details>

