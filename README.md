# Analisis-Tienda-de-Videojuegos
Análisis de datos de una Tienda Multinacional de Videojuegos

---
CONTEXTUALIZACIÓN

Proyecto n°6/BootCamp Tripleten Latam
El trabajo realizado consistió en preparar una extensa base de datos para posteriormente realizar un analisis de los juegos más y menos populares en 3 regiones distintas (Japón, Europa y Norteamérica), el propósito final era preparar una campaña publicitaria para el año siguiente, por lo que dentro del análsis se respondieron preguntas como: 
 - Cuales son los juegos más y menos populares
 - Cuales son las plataformas más vendidas
 - Cuales son los géneros de videojuegos mas populares por región
 - Como se ven reflejadas las ventas segun las valoraciones de los juegos
 - Pruebas de hipótesis
 - Entre otras.

---
ALGUNAS CONCLUSIONES

# CONCLUSIONES GENERALES DEL PROYECTO 
#### Parte 1: Conclusiones generales de las ventas

* A través de la visualización de la cantidad de juegos lanzados por año, se tiene registro desde el año 1980 hasta 2016, donde 1980 es el año con menos lanzamientos de juegos, registrados solo 9. Por otro lado, los años 2008 y 2009 fueron aquellos con más juegos lanzados, con una cantidad de 1427 y 1426 respectivamente, siguiendoles el año 2010 con 1255. 
* El año 2016 (a la fecha de obtenida esta base de datos), registra solo 502 videojuegos lanzados. 
* Existen 269 juegos sin registro de su año de lanzamiento, de un total de 16715. 

Las plataformas con mayores ventas totales registradas en millones de dolares estadounidenses a la fecha en la base de datos (años 1980-2016), han sido
* PS2 = 1255.77
* X360 = 971.42
* PS3 = 939.65
* Wii = 907.51
* DS = 806.12
* PS = 730.86
* GBA = 317.85

Seguidas de PS4 con 314.14 millones de dólares estadounidenses. Cabe destacar que estas ventas totales incluyen solamente las regiones de Norteamérica, Europa y Japón.

Las plataformas con menos recaudación total (en millones de dólares estadounidenses), por ventas han sido:
* PCFX = 0.03
* GG =	0.04
* 3DO = 0.10
* TG16 = 0.16
* WS = 1.42
* NG = 1.44
* SCD = 1.86

---

### Parte 2: Conclusiones para el modelo de ventas 2017

* Existen, a la fecha de obtenida esta base de datos, 9 plataformas que al año 2016 siguen activas en el mercado (registran ventas). Se puede observar que no existe un patrón dependiente del año de lanzamiento de las plataformas que determine si estas son exitosas o no, ya que se ve una gran variabilidad en este aspecto. Desde 3 años hasta décadas de permanencia en el mercado. Las plataformas activas son: 3DS, PC, PS3, PS4, PSV, Wii, WiiU, X360, XOne. De estas, las que se reducen hacia 2016 son 3DS, PS3, Wii, WiiU, PSV, X360. La plataforma que hacia 2016 presentan un crecimiento es PS4.
* En definitiva, las plataformas potencialmente rentables hacia 2017 son PS4, XOne y PC. 
* Se observó que desde 2012 hacia 2016 el promedio en ventans de estas tres plataformas fue casi el mismo, exceptuando algunos valores atípicos, sobre todo de la plataforma PS4. 
* En estudios de dispersion con datos desde 2012 a 2016 se determina que no existe una correlación entre el puntaje otorgado por los usuarios o la crítica profesional hacia las plataformas y las ventas que estas consiguen. Al menos para PS4 o XOne. 
* Dentro del estudio de perfil de usuario de las tres regiones principales de ventas de videojuegos se concluye que: 
1) Las plataformas más populares en Norteamerica corresponden a: PS4, XOne, 3DS, WiiU y PC, dentro de las cuales los usuarios prefieren los géneros de Shooter, Action, Sports, Role-Playing y Fighting.

2) Las plataformas más populares en Europa son las mismas que en Nortreamérica, solo que el orden preferencial es distinto, en primer lugar está PS4 y XOne, pero luego se prefiere PC, 3DS y WiiU. Con respecto a los géneros de videojuegos, Europa también se inclina primeramente por juegos de Shooter, pero luego el género más consumido es Sports (a diferencia de Norteamérica), seguido de Action, Role-Playing y Racing.  

3) Las plataformas más populares en Japón encabezan la lista con 3DS, luego PS4, PSV, PS3 y WiiU. Los géneros más consumidos por los japoneses son: Action, Role-Playing, Adventure, Shooter y Misc.

4) Además, se logró identificar que al menos en Japón si existe una relación de las ventas con la clasificación ESRB de los juegos. En Japón se consume mucho más  juegos con clasificación 'E', que juegos con clasificacion 'M', al contrario que Norteamérica o Europa. 

* Finalmente, para las pruebas estadiísticas se concluye que NO podemos rechazar la hipótesis nula de que las calificaciones promedio para las plataformas XOne y PC son las mismas y DEBEMOS rechazar la hipótesis nula de que las calificaciones promedio para las plataformas XOne y PC son las mismas.  Asi que se acepta la hipótesis alternativa, las calificaciones de usuarios para los géneros de Acción y Deportes son distintas. 
