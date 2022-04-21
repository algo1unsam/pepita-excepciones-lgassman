# Pepita (parte 2)

Este ejercicio extiende la versión inicial de pepita para que les estudiantes agreguen
sus primeras líneas en wollok luego de la explicación del docente

## Ejercicio 1: Pepón

Agregar a Pepón: Pepón es otra ave que puede comer el alpiste y la manzana y sigue las siguientes reglas:

- La energía inicial de pepón es 30.
- Sabe decir su energía. 
- Cuando come, solo puede aprovechar la mitad de la energía que aporta el alimento
- Cuando vuela gasta 20 fijos más 2 joules por km, 

Ejemplos:
- si tiene 30 de energía y come alpiste su nueva energía es 30 + 20/2 = 40 
- si tiene 30 de energía y vuela 3 km su nueva energía es: 30 - 20 - 2*3 = 4


## Ejercicio 2: Roque
Agregar a Roque, que es una persona

### Ave de roque
Tiene un ave, a veces es Pepón, a veces es Pepita, por lo tanto tiene que entender un mensaje para que se le indique cual es su ave. Inicialmente es pepita.

### Alimentar

 Entiende el mensaje *alimentar*, que recibe un alimento por parámetro. Al recibir este mensaje roque alimenta a su ave. 

Ejemplos:
- Si tiene a pepona con energía de 30, y recibe el mensaje alimentar(alpiste) pepon queda con 40 de energía
- Si tiene a pepita con energía de 100 y recibe el mensaje alimentar(alpiste) pepita queda con 120 de energía.

### Cenas

Entiende el mensaje *cenas* sin parámetros, el cual devuelve la cantidad de veces que roque dio de alimentar a su ave desde que es la suya (pensar como hacer para recordar este dato).


## Ejercicio 3: Excepciones

Milena es una entrenadora de aves que puede entrenar a varias a la vez. Cuando Milena recibe el mensaje movilizar(distancia), hace que todas sus aves se muevan esa distancia.

Se pide 
* implementar a milena, 
* realizar las modificaciones a los objetos ya resueltos para garantizar que un ave no puede volar una distancia mayor a la de su energia. 
* Tener en cuenta que milena no puede movilizar sus aves si alguna de ellas no puede recorrer esa distancia

Ejemplos: 
 Suponiendo que milena tiene a pepita y a pepon, con sus respectivas energias iniciales (100 y 30).
 
 * tanto pepita como pepon pueden volar 4 kms. Por lo tanto milena puede movilizarlas.
 * pepita puede volar 6 kms, pero pepon no. Por lo tanto milena no puede movilizarlas. (Si se intenta movilizarlas ambas deben quedar con su energia inicial)
 * ni pepita ni pepon pueden volar 100 km.
 
 
 
 
 











