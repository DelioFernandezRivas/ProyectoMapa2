# ProyectoMapa2
ProyectoMapa
Estos son los pasos que segui para realizar el proyecto:
1º Creamos el Proyecto de tipo vacio 
2º Creamos el fracment que contenga el mapa en el activity de la aplicacion
3ºCon esto echo pasamos a obtener una cuenta en google API y habilitamos en nuestra aplicación google play services y 
los servicios de google.maps
4º Obtenemos el SH1 y el nombre de nuestro proyecto del android manifest, el SH1 lo obtenemos de la siguiente forma:
Abrimos el terminal y vamos a la ruta "C:\" mediante los comandos "cd" y "cd ..", una vez en la ruta seguimos los siguientes pasos:

//Entramos en la carpeta Program Files
C:\>cd "Program Files"

//Entramos en la carpeta Java
C:\Program Files>cd Java

//Entramos en la carpeta de nuestro jre (la versión puede variar)
C:\Program Files\Java>cd jre1.8.0_20

//Entramos en la carpeta bin
C:\Program Files\Java\jre1.8.0_20>cd bin

//Introducimos la siguiente combinación de comandos cambiando "MI_NOMBRE_DE_USUARIO" por vuestro nombre de usuario
(la ruta es para buscar el archivo debug.keystore que por defecto se instala en esta ruta, si se ha cambiado de ubicación hay que cambiar la ruta)
C:\Program Files\Java\jre1.8.0_20\bin>keytool -list -v -keystore C:\Users\MI_NOMBRE_DE_USUARIO\.android\debug.keystore

//Debe perdirnos una contraseña
Introduzca la contraseña del almacén de claves:

//Introducimos "android" sin comillas y en minúscila tal cual lo muestro. Si todo ha ido bien nos muestra las huellas digítales de nuestro certificado.

5ºCreamos una Clave de APi y le añadimos el SH1 y el nombre de la api 
6ºCon esto realizado ejecutamos y nos muestra el mapamundi de google maps
7ºObtenemos la localizacion de nuestro dispositivo
8ºCreamos circulos que muestren las zonas donde pueden estar los tesoros 
9ºCreamos la localizacion exacta de los tesoros
10º Cuando se acerque a la zona se mostrará la localización exacta del tesoro 

Esto es todo 
