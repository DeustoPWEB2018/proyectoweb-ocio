# Plano de estructura
## Diseño de la interacción

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
		- Si eligen España también se les preguntará por la provincia y la localidad. Si ponen algún otro país que no sea España, en el momento que hagan clic en el país van a desaparecer los campos de provincia y localidad.
		
- Provincia (aparecerán todas las provincias de España en una barra y tendrán que hacer clic en la suya)
- Localidad (según la provincia que elijan les aparecerán todos los municipios de esta provincia en una barra y tendrán que hacer clic en la suya.
		- Cuando ponen su municipio aparecerá directamente el código postal 
		
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
				- Si hacen clic en otro les aparecerá una barra donde podrán escribir el nombre del género que estén interesados

- He leído y acepto los Términos de uso. (aparecerá un cuadrito al lado y tendrán que clicar encima para aceptar. Para ver que ya lo han aceptado aparecerá un tick dentro del cuadrito pequeño).
		*NOTA:* Para registrarse es obligatorio aceptar los Términos de uso

- Después de rellenar todos los campos (son obligatorios), hacer clic en Registrarse

Una vez que hayan hecho clic en Registrarse, se les conducirá directamente a la página de login con una nota arriba de la página: 

*NOTA:* Registro exitoso. Ingresa tus credenciales para acceder. 

En este caso volverán a la página de login para acceder a su cuenta mediante el e-mail o el nombre de usuario y la contraseña.

#### Ventajas de los usuarios registrados

## Arquitectura de la información
### Card Sorting
### Clasificación de contenidos
## Referencias
