# ¿Que es EC2?

Amazon Elastic Compute Cloud (Amazon EC2) es una parte central de la plataforma de cómputo en la nube de la empresa Amazon denominada Amazon Web Services (AWS).

# ¿Para que sirve?
EC2 permite a los usuarios alquilar computadores virtuales en los cuales pueden ejecutar sus propias aplicaciones.

# Documentacion:
Primero empezamos por lanzar una instancia:


![Imagen 1](aws/1.PNG)


Despues a la derecha nos aparecera una lista y tendremos que clickar aqui:


![Imagen 2](aws/2.PNG)

Tenemos que seleccionar la opcion de ubuntu, en mi caso la mas nueva y le damos a select:


![Imagen 3](aws/3.PNG)

Despues nos aparecera lo siguiente (tendremos uno ya seleccionado por defecto) y le damos a next:


![Imagen 4](aws/4.PNG)

Nos saltara aqui, y le volvemos a dar a next:


![Imagen 5](aws/5.PNG)

Aqui cambiaremos el tamaño y lo pondremos a 30:


![Imagen 6](aws/6.PNG)

Despues le damos otra vez a Next:


![Imagen 7](aws/7.PNG)

Next:


![Imagen 8](aws/8.PNG)

Y ya aqui le daremos a Launch


![Imagen 9](aws/9.PNG)

Abajo a la derecha


![Imagen 10](aws/10.PNG)

Aqui nos saldra una ventana en la cual tendremos que crear una clave:


![Imagen 11](aws/11.PNG)


En mi caso lo he llamado clave2, le damos a descargar y lo guardamos bien para saber donde se encuentra Y le damos a Launch instances :


![Imagen 12](aws/12.PNG)


![Imagen 13](aws/13.PNG)


![Imagen 14](aws/14.PNG)


Nos saldra esta ventana:


![Imagen 15](aws/15.PNG)

Luego nos vamos a instancias y veremos que ya esta creada:


![Imagen 16](aws/16.PNG)


Ahora le daremos a mis acciones y despues a conectar:


![Imagen 17](aws/17.PNG)


Ahora hacemos click derecho sobre la carpeta donde hemos guardado la clave que habiamos creado, y le damos a Git Bash here (y escribimos el siguiente comando):


![Imagen 18](aws/18.PNG)


Despues copiamos y pegamos este comando:


![Imagen 19](aws/19.PNG)


Le tendremos que dar a si para continuar:


![Imagen 20](aws/20.PNG)


# ¿Que es Apache?

El servidor HTTP Apache es un servidor web HTTP de código abierto, para plataformas Unix (BSD, GNU/Linux, etc.)

# ¿Para que sirve?
Apache permite a los propietarios de sitios web servir contenido en la web

# Documentacion:
Primero empezamos por instalar apache con el siguinte comando:


![Imagen 21](apache/21.PNG)


Iniciamos la instancia, y despues debajo de esto abrimos la pestaña de seguridad


![Imagen 22](apache/22.PNG)


Clickamos sobre el link de grupos de seguridad y despues a editar:


![Imagen 23](apache/23.PNG)


Y nos llevara a esta pestaña:


![Imagen 24](apache/24.PNG)


Lo dejaremos asi:


![Imagen 25](apache/25.PNG)


Y le daremos a guardar:


![Imagen 26](apache/26.PNG)


Podemos ver en esta lista todos los cambos que hemos realizado:


![Imagen 27](apache/27.PNG)


Por ultimo copiamos la ip en nuestro navegador y si lo hemos hecho bien nos aparecera la siguiente ventana:


![Imagen 28](apache/28.PNG)


# ¿Que es Mysql?

MySQL es un sistema de gestión de bases de datos relacional desarrollado bajo licencia dual: Licencia pública general/Licencia comercial por Oracle Corporation y está considerada como la base de datos de código abierto más popular del mundo,1​2​ y una de las más populares en general junto a Oracle y Microsoft SQL Server, todo para entornos de desarrollo web.

# ¿Para que sirve?
MySQL sirve para almacenar toda la información que se desee en bases de datos relacionales, como también para administrar todos estos datos sin apenas complicaciones gracias a su interfaz visual y a todas las opciones y herramientas de las que dispone.

# Documentacion:
Primero empezamos por instalar mysql con el siguinte comando:




