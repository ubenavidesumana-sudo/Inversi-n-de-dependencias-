# Inversi-n-de-dependencias-
Este principio de inversión de dependencias nos dice que las clases de alto nivel no deben depender 
de las clases de bajo nivel si no de abstracciones. por ejemplo en este codigo La clase AdmProducto utiliza EnvioRecibo para enviar los recibos, sin depender de una forma específica de envío. EnviarEmail y EnviarApp implementan esa clase. se puede agrega otra forma de envío, como SMS sin cambiar el código de AdmProducto.
