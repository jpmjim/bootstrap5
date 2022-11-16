# bootstrap5
Curso de Bootstrap desde Cero

## Proyecto
  Desarrollo de un portafolio web que sera construido con HTML CSS y BOOTSTRAP.

  Dentro de la barrade navegación contendra 4 opciones que son las siguientes: "sobre mí, Proyectos, Testimonios y Contacto" los cuales van hacer enlaces el cual nos desplazaran a la sección a cada de uno de los espacios.

  La página web va ser responsive para poder adaptarse a cualquier dispositivo.

## Herramientas
  - Instalación de nuestro editor de código [**Visual Studio Code**](https://code.visualstudio.com/).
  - La extensión de [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) nos permite actulizar los cambios directamente en el navegador.

## Herramientas de desarrollo de Chrome
  Es muy util para poder trabajar con páginas web responsives adaptables a distintos tamaños, nos ayudara para poder trabajar con estructura HTML Y CSS de la página, una consola interactiva.

  Para poder utilizar las herramientas con un solo click derecho seleccionando inspect o presionando la tecla <kbd>F12</kbd>, donde nos mostrara un panel al lado derecho. Donde se podra experimentar cambios al código sin alterarlo directamente al archivo simplemente refrescando la página y no se habra realizado ningun cambio.

  Dentro del panel incluye ña opciones de poder probar la página dentro de distintos dispositivos como desktop, table, numerosos tamaños de celulares, como se poder desarrollar de manera responsive.

## Introducción a Bootstrap
  Es un framework CSS para desarrollar sitios adaptables, una forma de aplicar estilo css mucho mas facil.

  - Framework es una estructura bsae que puedes usar para desarrollar tu aplicación o sitio web de forma más rápida y eficiente.

  - El framework CSS es un conjunto de clases que nos permite personalizar el estilo de los elementos de HTML dentro del sitio web.

  - Responsivo o responsive es que se adaota a distintos  dispositivos en base a su tamaño y orientación en desarrollo web.

## Tres pilares de Bootstrap
  Tres de las caracteristicas principales que nos ofrece bootstrap son 
  
  - Grid como se van estructura los elementos de la página web y como se van adaptar al tamaño del dispositivo.
  - Componentes son elementos html reutilizables que vienen con un estilo predeterminado.
  - Iconos que vienen dentro del framework.

## La grid de Bootstrap
  Grid o cuadrícula es como queremos que se presenten que espcacio deben ocupar los elementos de la página.

  Conjunto de contenedores, filas y columnas que definen cómo se va a presentar y a alinar el contenido.

  ![](https://images04.nicepage.com/feature/447593/es/80-grid-layouts.jpg)

  Dentro de la cuadricula nos permite trabajar con filas y columnas, cada fila pude estar dividida en 12 columnas, cuantas columnas puede ocupar cada elemento.

  Clases especificas para la grid que podemos asignarles a los elementos de html:

  ![Imgur](https://i.imgur.com/catK4rL.png) 

  - **Row** cuando utilizamos la clase decimos que ese elemento html se va copnvertir en una fila.
  ![Imgur](https://i.imgur.com/ve1lNNC.png)

  - Para especificar la cantidad de columnas debemos utilizar la clase de **col-**, dentro de la clases se puede determinar tambien el tamaño de las dimensiones ***xs, sm, md, lg, xl y xxl*** los cuales representan el ancho de la ventana donde se ve la página web o llamado la viweport.
  ![Imgur](https://i.imgur.com/deYA28B.png)

## Breakpoint
  Dimensión ancho a partir de la cual podemos cambiar el estilo o la estructura de la página web. Es un punto de quiebre el cual hace que el estilo se actulice o cambie a partir de una dimension.

  ![Imgur](https://i.imgur.com/5OUnxuZ.png)

## Estructura de la grid
  - Un contenedor puede contener filas y cada fila contiene 12 columnas.
    ![Imgur](https://i.imgur.com/XVnLM30.png)

    ![Imgur](https://i.imgur.com/LrzvUTn.png)


## Contenedores en Bootstrap

  - Un contenedor es un elemento html que contendra en su interior toda la estructura de filas y columnas o elementos html que podamos incluir

  - Hay dos clases especificas dentro de bootstrap para usar un contenedor: **.container y .container-fluid**

    - ***.container*** crear un contenedor responsivo con un ancho máximo fijo que depende del tamaño del dispositivo.

    - ***.container-fluid*** crea un contenedor respondivo que cubre 100% del ancho de la ventana.

## Contenedores

  ![Imgur](https://i.imgur.com/BrbbjNP.png)

  Contenedores responsivos crea un contenedor responsivo que cubre 100% del ancho de la ventana hasta que llega  a las dimensiones de ese breakpoint.

## Estructura de la grid
  - Los elementos de una fila pueden ocupar varias columnas.

  ![Imgur](https://i.imgur.com/kGTOUX3.png)

  - Podemos generar cualquier combinacion de estructura elemento.

  ![Imgur](https://i.imgur.com/pRFevDo.png)

  - Las columnas de los elementos de una fila deben sumar 12 para que esten ubicados en la misma línea.

  - Si suman más de 12, las columnas adicionales se colocan en una línea nueva.
