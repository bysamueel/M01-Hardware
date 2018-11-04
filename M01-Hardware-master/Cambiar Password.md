# Es posible cambiar la contraseña sin tener la contraseña ROOT?

Hay varias maneras de obtener permisos de root desconociendo la contraseña, como podemos cambiarla?

## Mètodo 1

* Hemos de poner en el terminal: 

**<pre> sudo su </pre>**

* Ahora tendriamos el acceso a los permisos de root, ejecutamos el siguiente comando: 

**<pre> passwd root </pre>**

* Ponemos la contraseña que deseemos + ENTER  
* Luego ponemos otra vez la contraseña que pusimos anteriormente + ENTER  
  
De esta manera nuestra contraseña de root habrá sido modificada. 

## Mètodo 2

Pondremos el comando 

**<pre> sudo passwd root </pre>**  

Ahora, ponemos la contraseña primero una vez y después otra para guardar los cambios. 

Una vez hecho esto escribiremos el comando 

**<pre> su - </pre>**

Y a continuacion ponemos la contraseño reestablecida y tendremos acceso root con la contraseña que hemos establecido
