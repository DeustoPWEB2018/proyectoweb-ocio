# Plano de estructura
## Diseño de la interacción
<<<<<<< HEAD
=======

En esta parte de diseño de la interacción definiremos el comportamiento que tendrá el usuario en nuestra página web de contenido musical de Musikamania.com. Para definir este comportamiento, será necesario identificar cómo se adecuará y responderá el sitio web al dicho comportamiento del usuario. 

El objetivo de esta interacción, será como hemos dicho identificar qué es lo que hace el usuario, y cómo lo hace e intentar diseñar el software definitivo de nuestra página web de manera que mejor funcione para aquellos usuarios que puedan acceder a la página. 

### Pantalla de entrada

En nuestra página web de Musikamania, en la pantalla de entrada aparecerá un anuncio cada vez que el usuario entre en ella. Para ser más exactos, el anuncio tendrá una duración de 20 segundos, que tras 10 segundos del anuncio, aparecerá la opción de “Skip add”, para aquellos que quieran quitar el anuncio y entrar en la página principal de nuestra web, pero también los usuarios tendrán la posibilidad de permanecer en el anuncio si es de su interés.

Hay que dejar claro, que el anuncio de la pantalla de entrada les aparecerá a todas las personas que entren en la página web de Musikamania, tanto si están registradas en la web, como si no lo están.  

### Buscador

Aparece el icono de una lupa y al lado una barra de texto para que los usuarios escriban lo que quieran.

- Si escriben cualquier letra, número o palabra que contenga cualquier contenido que esté publicado en la página web y hacen clic en el icono de la lupa aparecerán el título, autor y fecha de cada publicación ordenados en una lista cronológicamente, del más actual al que más tiempo tiene. 

- Si escriben cualquier letra, número o palabra que no aparezca en ninguno de los contenidos publicados en la página web, cuando hagan clic en el icono de la lupa les aparecerá una nota:

*NOTA:* No hemos encontrado resultados para tu búsqueda

### Acceso

Cuando hacen clic en acceso les aparecerá una barra con dos opciones: login y regístrate.

#### Si hacen clic en login

