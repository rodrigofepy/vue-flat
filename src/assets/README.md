```
<img src="https://github.com/wilmercampagna/vue-flat/blob/master/src/assets/VueFlat.jpg">

```
# Clases vue-flat

## Estructura

Los estilos se definirán en archivos aislados dentro del directorio ```/src/assets/``` allí encontratarán el archivo ```main.scss``` en el cual se realizará el llamado a todas las utilidades, variables, mixins y funciones creadas.

```
<!-- /src/assets/main.scss -->

@import './scss/variables'

```

El desarrollo de funciones, mixins y demás deberá hacerse dentro del directorio ```/src/assets/scss/_file.scss```

Todos lo archivos creados deberán tener el prefijo ```"_"``` y ser importados dentro del archivo principal ```main.scss``` 


### Referencias sobre como desarrollar estilos con Sass
Ver [Documentación de Sass](https://sass-lang.com/guide).

## Colores

A continuación se muestra el listado de variables con los colores definidos para el proyecto.

``` 
// <----------- Sistema de Colores ----------->

// <----------- Escala de grises ----------->

$white:    #fff;
$gray-100: #f8f9fa;
$gray-200: #e9ecef;
$gray-300: #dee2e6;
$gray-400: #ced4da;
$gray-500: #adb5bd;
$gray-600: #6c757d;
$gray-700: #495057;
$gray-800: #343a40;
$gray-900: #212529;
$black:    #000;

// <----------- Colores ----------->

$primary:         #2eeef4;
$primary-light:   #4bf1f7;
$primary-lighter: #87f1f4;
$primary-dark:    #3fbed6;
$primary-darker:  #287288;
$warning:         #ffff00;
$danger:          #fe0065;
$success:         #01e172;
$link:            #0408fe;
$info:            #0267fc;
$violet:          #e325e9;
$violet-light:    #f751d3;
$violet-dark:     #ad318c;
$purple:          #8088be;
$purple-light:    #9ea4cc;
$purple-dark:     #47508A;
$wine:            #b6143b;
$wine-light:      #c21b40;
$wine-dark:       #911230;
$orange:          #ff1919;
$orange-light:    #ff592b;
$orange-dark:     #ee3c19;
$blue:            #007bff;
$indigo:          #6610f2;
$pink:            #e83e8c;
$red:             #dc3545;
$yellow:          #ffc107;
$green:           #28a745;
$teal:            #20c997;
$cyan:            #17a2b8;
$space:           #233c5d;
$space-light:     #287288;
$space-dark:      #222243;

``` 
