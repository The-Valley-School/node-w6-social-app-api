# WORKSHOP 6 - API de Red Social

¡Hola! Para este Workshop, el enunciado no será guiado como en otras ocasiones. Pero no te preocupes, estamos aquí para guiarte y ayudarte en todo lo que necesites.

Debes tener en cuenta que, en el mundo profesional, cuando debes desarrollar una API, nadie te indicará de forma precisa todo lo que debes hacer. Pero no te preocupes, ¡tú eres capaz de hacerlo!

Teniendo esto en cuenta, te proporcionaremos toda la información que necesitas para comenzar. Aquí te dejamos una lista de los requerimientos de la API que debes crear para una aplicación de una red social:

- Crear las entidades necesarias
- Validar los campos correspondientes
- Crear todos los endpoints necesarios
- Usar las librerías que consideres necesarias

¡Ánimo! Estamos seguros de que lo harás genial.

**REGISTRO**

![Untitled](/assets/Untitled.png)

Un usuario debe poder registrarse indicando nombre y apellido, email, contraseña, fecha de nacimiento y género.

Todos los campos son obligatorios.

**LOGIN**

![Untitled](/assets/Untitled%201.png)

Por supuesto, si hay un registro habrá un login… un usuario podrá hacer login con su usuario y contraseña

**BÚSQUEDA DE PERSONAS**

![Untitled](/assets/Untitled%202.png)

Una vez ha hecho login, el usuario podrá buscar personas por su nombre.

En caso de que sean amigos podrá consultar su perfil, en caso de que no lo sean sólo podrá enviarle una solicitud de amistad.

**DETALLE DE UN AMIGO**

Si el usuario está logado e intenta consultar la información de una persona, podrá ver:

Publicaciones:

![Untitled](/assets/Untitled%203.png)

Información

- Correo
- Fecha de nacimiento
- Género

![Untitled](/assets/Untitled%204.png)

Amigos:

![Untitled](/assets/Untitled%205.png)

**ENVIAR SOLICITUD DE AMISTAD:**

![Untitled](/assets/Untitled%206.png)

A la hora de ver a una persona que no es un amigo, solo podrás consultar su nombre y mandarle una solicitud, en la solicitud podremos adjuntar un texto.

Una persona podrá ver sus solitudes de amistad pendientes tanto enviadas como recibidas.

En caso de las enviadas podrá cancelarlas y en las recibidas podrá rechazarlas o aceptarlas.

**CREAR UNA PUBLICACIÓN**

Los usuarios logados podrán crear publicaciones, en una publicación se podrá indicar un texto y adjuntar imágenes.

![Untitled](/assets/Untitled%207.png)

Sobre una publicación, nuestros amigos podrían darle like.

**CREAR UN GRUPO**

Un usuario logado podrá crear un grupo. Un grupo tendrá un titulo, una foto y una lista de usuarios.

![Untitled](/assets/Untitled%208.png)

El usuario que crea el grupo será el administrador. 

Un usuario cualquiera puede unirse al grupo y podrá crear una publicación, pero las publicaciones deben ser aprobadas por el administrador para que puedan verlas los demás.

Las publicaciones son públicas por defecto.

**EXTRAS**

- Añade un endpoint para ver tu muro: en tu muro verás las publicaciones más recientes de tus amigos y de los grupos a los que perteneces
- Añade un usuario admin que pueda hacer todas las operaciones
- Añade ubicación a las personas, de manera que se puedan buscar amigos por ciudad o por país.
- Cuando un usuario cree una publicación podrá marcar si es publica o privada.
- Añade la posibilidad de etiquetar a tus amigos en las publicaciones
