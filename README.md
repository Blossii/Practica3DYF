# Practica3DYF



Juan José Regueira Fernández.



W -> Moverse hacia delante

A -> Moverse hacia la izquierda
S -> Moverse hacia atrás
D -> Moverse hacia la derecha

F -> Bajar

R-> Subir



4 -> Agarrar objeto



Tras intentar todas las opciones, no he podido encontrar el error por el cual no se pueden agarrar los objetos.

El peso de la bola de bolos es de 2kg. La bola tiene el BP grab component para poder agarrarla y lanzarla. Lo mismo con el resto de componentes que se tienen que agarrar.



El damage threshold de la estatua está en 50000.0, de otra forma se rompía al iniciar la simulación.



Tanto las partes del mr potato como el dardo tienen lógica, si se sueltan cerca del cuerpo o de la diana, hacen snap a estos.

