# Ejercicios de Modelado

## SQL-2

La compañía Viajes S.A. necesita contar con métricas que le permitan entender el comportamiento de los diferentes tipos de usuarios en su sitio WEB, para esto desarrolla un sistema de trackeo que registra la interacción de los usuarios en el sitio.

La estructura de tracking es la siguiente:

![SQL-2](img/SQL-2.png)

**Nota:** *La tabla Transaction está poblada con información del sistema transaccional de la empresa, como las tablas provienen de sistemas diferentes pueden existir transacciones que estén registradas en el sistema pero NO trackeadas.*

1. Explique con sus propias palabras, una posible interpretación del modelo, dar ejemplos del contenido de la tabla UserTracking.
2. Detallar un posible contenido de la tabla que represente la navegación de un usuario que el lunes hizo 3 búsquedas de Vuelos, llegó hasta el checkout en el 3er intento y desistió, el miércoles entró directo al checkout, luego compró y continuó buscando Hoteles.
3. Confeccionar una consulta SQL que calcule el “convertion rate” diario por país y producto de la página de búsqueda y de la página del Checkout.
4. Los usuarios desean que las ventas usadas para calcular el “convertion rate” coincidan exactamente con los reportes de ventas corporativos, confeccione una consulta SQL para satisfacer la necesidad.

En los últimos tiempos Viajes S.A. tuvo un importante crecimiento que se ve reflejado directamente en el volumen de la información a procesar.
1. Qué tipo de tecnología/arquitectura considera debería adoptar esta empresa?
2. Qué tipo de estrategia debería seguirse para que tanto usuarios Analistas como Managers puedan trabajar con la información?
