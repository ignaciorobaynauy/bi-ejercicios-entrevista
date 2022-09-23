# Ejercicios de diseño de algoritmo

## Distribución de Cajas 

Tengo cierta cantidad de cajas apiladas en columnas. Se asegura que la cantidad total de cajas es múltiplo de las columnas, de tal manera que se puedan formar columnas de igual tamaño.

Escriba un algoritmo que dada la cantidad de cajas en cada columna, indique cuántas cajas hay que mover para que todas las columnas tengan la misma cantidad de cajas.
Y además indicar el número (o índice) de columna en el cual se deben agregar o sacar dichas cajas (*1).
Para devolver esta información, utilizar la forma de lista de par ordenado (o tupla) como (Número de Columna y Cantidad)

![DistribucionDeCajas](img/DistribucionDeCajas.png)

## String incluído
Dado 2 cadenas de caracteres, devuelve verdadero (true) si la segunda cadena está contenida en la primera, de lo contrario devuelve falso (false).
No utilizar funciones nativas del lenguaje, y en caso de hacerlo escribir la implementación.

Ejemplo: 
- (“Joven de Alto Vuelo“, “de Alto”) -> True
- (“Joven de“, “De Alto”) -> false
- (“Joven de AlDe Alto Vuelo“, “De Alto”) -> True

Escribir una solución en pseudocódigo imperativo y, de ser posible, una variante en funcional usando recursividad (considere usar funciones Cola y EsPrefijo).

# Ejercicios de Modelado

## SQL-1

La compañía Viajes S.A. vende noches de hotel y vuelos a través de su portal de internet en 10 países alrededor del mundo. En el portal se pueden buscar hoteles por destino y fecha de hospedaje (Check-in, Check-Out), además de los pasajes aéreos relacionados al viaje.

Cuando se compran vuelos y hoteles, se registra en el sistema de la compañía cada producto comprado de forma individual, aunque se hayan comprado en una misma transacción.

Al registrarse ambos productos comprados, cada uno puede terminar en un estado diferente (EMITIDO o CANCELADO) según la disponibilidad real en el proveedor al momento de la compra.

Además, se registran para cada una de ellas los intentos de cobro, que pueden tener estado “ERROR” u “OK”.
1. Modelar el mínimo de entidades (con sus atributos) para resolver la consulta requerida en el punto 2. Indicar la relación entre las entidades creadas.
2. Confeccionar una consulta SQL para el reporte de cobros, que liste “Monto cobrado OK, por país, de productos emitidos”
3. Además, la compañía ofrece cupones de descuento nominales, y se registran en un sistema cuyo modelo de datos es el siguiente:

