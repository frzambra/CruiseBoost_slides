---
title       : Muestreo asistido por imágenes satelitales
subtitle    : CruiseBoost para rodal y estrato
author      : Francisco Zambrano Bigiarini
job         : Representante Latinoamérica
logo: silviaTerra_logo.png
biglogo: silviaTerra_logo1.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax,  bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- .class #id

<!-- <style> -->
<!-- .title-slide { -->
<!--      background-image: url(./assets/img/background_title.jpg); -->
<!--    } -->
<!-- </style> -->

## SILVIATIERRA

- Startup Norteamericana creada el año 2009.

<iframe src="https://landsat.gsfc.nasa.gov/silviaterra-landsat-use-by-a-forestry-start-up/" width=1000 height=200 allowtransparency="true"> </iframe>

---

## SILVIATIERRA

- Esta ayudando a mejorar el manejo forestal en los Estados Unidos.
- Aumentando el retorno de la inversión.
- Equipo de emprendedores de la Universidad de Yale, USA.


## "Better data, better decisions"

---

## CruiseBoost -> parcelas + imágenes =

- 25% de ahorro para rodal
- 60% de ahorro para estrato
- alta calidad y resolución
- manten el protocolo normal de muestreo 
  - usa el grillado estandar
- bajo riesgo 

<div style='text-align: center;'>
    <img width='100%' src='./assets/img/3mosaicos.png' />
</div>

--- &twocol1

## CruiseBoost para rodal

### _Menor costo_ y _mayor precisión_ vs muestreo no asistido

*** {name: left}

--Muestreo no asistido--

- 22 parcelas:
  - Costo = 440$USD
  - Precisión = 65%

<div style='text-align: center;'>
    <img width='60%' src='./assets/img/muestreo_noasistido_submuestra.png' />
</div>    

*** {name: right}

--CruiseBoost--

- 14 parcelas + asistencia por imágenes:
  - Costo = 335$USD
  - Precisión = 90%

<div style='text-align: center;'>
    <img width='60%' src='./assets/img/muestreo_asistido_submuestra.png' />
</div>    

--- &slide1

## CruiseBoost para rodal

<div style='text-align: center;'>
    <img width='85%' src='./assets/img/muestreo_asistido_ejemplos.png' />
</div>    

--- &slide1

## CruiseBoost para rodal

La relación entre las mediciones realizadas en las parcelas y los valores del pixel
de la imágen permiten la estimación de APH, AB, especies y distribución de los diámetros, 
y por lo tanto listas jerarquicas de todas las areas cubiertas.

<div style='text-align: center;'>
    <img width='80%' src='./assets/img/explicacion_capas_info.png' />
</div>    

--- &slide1

## CruiseBoost para rodal

<div style='text-align: center;'>
    <img width='60%' src='./assets/img/ejemplo_area_basal_heatmap.png' />
</div>    

<div style='text-align: center;'>
    <img width='60%' src='./assets/img/ejemplo_area_basal_relative_cruise_mean_heatmap.png' />
</div>    

--- &slide1

## CruiseBoost para rodal

### Usando parcelas + imágenes:

- Permite ahorrar ~25% en el inventario mientras mantiene o mejora la precisión.
- Resulta en un inventario con un completo treelist, con detalle de _especies_ y _DAP_, y tabla de reporte por rodal que pueden ser resumidos y hacerlos crecer.
- Produce útiles heatmaps que entregan mas información para el personal en terreno.

---&slide2

## CruiseBoost para estrato

### Obtenga eficiencia a escala

- Paga por un muestreo a nivel de *estrato*, y obten información a nivel de rodal.

<div style='text-align: center;'>
    <img width='90%' src='./assets/img/estrato_rodal.png' />
</div>   

## Ahorro de ~60%+

---&slide2

## CruiseBoost para estrato

### Ejemplo de diseño de muestreo CruiseBoost

Las grillas de abajo representan rodaels en un diseño "estrato" de ejemplo con 24 rodales de A hasta la X.

<div style='text-align: center;'>
    <img width='70%' src='./assets/img/estrato_24_rodales.png' />
