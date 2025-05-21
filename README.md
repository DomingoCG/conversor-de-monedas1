# Conversor de monedas

Esta aplicación permite hacer la conversión entre monedas multiplicando:
Moneda origen * Tasa de cambio * Cantidad a convertir / Moneda destino.
Para mostrar la funcionalidad se ha diseñado un menú con 6 opciones de cambio de monedas, una opción para salir del sistema y una opción por defecto para cuando el usuario ingrese una opción no valida.

Ejecución:
1. El usuario digita la opción deseada según lo que muestra el menú.
2. El usuario ingresa el monto que desea convertir.
3. La aplicación realiza la búsqueda de la tasa de conversión en la API ExchangeRate y hace el cálculo indicado anteriormente.
4. La aplicación muestra al usuario el resultado del cálculo y nuevamente el menú de opciones por si desea realizar otro cálculo.
5. El usuario ingresa los parámetros para la siguiente búsqueda o selecciona la opción 7 para salir del sistema.

Tecnologías utilizadas:
1. Java
2. API de ExchangeRate
3. Biblioteca Gson 2.13.1
4. IDE IntelliJ
