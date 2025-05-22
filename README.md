![Logo en blanco y negro con las iniciales del autor y la descripcion conversor de monedas](https://github.com/user-attachments/assets/3ef0e50c-1d2a-4f20-8ceb-136eee72d897)

Esta aplicación permite hacer la conversión entre distintas monedas ejecutando el siguiente cálculo:
<br>(Moneda origen * Cantidad a convertir * Tasa de cambio) / Moneda destino.</br>

<Strong>Funcionalidad:</Strong>

Se ha diseñado un menú con 6 opciones de cambio de monedas y una opción para salir del sistema. También tiene una opción por defecto para solicitar al usuario que ingrese una opción válida cuando este digite un número distinto a los disponibles en el menú. 
<br>Menú de opciones mostrado al usuario:
<em>1. Dolar americano a peso argentino.
2. Pesos argentinos a dolar americano.
3. Dolar americano a real brasileño.
4. Real brasileño a dolar americano.
5. Dolar americano a peso colombiano.
6. Peso colombiano a dolar americano.
7. Salir del sistema.</em></br>

<strong>Ejecución:</strong>
1. El debe usuario digitar la opción deseada según las que muestra el menú.
2. El usuario debe ingresar la cantidad que desea convertir.
3. La aplicación realiza la búsqueda de la tasa de conversión de la moneda de origen a la moneda de destino en la API ExchangeRate y hace el cálculo indicado anteriormente.
4. La aplicación indica al usuario el resultado del cálculo y le muestra nuevamente el menú de opciones por si desea realizar otro cálculo.
5. El usuario debe ingresar los parámetros para la siguiente búsqueda o simplemente seleccionar la opción 7 para salir del sistema.

<Strong>Tecnologías utilizadas:</strong>
1. Java
2. API de ExchangeRate
3. Biblioteca Gson 2.13.1
4. IDE IntelliJ