</div>   

Nota para biometricians: CruiseBoost es un muestreo imagen-asistido de dos etapas.

---&slide2

## CruiseBoost para estrato

### Etapa 1: Selección aleatoria de rodales

Se seleccionaron 8 rodales de forma aleatoria de un total de 24.

<div style='text-align: center;'>
    <img width='70%' src='./assets/img/selection_8_rodales_estrato.png' />
</div>   

---&slide2

## CruiseBoost para estrato

### Etapa 2: Grillas de parcelas en los rodales seleccionados

## Rodal B

<div style='text-align: center;'>
    <img width='70%' src='./assets/img/rodal_B_seleccionado.png' />
</div>   

--- &twocol2

## CruiseBoost para estrato

### Nivel de análisis de estrato

*** {name: left}

Estrato = $\sum{[A-X]}$  
(suma de todos los rodales)

- *Solo parcelas*: estimación no sesgada de la poblacion 
  - +/- 6% error de muestreo
- *Parcelas + imagenes*:estimación no sesgada de la poblacion 
  - +/- 3% error de muestreo

*** {name: right}

<div style='text-align: center;'>
    <img width='80%' src='./assets/img/estrato_24_rodales.png' />
</div>   

--- &twocol2

## CruiseBoost para estrato

### Nivel de análisis de rodales (rodales muestreados)


*** {name: left}

Muestreados = [B,E,H,I,M,P,T,W]

Para cada uno de los rodales:

- Solo parcelas: 
  - Pecisión = 70%
- Parcelas + imagenes
  - Pecisión = 90%

Heatmap de sub-rodal para especie, volumen

*** {name: right}

<div style='text-align: center;'>
    <img width='90%' src='./assets/img/selection_8_rodales_estrato.png' />
    <img width='90%' src='./assets/img/hetmap_su_rodal.png' />
</div>   

--- &twocol2


## CruiseBoost para estrato

### Nivel de análisis de rodales (rodales no muestreados)

No muestreados = [A,C,D,F,G,J,K,L,N,O,Q,R,S,U,V,X]

*** {name: left}

Para cada uno de esos rodales:

- Treelist y tabla-rodal.
- Precisión = 90%
- Sub-rodal heatmap para especie, volumen, etc.

*** {name: right}

<div style='text-align: center;'>
    <img width='90%' src='./assets/img/estrato_verde_celeste.png' />
</div>   

--- &twocol2

## CruiseBoost para estrato

### Economía

24 rodales | 389 há | Información nivel de rodal | 90% precision

*** {name: left}

*Solo parcelas*

Inputs:    

- 24 rodales muestreados con parcelas
- 20 parcelas por rodal
- $20 por parcela

Total:

= $ 9.600  

$24.7 / há

*** {name: right}

*Parcelas + imágenes*

Inputs:

- 8 rodales muestreados con parcelas
- 10 parcelas por rodal
- $20 por parcela

- $6.2/há por imagenes y análisis
Total:

= $ 4.012  

$10.3 / há

~60% reducción de costo

---

## CruiseBoost es:

- Mas barato que muestreo solo con parcelas a nivel de rodal
- Mas informativo que los diseño a nivel de estrato 
- Rapido, ideal para adquisiciones
- Preciso, estimaciones no sesgadas
- Alta resolución para operacion y planeamiento
- Sin riesgo

---

## CruiseBoost es ideal para:

- Adquisiciones / ventas
- Cierre de corona
  - Obten el nivel de detalle de rodal que necesita para decidir en la fecha de raleo
- Despues del raleo
  - Proporciona el precisio detalle a nivel de arbol que necesita para projectar futuras condiciones.
- Rodales naturales y mezclados
  - Información específica de especies.
  - Mejoras significativas para rodales con gran variación

---

## Ejemplo (Here we can show results)

<iframe src="./assets/widgets/chilean_forest.html" width=100% height=100% allowtransparency="true"> </iframe>

--- &vcenter


## ¿Preguntas?

<div style='text-align: center;'>
    <img width='90%' src='./assets/img/background_final.png' />
</div>   

Si piensas en alguna luego, escribeme

