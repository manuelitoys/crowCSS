## Framework CSS

Un Framework con los estilos básicos y algunas animaciones

### CDN

`<link rel="stylesheet" href="https://manuelitoys.github.io/frameworkCSS/frameworkCSS.css">`

### Animations

- animate-fadeOut
- animate-fadeIn
- animate-fadeInUp
- animate-fadeInDown
- animate-fadeInLeft
- animate-fadeInRight
- animate-shakeX
- animate-shakeY
- animate-bounce
- animate-bounceIn
- animate-flip
- animate-flipInX
- animate-flipInY
- animate-lightSpeed
- animate-rotateIn
- animate-rotateInDownLeft
- animate-hinge
- animate-zoomIn
- animate-zoomInDown
- animate-zoomInLeft
- animate-zoomInRight
- animate-zoomInUp
- animate-zoomOut
- animate-zoomOutDown
- animate-zoomOutLeft
- animate-zoomOutRight
- animate-zoomOutUp
- animate-slideInLeft
- animate-slideInRight
- animate-slideInUp
- animate-slideInDown
- animate-slideOutLeft
- animate-slideOutRight
- animate-slideOutUp
- animate-slideOutDown

### Background

p = position

- bg-transparent
- bg-cover
- bg-contain
- bg-repeat
- bg-no-repeat
- bg-repeat-x
- bg-repeat-y
- bg-p-center
- bg-p-top
- bg-p-bottom
- bg-p-left
- bg-p-right
- bg-p-top-left
- bg-p-top-right
- bg-p-bottom-left
- bg-p-bottom-right
- bg-p-center-left
- bg-p-center-right
- bg-p-top-center
- bg-p-bottom-center
- bg-p-left-center
- bg-p-right-center

### Blend

- blend-normal
- blend-multiply
- blend-screen
- blend-overlay
- blend-darken
- blend-lighten
- blend-difference
- blend-exclusion
- blend-saturation
- blend-luminosity

### Border

- b-solid
- b-dashed
- b-dotted
- b-double
- b-circle = "border-radius: 50%"
- b-**xx** (Desde 0 a 10, reemplazar **xx**) = border-width
- b-radius-**xx** (Desde 0 a 10, reemplazar **xx**)

### Centrar elemento

- mx-auto

### Colors

Los colores solo funcionan combinandolos con los prefijos de **text** o **bg** (text-**{color}** o bg-**{color}**)

- red
- green
- blue
- yellow
- orange
- purple
- pink
- white
- black
- gray

### Container

Todos los container van centrados

- container = Emplea el 100% con un padding interno de 20px izquierda y derecha
- container-1440
- container-1280
- container-1024
- container-960
- container-800
- container-768
- container-640
- container-480
- container-320

### Display

- d-flex
- d-inline-flex
- d-inline
- d-block
- d-none
- d-table
- d-table-row
- d-table-cell
- d-grid

### Float

- float-left
- float-right
- float-none

### Grid
1. jc = justify-content
2. ai = align-items

- row
  - col
- jc-center
- jc-end
- jc-space-between
- jc-space-around
- jc-start
- ai-center
- ai-end
- ai-space-between
- ai-space-around
- ai-start
- ai-stretch

### Margin
Desde 0 hasta 250px con la sintaxis:

- m-**xx** = margin + número
- mt-**xx** = margin-top + número
- ms-**xx** = margin-left + número
- me-**xx** = margin-right + número
- mb-**xx** = margin-bottom + número
- NOTA: Reemplazar **xx** por la cantidad de pixeles (max: 250)

### Padding
Desde 0 hasta 250px con la sintaxis:

- p-**xx** = padding + número
- pt-**xx** = padding-top + número
- ps-**xx** = padding-left + número
- pe-**xx** = padding-right + número
- pb-**xx** = padding-bottom + número
- NOTA: Reemplazar **xx** por la cantidad de pixeles (max: 250)

### Overflow

- over-hidden
- over-visible
- over-scroll
- over-auto
- over-inherit
- over-unset
- over-initial

### Position

- p-absolute
- p-relative
- p-fixed
- p-static
- p-sticky
- p-initial
- p-inherit
- p-unset
- p-center

### Text

- text-center
- text-left
- text-right
- text-justify
- text-nowrap
- text-wrap
- text-capitalize
- text-uppercase
- text-lowercase
- text-underline
- text-overline
- text-line-through
- text-thickness (se combina con **text-underline**, sirve para hacer la linea mas delgada)
- text-d-offset-**xx** (se combina con **text-underline**, sirve para dar distancia a la linea del texto, va desde 1 a 10)
- text-none = "text-decoration: none"
- text-ellipsis-**xx** (va desde 1 hasta 10, reemplazar **xx** por el numero) = Sirve para acortar texto a la cantidad de lineas deseadas con 3 puntos suspensivos (...)