![login](https://github.com/DeustoPWEB2018/proyectoweb-ocio/blob/anejuaristi-estructura/3-estructura/Imágenes/login.jpg)

- Si hacen clic en el cuadrito de Recuérdame se guardarán automaticamente el nombre de usuario y la contraseña. Cada vez que accedan a la página ya estarán directamente dentro de sus cuentas. Eso estará indicado arriba a la derecha, en vez de poner acceso, aparecerá el icono de un usuario y el nombre de usuario con el que esté registrado.

- Para asegurarse que han hecho clic en Recuérdame, aparecerá un tick en el cuadrito que tendrá al lado.

##### Si hacen clic en Entrar

Cuando el suario hace clic en Entrar, las siguientes comprobaciones tienen lugar en el servidor:

- Si se había introducido la dirección de e-mail, pero que no era una dirección de e-mail real porque no tiene el formato correcto (no está el signo @ o contiene caracteres no permitidos en direcciones de e-mail), el servidor devuelve otra página muy parecida al Formulario de entrada, sólo que esta vez, se inserta un mensaje de error en rojo sobre el cuadro de dirección de e-mail, diciendo *NOTA:* "La dirección de e-mail que usted ha escrito no es válida. Por favor, compruebela otra vez". Aunque este texto está en rojo, el texto "Por favor, introduzca su dirección de e-mail" sigue apareciendo en negro. La dirección de e-mail incorrecta que el usuario haba escrito originalmente aparecerá rellenando el cuadro de edición.

- Si se había introducido la dirección de e-mail, pero no corresponde a un miembro registrado, el servidor devuelve otra página muy parecida al Formulario de entrada, sólo que esta vez, se inserta un mensaje de error en rojo sobre el cuadro de dirección de e-mail, diciendo *NOTA:* "La dirección de e-mail que usted ha escrito no pertenece a un miembro. Por favor, compruebela otra vez. Para hacerse miembro, haga click en el enlace de la parte derecha de la pantalla". Aunque este texto está en rojo, el texto "Por favor, introduzca su dirección de e-mail" sigue apareciendo en negro. La dirección de e-mail incorrecta que el usuario había escrito originalmente aparecerá rellenando el cuadro de edición. 
Si se había introducido la dirección de e-mail, y corresponde a un miembro registrado, pero no se ha escrito ninguna contraseña, enviamos un e-mail que contenga la contraseña a esa dirección. El asunto del e-mail es "Su afiliación a Musikamania.com". El e-mail estará sólo en texto plano. La redacción exacta de este e-mail todavía es objeto de vivo debate por la junta de directores y será comunicado antes de la entrega. 

- Si se había introducido la dirección de e-mail, y corresponde a un miembro registrado, y se había introducido una contraseña, pero ésta es incorrecta, el servidor devuelve otra página muy parecida al Formulario de entrada, sólo que esta vez, se inserta un mensaje de error en rojo sobre el cuadro de contraseña, diciendo *NOTA:* "La contraseña que usted ha introducido no es válida. Por favor, compruébalo otra vez. Recuerde, en las contraseñas las mayúsculas y minúsculas son letras diferentes". Si la contraseña escrita no contiene ninguna letra minúscula, añadimos este texto al mensaje: "Quizá ha pulsado usted la tecla de TODO MAYÚSCULAS accidentalmente". Siempre que la contraseña sea incorrecta, el Formulario de entrada vuelve a aparecer con el cuadro de contraseña vacío.

- Si la dirección de e-mail y la contraseña están bien, se les cargará otra vez la página principal. En la parte donde aparecía la opción de “Acceso”, ahora aparecerá el icono de una personita y el nombre de usuario con el que el usuario está registrado. De esta manera, indica que ya está dentro de su cuenta de Musikamania. Ahora sí, una vez registrados, pueden navegar libremente y tienen el acceso permitido a todos los contenidos publicados en la página web. Además también contarán con la opción de poder escuchar las canciones que aparecen en las listas.  

##### Si hacen clic en ¿Has olvidado tu contraseña?

Se les conducirá a una página donde se les pida su correo electrónico y una nota arriba del todo de la página.

*NOTA:* Escribe la dirección de correo electrónico que usaste para registrarte y te enviaremos las instrucciones para restablecer tu contraseña.  

![restablecer contraseña](https://github.com/DeustoPWEB2018/proyectoweb-ocio/blob/anejuaristi-estructura/3-estructura/Imágenes/restablecer%20contraseña.jpg)

Cuando hayan escrito su correo electrónico y hagan clic en restablecer contraseña, se les indicará que: 

*NOTA:* Te hemos enviado un correo con los pasos para regenerar tu contraseña

El mensaje del e-mail que reciban en su correo será el siguiente:

![mensaje 1](https://github.com/DeustoPWEB2018/proyectoweb-ocio/blob/anejuaristi-estructura/3-estructura/Imágenes/mensaje%201.jpg)

Cuando hagan clic en el enlace, irán directamente a la página de login y aparecerá una nota arriba de la página:
 
*NOTA:* Email verificado. Le hemos enviado un nuevo correo con las nuevas indicaciones para acceder a Musikamania.com 
 
El mensaje del e-mail que reciban en su correo será el siguiente:

![mensaje 2](https://github.com/DeustoPWEB2018/proyectoweb-ocio/blob/anejuaristi-estructura/3-estructura/Imágenes/mensaje%202.jpg)

Cuando hagan clic en el enlace, irán directamente a la página de login de Musikamania.com

#### Si hacen clic en Regístrate

Si el usuario no está registrado y hace clic en “registrarse ahora”, le aparecerá un formulario de entrada con los siguientes campos:

- Nombre y dos apellidos
- Nombre de usuario
- E-mail
- Contraseña
- Repita la contraseña
- País (estará directamente puesto España, si son de aquí no tendrán que hacer nada, si no son de España tendrán que buscar su país)
		
  *Si eligen España también se les preguntará por la provincia y la localidad. Si ponen algún otro país que no sea España, en el momento que hagan clic en el país van a desaparecer los campos de provincia y localidad.
		
- Provincia (aparecerán todas las provincias de España en una barra y tendrán que hacer clic en la suya)
- Localidad (según la provincia que elijan les aparecerán todos los municipios de esta provincia en una barra y tendrán que hacer clic en la suya.

 *Cuando ponen su municipio aparecerá directamente el código postal 
		
- Año de nacimiento
- Sexo

Por otro lado, también se les preguntará: 

- ¿De qué géneros te gustaría recibir noticias?

	- Música clásica  
	- Rock 
	- Pop
	- Reggaetón 
	- Jazz 
	- Trap 
	- Punk 
	- Rap 
	- Techno 
	- Flamenco 
	- Country 
	- Otro: 
	
  *Si hacen clic en Otro les aparecerá una barra donde podrán escribir el nombre del género que estén interesados

- He leído y acepto los Términos de uso. (aparecerá un cuadrito al lado y tendrán que clicar encima para aceptar. Para ver que ya lo han aceptado aparecerá un tick dentro del cuadrito pequeño).

*NOTA:* Para registrarse es obligatorio aceptar los Términos de uso

- Después de rellenar todos los campos (son obligatorios), hacer clic en Registrarse

Una vez que hayan hecho clic en Registrarse, se les conducirá directamente a la página de login con una nota arriba de la página: 

*NOTA:* Registro exitoso. Ingresa tus credenciales para acceder. 

En este caso volverán a la página de login para acceder a su cuenta mediante el e-mail o el nombre de usuario y la contraseña.

#### Ventajas de los usuarios registrados

- Recibir noticias sobre los géneros musicales que hayan elegido los usuarios a la hora de registrarse

	- Cada vez que se publique cualquier contenido relacionado con el género o géneros que hayan seleccionado al registrarse, se les mandará un e-mail con el siguiente mensaje.
	
	![contenido en redes sociales](https://github.com/DeustoPWEB2018/proyectoweb-ocio/blob/anejuaristi-estructura/3-estructura/Imágenes/contenido%20en%20redes%20sociales.jpg)
	
	- Si hacen clic en el enlace se les conducirá directamente al contenido que se haya publicado en la página.
	
- Opción a ver contenido más desarrollado 

 	- Esto no lo van a notar los usuarios porque una vez que ya se hayan registrado podrán navegar por todas las páginas de la web y les aparecerá siempre todo el contenido.

- Dejar comentarios debajo de nuestros contenidos. 

 	- Cuando dejen cualquier comentario, aparecerá ya escrito el nombre de usuario con el que se hayan registrado en la página web, de modo que no habrá mensajes anónimos. 
	
	 ![dejar comentarios](https://github.com/DeustoPWEB2018/proyectoweb-ocio/blob/anejuaristi-estructura/3-estructura/Imágenes/dejar%20comentarios.jpg)
	 
	- Cuando hagan clic en Comentar, aparecerá el comentario que han escrito con su nombre de usuario debajo del contenido a la que hayan accedido.
  	
- Compartir nuestros contenidos a través de las redes sociales. Tendrán la opción de poder compartirlo a través de Facebook o Twitter. 

 	- Debajo del contenido a la izquierda (antes de los comentarios) aparecerán los logos de Twitter y Facebook.
 	- Cuando hagan click en una de ellas, se les abrirá otra pestaña en el navegador con la dirección de dicho portal. En caso de que tengan la sesión iniciada podrán compartir el link directamente, en caso de que no sea así, tendrán que iniciar sesión y copiar el link ellos mismos o volver a la pestaña de nuestra web y volver a hacer click en el icono de la red social. 
 	- Cuando compartan el contenido en las redes sociales, aparecerán el título y el enlace al contenido.

- Escuchar las listas de las últimas canciones o las más escuchadas de algunos géneros musicales. 

 	- Si no están registrados, les aparecerán todas las listas y los nombres de las canciones, pero no tendrán la opción de escucharlas. Si hacen clic en las canciones, les conducirá directamente a la página de regístrate con una nota arriba del todo de la página. 

*NOTA:* Para escuchar las canciones, es necesario que estés registrado.


- Las personas registradas, cuando hagan clic encima de cualquier canción, ésta se reproducirá automáticamente y aparecerá una barra de reproducción justo debajo para indicar lo siguiente:

 	- Se está reproduciendo la canción y su duración. Si hacen clic encima del logo de pausa (II), se parará automáticamente y el logo se cambiará a la de reproducir (punta de la flecha).
 	- En la duración de la canción, aparecerá una línea en la que se observará el tiempo de la canción. En el extremo izquierdo aparecerá escrito 00.00 y, a medida que la canción avance, se irán añadiendo los segundos y minutos. Sobre la línea temporal aparecerá un botón para saber que parte de la canción se ha escuchado y por donde va. A medida que la rueda avance, la parte que ya se ha transcurrido cambiará a color blanco. En el extremo derecho siempre aparecerá la duración de la canción. 
=======
>>>>>>> 8da73b3fefa873edb23b924b4fd8ca2c675299ed
## Arquitectura de la información
### Card Sorting
#### Metodología card sorting
El diseño de la página web debe estar centrado en el usuario. Para que la ejecución sea exacta, y del agrado de los usuarios es conveniente optar por hacer un trabajo de campo y así acercarse a ellos. Un método muy práctico para ello es el card-sorting. Un método, cuyo fin es servir de guía para diseñar la arquitectura de la información. Consiste en pedir a personas, o grupos crear categorías para agrupar distintos contenidos. Para la ejecución de esta actividad solamente serán necesarias unas tarjetas con etiquetas que harán referencia a distintos contenidos de la web, y unos voluntarios que quieran participar.
#### Muestra
En el card sorting realizado para la página web Musikamania.com, se optó por hacerlo por parejas. En total, han participado seis parejas. Es conveniente que el card sorting se haga en grupo, ya que ambas partes dan su opinión, y pueden llegar o no a un consenso. En consecuencia, posiblemente, interesa más la discusión que el resultado es sí.
#### Tipo de card sorting aplicado
Estas parejas han sido sometidas a realizar un card sorting abierto. Es decir, se les han entregado unas cartas con las etiquetas mencionadas a continuación, y han tenido que agruparlas. Es lógico realizar la prueba abierta, ya que la página web es nueva, y no tiene categorías ya preestablecidas.
#### Etiquetas
Las etiquetas del contenido que se les han ofrecido son los siguientes:
- Lo más escuchado en rock
- Lo mejor del pop
- Lo más escuchado en Spotify
- Lo más viral en Youtube
- Madrid: 21/12/2018, 22:00; Berri Txarrak. Entradas en venta en:
- Barcelona: 20/07/2019; Barcelona Beach Festival. Entradas agotadas
- Todo lo que tienes que saber para ir a Primavera Festival
- Fallece Aretha Franklin, la reina del soul
- Se suspende Tomorrowland por lluvia
- Gatibu presenta su nuevo tema: SALTO!
- Huntza presentará en Durango su nuevo disco
- Comunicado oficial: Vendetta dejará los escenarios
- Su ta Gar, 31 años a fuego
- Letras que duelen
- Un día cualquiera con: Rosalía
- Actuación para enmarcar de Berri Txarrak en los MTV
- Concierto de Gozategi pasado por lluvia
- Crónica e imágenes del concierto de Amaral
- Disco con la guitarra como protagonista: 9 puntos
- El nuevo álbum no cumple con las expectativas: 3 puntos
- Trini Fox: “Lo que empezó como un juego, es nuestra profesión”
- Maluma: “Es mejor no hacer caso a las críticas”
- Historia de Musikamania.com
- Fundadores
- Red de colaboradores

#### Resultados
Pueden verse los resultados obtenidos en la siguiente tabla. Los conceptos que están en horizontal con las categorías que los participantes crearon:
![Resultados](https://github.com/DeustoPWEB2018/proyectoweb-ocio/blob/iodrie-estructura/3-estructura/Resultados.jpg?raw=true)
Vistos los resultados conseguidos gracias al card sorting, cabe destacar que no ha habido grandes discrepancias entre los resultados de las seis parejas participantes. Los resultados más llamativos son los siguientes:
- Tendencia a especificar y dividir las noticias de actualidad en subcategorías. Sorprende la aparición de categorías como presentaciones, crónicas y noticias. Esto demuestra la tendencia a querer encontrar lo que se busca lo más rápido posible, sin perder el tiempo en leer contenidos que no interesan.
- La tendencia a relacionar titulares informativos  con las noticias, y los titulares gancho con los reportajes. Los contenidos titulados diciendo explícitamente lo que cuenta el texto se perciben como noticias puras, y como reportajes los que tienen un titular abierto.
- Poca duda en relacionar titulares con una cita textual con entrevistas. 
- Tendencia a relacionar las valoraciones en los titulares con críticas y reviews. Teniendo en cuenta que el significado de ambos conceptos es el mismo, no cabe duda que las notas puestas de 0 a 10 hacen relacionar al usuario el contenido con opiniones.
- La total relación que hacen los usuarios con la frase “lo más” y las listas. Al leer ese concepto  la mayoría de las parejas no dudó en crear una categoría llamada listas.

### Clasificación de contenidos
En base al Card Sorting que hemos realizado a un grupo de personas que encajan con las características de nuestro público objetivo, hemos decidido clasificar la información de nuestra página web de la siguiente manera:

Clasificación cronológica: El esquema de clasificación seguirá un orden cronológico, ya que hemos observado que los usuarios se decantan por ordenar la información en base a una línea temporal que va de lo más reciente a lo más antiguo. 


Clasificación por tema: Vamos a clasificar la  información en base a unos temas a los que nosotros llamaremos categorías, dentro de las cuales habrá subcategorías a modo de concretar más. De forma más específica, también utilizaremos etiquetas, que serán las palabras clave asociadas a un contenido concreto. 


Las categorías que usaremos son las siguientes:

- Actualidad (Noticias, Crónicas de conciertos y festivales, Crítica de CDs)

- Reportajes

- Entrevistas

- Listas de canciones (Rock, Pop, Reggaeton, Electronica)

- Videoclips 

- Agenda


El uso de las etiquetas, que se añadirán después de haber redactado el contenido, servirá para guiar al usuario al final de cada contenido que consuma.  Por ejemplo, si un usuario lee una noticia sobre un grupo de rock y ve la etiqueta “punk rock”, podrá enlazar la noticia que acaba de leer con cualquier otro contenido de la página que lleve esa misma etiqueta. 

Jerarquía de arriba a abajo (anchas y superficiales): Este enfoque nos ha parecido el más adecuado ya que nos permite tener un esquema temático a la hora de redactar el contenido que mostraremos en la página web, además la mayoría de los usuarios prefieren tener las categorías en la página de inicio y que éstas puedan desplegarse mostrando las subcategorías. Las etiquetas se añadirán posteriormente, el redactor del contenido tendrá la opción de elegir aquellas que ya estén creadas o bien crear una nueva en base a las necesidades que presente dicho contenido. Éstas aparecerán solo al final del contenido, aunque el usuario podrá buscar la etiqueta en el buscador desde la página de inicio en caso de que ya sepa que quiere leer nada más entrar. Al final de cada contenido también aparecerán los iconos sociales de Twitter y Facebook. 


Al final de la página de inicio, habrá un enlace a varias páginas estáticas con información de contacto, publicidad y  quienes somos. Al final del todo también aparecerán los derechos de la página, de su diseño y de su contenido.

### Diagrama
![Diagrama](https://github.com/DeustoPWEB2018/proyectoweb-ocio/blob/iodrie-estructura/3-estructura/diagrama.jpg?raw=true)

