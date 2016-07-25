Estructuras de control
=========================

Sentencia if
------------

La sentencia ``if`` es una estructura de control flujo simple, utilizada para la toma 
de decisiones en el curso de ejecución que sigue el programa. En casi todos los algoritmos 
existen *porciones* de código que sólo deben ejecutarse cuando se cumpla una condición 
establecida, es ahí donde la sentencia ``if`` tiene su utilidad. Vea el ejemplo dado 
a continuación:

.. code:: python

	a = 10
	if a > 0:
	    print "Número positivo"

Veamos: primero se define una variable **a** con valor 10, posteriormente se hace la 
comprobación que si **a** es mayor a cero, lo cual implicaría imprimir en pantalla 
un mensaje, de lo contrario no se realizará acción alguna. Para el ejemplo mostrado, 
puesto que **a** es 10, entonces es un número positivo, y por ende se ejecutará la 
porción de código incluido en la sentencia ``if``.

En muchas situaciones la sentencia ``if`` se utiliza en conjunto con la sentencia 
*complementaria* ``else``, para formar una bifurcación doble, que permite seleccionar 
una opción especificada o bien otra por default. A manera de ejemplo vamos a desarrollar 
un programa que determinará si un número ingresado es par o impar:

.. code:: python

	n = input("n = ")
	if (-1)**n == 1:
	    print "Par"
	else:
	    print "Impar"

Si la condición propuesta se cumple entonces se ejecutará el bloque incluido dentro de la 
sentencia if, en cualquier otro caso se ejecutará el bloque definido por la cláusula ``else``.

Además de las anteriores, existe otra forma más *general* definida por las sentencias 
``if-elif-else`` cuya estructura general es:

.. code:: python

	if cond1:
	    # ... 
	elif cond2:
	    # ...
	elif cond3:
	    # ...
	.
	.
	.
	elif condN:
	    # ...
	else:
	    # ...

La anterior es un tipo de bifurcación múltiple, que permite seleccionar entre varias 
condiciones definidas en la cláusula ``if`` y en las subsecuentes ``elif``, y una 
opción por defecto establecida en la cláusula ``else``. Un ejemplo: 

.. code:: python

	n = input("n = ")
	if n>0:
	    print "Positivo"
	elif n<0:
	    print "Negativo"
	else:
	    print "Cero"




Bucle for
---------


Bucle while
-----------
