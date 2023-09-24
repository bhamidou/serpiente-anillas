# Ejercicio 6 - Serpiente

Diseñaremos un programa orientado a objetos que nos permita simular la vida de una
serpiente. Nuestra serpiente será un poco especial y tendrá las siguientes características:

- Es una serpiente compuesta por anillas de un color diferente cada una. Estos colores
podrán alternar entre (r ,v,a). Por ejemplo: rrvva  sería una serpiente de 5 anillas.
- Cuando nace tiene un color asignado al azar.
- Se simulará su vida hasta que esté muerta (en nuestro caso se quede sin cuerpo) de
forma que cada año (segundo):
o Si es joven (menos de 10 años) hará dos cosas:
 Crecerá el 80% de las veces: añadiendo una nueva anilla a su cuerpo de
un color asignado aleatoriamente.
 Mudará la piel el 20% de las veces. En este caso se cambia el cuerpo de
toda la serpiente respetando su número de anillas.

o Si ya va siendo mayorcilla (más de 10 años):
 Decrecerá el 90% de las veces: quitando una anilla a su cuerpo (la
última) y respetando el resto.
 Mudará la piel el 10% de las veces.

- Aleatoriamente, el 10% de las veces, durante el año de esa vida puede sufrir el ataque
de una mangosta que se la zampa y por lo tanto la serpiente muere y se para la
simulación.
Cuando esté realizado, generaliza el ejercicio para un nido de serpientes que puede albergar,
como máximo, hasta 20 serpientes.

En este caso la simulación se ajusta a lo siguiente:

- Se simulará la vida del nido durante 5 minutos.
- Cada cinco segundos nacen (si pueden) entre 1 y 3 serpientes, ocupando su lugar en el
nido.
- Cada segundo (año de la vida de una serpiente) pasará la vida para cada serpiente del
nido según se especificó en el apartado anterior (menos el ataque de la mangosta).
- Cada 10 segundos una mangosta aparece por el nido zampándose entre 0 y 4
serpientes el 20% de las veces.
- Se debe mostrar el estado del nido cada segundo y describir lo que va ocurriendo.
