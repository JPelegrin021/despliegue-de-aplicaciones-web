1-2. 
![Captura de pantalla 2023-09-20 132638](https://github.com/JPelegrin021/despliegue-de-aplicaciones-web/assets/144775334/0410b6f3-06df-4ac5-a5d9-9d290ba108ee)


3. El servidor asigna una sesion al cliente, asigna un token a la sesion y una vez a recibido la peticion con el user y la contraseña asigna una cuenta a la sesion del cliente. Para mas seguridad para enviar la informacion de inicio de sesion anteriormente se nos asignara un token llamado: logintoken. El cual sirve para "controlar" y traquear las peticiones de inicio de sesion.
![Captura de pantalla 2023-09-20 133120](https://github.com/JPelegrin021/despliegue-de-aplicaciones-web/assets/144775334/b04cfa79-cede-4903-b3eb-f526861ead14)



4. Puerto HTTP: Las peticiones HTTP suelen recibir en el puerto 80 para conexiones no seguras (HTTP) y en el puerto 443 para conexiones seguras (HTTPS).

Capa del modelo TCP/IP: El protocolo HTTP se encuentra en la capa de aplicación del modelo TCP/IP. Además, el modelo TCP/IP comprende otras capas, como la capa de transporte, donde se ubican protocolos como TCP y UDP, y la capa de red, donde se encuentra el protocolo IP.

Protocolos TCP, UDP e IP:

TCP (Transmission Control Protocol): Se sitúa en la capa de transporte y garantiza la entrega confiable y ordenada de datos.
UDP (User Datagram Protocol): También está en la capa de transporte, pero no garantiza la entrega ni el orden de llegada de datos, ya que es un protocolo sin conexión.
IP (Internet Protocol): Se ubica en la capa de red y se encarga del enrutamiento y la entrega de paquetes de datos en la red.


5. La respuesta "HTTP/1.1 302 Found" indica que el servidor ha encontrado el recurso solicitado, pero el cliente debe realizar una redirección temporal a la URL especificada en el encabezado "Location" para obtener el recurso.
