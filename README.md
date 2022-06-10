# DATOS Y ALMACEN

**Storage: Proporciona servicios de almacenamiento de archivos y objetos.**

### Cuenta de Almacenamiento de Azure

![Almacenamiento de Azure](Imagenes/azurealmacenamiento1.png)

- **Modelo de servicio:** IaaS.
- **Caracteristicas:** Seguridad, alta, disponibilidad, durabilidad y escalabilidad.

La cuenta de almacenamiento de es la que contiene todos los objetos de los demas servicios.

-----------------------------------------------------------------------------------
## Azure Queue Storage  *(Queue= significa cola)*

![Azure Queue Storage](Imagenes/queueStorage1.png)

Lo que hace es encolar mensajes.

Mensajes pequeños o textos pequeños.

El primer mensaje que llega, es el primero que sale.

- **Modelo de servicio:** IaaS
- **Funcion:** Para almacenar cantidades de mensajes.
- **Caracteristicas:** Accesibles por HTTP o HTTPS.
- **Caracteristicas:** Encola mensajes de hasta 64KB.
- **Cuando usar:** Respuestas de APIs, servicios de mensajeria, loT.

-----------------------------------------------------------------------------------------------------------------------------

### Pasos para crear un Azure Queue Storage

1.- Abrimos el [Portal Azure](portal.azure.com).

![Potal Azure](Imagenes/portalAzure.PNG)

2.- Nos vamos a nuestro almacenamiento.

![Almacenamiento](Imagenes/cuentaAlmacenamiento.PNG)

3.- Buscamos donde dice cola.

![Buscalos Cola](Imagenes/colas.JPG)

4.- Agregamos una cola de mensaje.

![Add Cola](Imagenes/Crearcola.JPG)

5.- Le damos un nombre a la cola de mensajes.

![Cola Ready](Imagenes/ColaLista.JPG)

6.- Accedemos a la cola creada.
![Accedemos a la Cola](Imagenes/accedemosalacola.JPG)
7.- agregamos un mensaje y ponemos en cuanto expira.
![Creamos un Mensaje](Imagenes/cremosunmensaje.JPG)
8.- Se cargara eso, los podemos ir quitando o agrenado otros mensajes.
![Listo](Imagenes/fin.JPG)
9.- No se puede editar, solo borrar, resetear toda la cola o agregar.
