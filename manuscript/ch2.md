Tipos de datos
==============

Enteros
-------

En matemáticas se clasifican como enteros aquellos números en el intervalo **(-oo, oo)**, 
que no contienen una parte decimal o fraccionaria. Dadas las limitaciones de los ordenadores 
es evidente que no podrá representarse un entero demasiado "grande", generalmente el límite 
de representación es dado por las características del procesador.

En Python existen 2 tipos de enteros: el tipo entero ordinario (int) y el entero largo (long). 
La diferencia es precisamente el límite de representación de cada uno. Puede obtener información 
acerca del máximo entero tecleando lo siguiente en el intérprete de Python:

.. code:: python

	>>> import sys
	>>> max_int=sys.maxint
	>>> max_intl=sys.maxsize

Siendo ``max_int`` el entero ordinario máximo representado, generalmente este valor equivale a 
**(2^31)-1**. El valor de ``max_intl`` corresponde al máximo entero largo.

Para definir un tipo entero no hace falta declararlo de forma explícita, por ejemplo:

.. code:: python

	>>> a=1
	>>> b=100
	>>> type(a)
	<type 'int'>
	>>> type(b)
	<type 'int'>
	>>> c=-100
	>>> type(c)
	<type 'int'>


De coma flotante
----------------

Los números de coma flotante son aquellos que normalmente conocemos como números reales. 
En Python para que un valor numérico sea "reconocido" como real, debe utilizarse la función 
``float`` o bien añadir la parte decimal del número, aun cuando esta sea nula:

.. code:: python

	>>> a=3
	>>> b=float(3)
	>>> c=3.0
	>>> type(a),type(b),type(c)
	(<type 'int'>, <type 'float'>, <type 'float'>)



Booleanos
---------

También conocidos como valores lógicos, son un tipo de dato fundamental, cuyo valor sólo 
puede adquirir dos estados: verdadero y falso. Se utilizan comunmente para la toma de 
decisiones en conjunto con las estructuras de control de flujo. Las constantes booleanas 
en Python se nombran mediante ``True`` y ``False``.

Por ejemplo, si comparamos dos números enteros cualesquiera para ver si son iguales:

.. code:: python

	>>> a=10
	>>> b=15
	>>> a==b
	False
	>>> a>b
	False
	>>> a<b
	True


Cadenas de caracteres
---------------------


Listas
------


Tuplas
------

Esto es una tupla

	>>> print "HOLA"

::

	print 1
	import os
	os.system('pause')



Diccionarios
------------

