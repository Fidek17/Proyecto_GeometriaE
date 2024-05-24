# Proyecto_GeometriaE
## **Calculadora de operaciones con vectores**

Proyeto pensado para la materia de Geometría del Espacio.

### Objetivo:
Crear una Calculadora de operaciones con vectores para facilitar y agilizar el procedimiento.


Aprovechar los conocimientos obtenidos en la materia y juntarlos con los aprendidos en semestres anteriores para de esta forma generar código que nos permita hacer las operaciones con vectores de manera mucho más rápida aprovechando una herramienta tan útil como lo puede ser el lenguaje de *Python* por su versatilidad y sobre todo, por su capacidad de graficar los vectores generados en cuestión al final de la matriz.

### Funcionalidad:

Primero se deberá hacer uso de las bibilotecas que nos ayudan, en su mayoria, a hacer más sencilo el graficar los resultados, ya entrando en código:
1. Se crea una clase vector que contendrás las coordenadas del eje de las x, y, z.
2. Se crea la función *calcular_distancia* que recibe dos objetos de la clase *Vector* para realizar los calculos de la distancia entre vectores, esto usando las definiciones vista en clase.

3. Continuamos con la función *calcular_producto_punto* que de igual manera recibe dos objetos de clase *Vector* y directamente nos retorna el valor generado por las operaciones coodifcadas por las definiciones vistas en clase, multiplica cada entrada con su correspondiente y se suma cada valor resultante.
4. Se crea la función *calcular_producto_vectorial*, este se construye similar a la función anterior pero cambia la operación según la definición vista, en este caso se multiplican las entradas entre si como si se tratará de un determinante y se hace en es orden especifico para finalmente generar el *vector* resultado.
5. Seguimos con *sumar_vectores*, recibe dos objetos de la clase *Vector* y hace las operaciones de sumar cada entrada con la otra para generar un nuevo *vector*.
6. Después se tiene a *calcular_triple_producto_vectorial*, este recibe 3 vectores y con primero con los vectores *v1* y *v1* manda a llamar a la función para calcular el producto vectorial, guarda este resultado en un *vector* de nombre *v1_cross_v2* y nos retorna el resultado mandando a llamar por último a la función *calcular_producto_punto* que se le manda el vector *v1_cross_v2* y el vector *v3*, como se puede observar, estas operaciones obedecen a las definiciones vistas en clase.
7. A la función *graficar_vectores* se le dará la tarea de graficar tantos objetos de la clase *vector* como se le manden.

8. Por ultimo en el **main** simplmemente creamos un menu para poder escoger que operacion se desea realizar, si se desea otra pareja de vectores o si se desea salir del programa, todo esto digitando el numero del menu.

### Uso:

En mi caso me ayudo mucho para verificar si las operaciones de mi tarea y sus resultados eran los correctos, las operaciones fueron generadas a mano pero verficar sus resultados fue mucho más rapido y por esto mismo estoy convencido que le podremos dar uso a este material de trabajo más adelantado el semestre.

### Conclusión: 
Considero que es un proyecto no muy complicado o muy extenso pero de igual forma creo que su valia radica en el haber usado conocimientos anteriores para su desarrollo además de su innegable utilidad para esta materia al momento de las tareas y el que tendra a futuro. 

### Código
Con el siguiente link se llevará al usuario a una ventana de *Collab*, en esta página se puede ejecutar el programa sin problemas presionando el bóton de *play* en la esquina superior derecha.

https://colab.research.google.com/drive/1ARABdFS6SE7qykPQD7DKWvjpkgZ6sb1E?usp=sharing


