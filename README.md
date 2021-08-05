# Lab1

Ejecución:
  * Desplegar 3 instancias EC2 con Amazon Linux para el servidor y dos clientes de prueba.
  * Abra los puertos para todas las conexiones TCP en los inbounding rules de las instancias, si lo desea desde la ip 0.0.0.0.
  * conectese a la instancia por ssh.
  * instale git con sudo yum install git
  * Cualquiera de los archivos sea el cliente o el servidor debe ser ejecutado con python3.
  * Antes de ser ejecutado es importante que el servidor esté escuchando la ip privada de la instancia y los clientes deben estarse conectando a la ip publica de la instancia del servidor.
  * ingresa a los archivos con su editor preferido y cambia la ip que está en las primeras lineas de codigo.
  
  Funcionamiento:
    * La aplicación es un chat donde el servidor es quien recibe todos los mensajes y los clientes lo envían.
    * se soportan conexiones de varios clientes simultaneamente.
    
  Nota: Este laboratorio fué hecho basado en el siguiente tutorial https://pythonprogramming.net/client-chatroom-sockets-tutorial-python-3/?completed=/server-chatroom-sockets-tutorial-python-3/
