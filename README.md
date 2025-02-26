# Configuración de un servidor de correo

# Paso 1

Agregar los dispositivos a la hoja de trabajo. Usaremos un servidor, un switch y dos laptops.

![Imagen de ejemplo](Image2.png)

Seguidamente hacer las conexiones entre estos dispositivos

![Imagen de ejemplo](Image3.png)

# Paso 2
 
Asignar la dirección IP del servidor y del DNS server

![Imagen de ejemplo](Image4.png)

Posteriormente irnos al apartado de DHCP para asignarle la dirección de IP y hacer la configuración y lo guardamos dandole al botón "Save"

![Imagen de ejemplo](Image5.png)

Luego nos dirigimos a Email, creamos el nombre del dominio que en este caso será "gatos.com" y a cada dispositivo le colocamos un usuario y contraseña

![Imagen de ejemplo](Image6.png)

Luego nos vamos a las Laptops y en IP seleccionamos DHCP

![Imagen de ejemplo](Image7.png)

![Imagen de ejemplo](Image8.png)

Ahora nos digirimos a configuración de Email y llenamos los datos correspondientes 

![Imagen de ejemplo](Image9.png)

![Imagen de ejemplo](Image10.png)

# Paso 3

Finalmente para comprobar que está todo bien hacemos la prueba enviando un correo desde la laptop0 a la laptop1 haciendo lo siguiente:
1. Le damos a "Compose"

![Imagen de ejemplo](Image11.png)

3. Llenamos los datos y el mensaje que queremos enviar y lo enviamos dandole al botón "Send"

![Imagen de ejemplo](Image12.png)

3. Nos dirigimos al otro dispositivo, a la laptop1, y en "receive" debería mostrarse el correo de la Laptop0

![Imagen de ejemplo](Image13.png)

![Imagen de ejemplo](Image14.png)
