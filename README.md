# zork

DETALLES I DIFICULTADES:
Cómo apenas conocía el lenguaje C++, me ha resultado complicado adaptarme, sobre todo los 2-3 primeros días. Aun así, como el concepto de clases, herencia… lo he trabajado mucho con Java, y he programado mucho con C a lo largo de la carrera, al final me he podido por adaptar, buscando todas las dudas y errores por internet, y completar el código, siendo consciente que me queda mucho por aprender y mejorar, para hacer el código más claro y, sobretodo, más eficiente. 
He separado por clases el juego tal y como se detallaba en el enunciado. 
Es un juego con 5 habitaciones, que previamente pueden estar cerradas, un NPC y objetos que el jugador principal puede recoger y dejar.  

INSTRUCCIONES PARA SUPERAR EL JUEGO:
1. Go north
2. Take sword
3. Go west
4. Kill troll (daño -50 hp)
5. kill troll (muere y deja una llave en la habitación)
6. Take key
7. Go east
8. Go south
9. Open the door (usas la llave que dejó el troll)
10. Go east
11. Take key
12. Go west
13. Go north
14. Open the door
15. Go north
16. Go east

Obs: 
1. Cada llave abre una determinada puerta
2. He intentado tener en cuenta cualquier instrucción que introduzca el jugador que no sea válida para indicarlo por pantalla: direcciones incorrectas, matar al troll sin arma en el inventario, intentar abrir puertas sin la llave, instrucciones que no detecta el parse(), etc…  
