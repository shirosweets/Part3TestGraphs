# Part3TestGraphs

## Ejemplos de Grafos donde deben correr el main de la parte 3

En la parte 3 les pedimos que hagan un main y dijimos:

"Deben testear extensivamente sus funciones, con este y otros mains que hagan, pero al menos
con este. Deben mandar algunos archivos de corrida de su main con algunos grafos y algunos
parametros. Especificaremos esos grafos y parámetros en la página del Aula Virtual."

Aca especificamos cuales grafos y con cuales parametros tienen que correrlos.

Recordemos que el main tiene 6 parametros a,b,c,d,e,f.

El "f" es una semilla de aleatoriedad, ese parametro no lo especificamos, queda a libertad suya.

## Octo

> Grafo "Octo"

Háganlos dos veces:

1) Parametros a,b,c,d,e: 8 5 47 7 3

2) Parametros a,b,c,d,e: 16 0 82 4 3

Con esos parametros y ese grafo no deberían demorar más de unos minutos.

(en mi maquina yo demoro 1m16.975s y 1m16.435s, pero sería razonable que demoren unos 5 minutos. De todos modos si demoran más, y el problema está con su *parte 1*, no hay problema porque como ya dije varias veces, voy a testear con mi parte 1 y no la suya. Si demoran más y el problema es Greedy o los reordenamientos, es otra historia).

## Gf.....

> Grafo Gf12345....

Parametros a,b,c,d,e: 8 5 47 7 3

Tanto en este como en el anterior deberían ver como bajan notablemente el número de colores con las corridas, hasta que eventualmente se estabiliza.

Este es más complicado y puede ser que demoren 15 minutos o más. (yo demoro con el main que dijimos y esos parametros, 3m24.457s).

## large and complex

Mismos parametros que el anterior: a,b,c,d,e: 8 5 47 7 3

Debería demorar más o menos lo mismo que el anterior.

La diferencia es que el anterior se colorea con más de 500 colores y este puede llegarse a 33 colores.

## queen 13

Grafo queen 13

Parametros: a,b,c,d,e: 16 0 820 4 3

Los anteriores corrían unos 1000 Greedys más reordenes, estos son más de 9.000.

Pero el grafo es muy chico y deberían demorar menos de un segundo, a lo sumo algunos segundos.

## R1999

Grafo con el cual en muchos años anteriores algunos grupos tenían problemas con Greedy que no terminaba más.

El problema solía ser a la hora de pasar de colorear un vertice al siguiente y como se reinicializan ciertos parametros internos que algunos grupos usan y que no lo hacen bien.

Parametros: 4 4 4 4 4

con esos parametros son un poco más de 50 Greedys, no deberían demorar mucho aun con este grafo grande. Yo demoro 15 segundos.

Deberían poder hacer 1000 Greedys en no más de 15 o 20 minutos con este grafo, así que 50 no debería serles problema. Si demoran mucho, revisen su Greedy.

Con casi cualquier orden debería darles un coloreo con 7 colores.
## BxB1100

> (BxB1100_999_54_2017.tar.gz)

También Parametros 4 4 4 4 4

Este grafo tiene una estructura complicada pero la cantidad de colores en gral. oscila entre 4 y 5, aunque hay un orden que requiere de más de 2000 colores, pero sería raro que lo encuentren.

1000 Greedys les podría demorar entre 15 minutos a 30 minutos, y en gral. debería demorarles algo menos  del doble que el anterior.

Igual para esos parametros no deberían demorar más de un minuto, pero algunos puede ser que demoren más por ineficiencias en la parte 1. (yo demoro menos de medio minuto).

## Q53

> Queen 53

El número cromático es 53 pero nunca he podido bajarle la cantidad de colores por debajo de 60, en general llego a 63 o algo así.

Parametros: 16 0 82 4 3

Deberían demorar solo unos segundos con esos parametros.

## BQStarMM

Parametros 16 0 82 4 3

No deberían demorar más que unos minutos.

## Harkon

Parametros:  8 1 82 4 3

Este grafo tiene 6160 vertices, 18092520 lados y Delta=6057.

Se ve muy bonito como bajan los colores de posiblemente más de 600 a un poco más de 200.

Pueden ser que demoren entre 5 minutos y media hora dependiendo como hayan implementado las cosas. (yo demoro 5m19.103s)
