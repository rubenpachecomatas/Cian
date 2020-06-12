<p align="center">
  <img src="https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/saturncian.png" width="150">
</p>

<h1 align="center">CIAN</h1>
<h4 align="center">Creativity in a Nutshell</h4>
<br>

## Índice

  - ¿Qué es Cian?
  - ¿Cómo funciona?
  - Cian App
  - Cian Back
  - Cian Web
  - Cian Database
  - Diario de desarollo
  
<br>

## ¿Qué es Cian?

Cian es una red social enfocada en fomentar la creatividad de los usuarios. O, al menos, esa fue la idea con la que nació. Porque Cian no busca traer algo nuevo y novedoso, solo prestarle la atención que se merece a algo muy importante y que tendemos a encerrar en nosotros mismos. Cian te proporciona un espacio donde compartir tus ideas en busca de esa ayuda extra que se necesita para desarrollarlas. Ya seas un estudiante como yo al que no se le ocurría que podría hacer con su proyecto final, un escritor que es incapaz de ver más haya de sus palabras, o simplemente una persona que está cansada de rendirse por miedo a que sus ocurrencias solo sean buenas para él, Cian podría ser eso que necesitabas y aún lo sabías. O no. Pero no hablamos de esas veces.

[Videotutorial de uso](https://youtu.be/JazWH483ARA)

[Presentación en formato PDF](https://github.com/rubenpachecomatas/Cian/blob/master/TFG%20CIAN.pdf)

[Presentación en formato Power Point](https://github.com/rubenpachecomatas/Cian/blob/master/TFG%20CIAN.pptx)

<br>

## ¿Cómo funciona?

### Welcome

Esta es la primera página que nos encontramos al entrar a la app. Te permite navegar a las páginas de Login y Register o cambiar el idioma predeterminado.

![welcome](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/welcome_page.png)
![welcome-lang](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/welcome_page_language.png)

### Login and Register

No tienen mucho misterio. Introduce email y contraseña para iniciar sesión o registrarte.

![login](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/login_page.png)
![register](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/register_page.png)

### Recover

En la página de login teníamos la opción de recuperar nuestra contraseña en caso de perdida. Metes tu email y te llegará un correo de recuperación.

![recover](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/recover_page.png)

### Home

El corazón de la app. Nos encontramos unos cuantos scrolls horizontales de diferentes categorías, cargando hasta 8 posts de cada una (en caso de querer ver más pulsaríamos el botón al final de cada scroll para navegar a la página de posts (explicada más abajo). Podemos ver las últimas publicaciones, las más gustadas de la semana, las publicaciones de los usuarios a los que seguimos, y, si seguimos bajando, cargará poco a poco más categorías en función de lo usadas que sean. También tenemos un botón de una lupa con una tag en la esquina superior derecha. Al pulsarlo abrirá un popover con el componente Filter Tags, que nos permitirá buscar una categoría en concreto. En la parte inferior tenemos una barra de tabs que nos permitirá navegar a las páginas de notificaciones, chats, biblioteca, perfil y crear una nueva publicación.

![home](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/home_page.png)

### New Post

Es sencillo. Intruduce el título, la descripción y asígnale categorías. Ya tienes tu nuevo post.

![new-post](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/new_post_page.png)

### Profile and Visitor Profile

Dos páginas muy parecidas pero con sutiles diferencias. En ambas encontraremos las publicaciones del usuario, el número de seguidores, seguidos y likes que ha dado, además de la foto y el nombre. En cambio, en nuestro perfil el botón que aparece en la esquina superior derecha servirá para desplegar un menú del que hablaremos más adelante. En la página de visitante tendremos un icono que nos llevará a la página de chat para, pues eso, hablar con el usuario. Además en la parte inferior tendremos un botón flotante que desaparecerá al bajar y aparecerá a subir haciendo uso del scroll. En el tendremos las opciones de seguir/dejar de seguir al usuario y volver a casa. Por cierto, las imágenes de perfil son generadas a través de una api externa, en base al nombre. Y están bien chulas.

![profile](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/profile_page.png)
![visitor-profile](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/visitor_profile_page.png)

### Post Details

En Post Details tendremos la vista de una publicación, con el título, descripción y categorías que le hayamos dado. Si eres el autor además encontrarás dos botones, uno de ellos para modificar y otro para borrar. Debajo tendremos la sección de comentarios, donde podremos dejar ideas u opiniones que el creador de la publicación podrá descartar (borrar) o aprobar (resaltar). Cada comentario además nos dejará navegar al perfil de su creador. Y, también en la parte de abajo, volvemos a contar con un botón flotante de comportamiento similar al de las páginas de perfil, solo que este nos dejará ver el número de likes (y una lista con los respectivos usuarios pulsándolo), y en vez de seguir tendremos la opción de dejar o quitar nuestro propio like.

![post-details](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/post_details_page.png)
![comments-options](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/comments_options.png)

### Chats and Chat

En la página de chats nos encontraremos una lista de tarjetas correspondientes a conversaciones que ya hayamos entablado. Podremos ver la imagen de perfil del usuario, el nombre, el último mensaje (que saldrá en azul en caso de no haberlo leído) y cuanto hace que fue mandado. Entrando en la página de uno de los chats nos encontraremos la lista de mensajes (los nuestros a la derecha y los de la persona con la que estemos hablando a la izquierda), cada uno con la hora a la que fue mandado. En el caso de nuestros mensajes también podremos ver un doble check en caso de que la otra persona lo hubiese leído.

![chats](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/chats_page.png)
![chat](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/chat_page.png)

### Notifications

Cada vez que alguien nos siga, comente una de nuestras publicaciones o le de like, se añadirá una notificación a nuestra lista, estando ordenadas por fecha. Si abriesemos una de ellas pasaría a verse más transparente para indicar que la hemos visto.

![notification](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/notifications_page.png)

### Library

En este momento solo muestra tus publicaciones favoritas (Aquellas a las que has dado like), pero en un futuro me gustaría implementar el crear tus propias colecciones de publicaciones.

![library](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/library_page.png)

### User List

La lista de usuarios es usada para mostrar las personas que te siguen, a las que sigues o las que han dado like a una publicación. También puedes ver quien sigue y a quien sigue otro usuario. Si pulsas en una de las tarjetas te llevará a su perfil.

![library](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/user_list_page.png)

### Posts

Tiene un funcionamiento similar a la lista de usuarios. Carga las publicaciones de una categoría, no todas de golpe claro, de 8 en 8 según el usuario baja haciendo uso del scroll.

![library](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/posts_page.png)

### Menu

Menu con opciones de usuario e información al que accederemos desde nuestro perfil (Botón esquina derecha). Nos permitirá cerrar nuestra sesión, cambiar el idioma predeterminado y acceder a las páginas que se explican a continuación.

![menu](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/menu_component.png)

### Account Settings

Nos permite modificar tanto nuestro nombre (inicialmente sacado del email) como nuestra contraseña, así como borrar la cuenta permanentemente.

![settings](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/settings_page.png)

### About

Página de información con enlaces a mi perfil de github y linkedn, además de una lista con las atribuciones de todas las ilustraciones, iconos y demás usados en la app que no me pertenecen.

![about](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/about_page.png)
![attributions](https://github.com/rubenpachecomatas/Cian/blob/master/ASSETS/attributions_about_page.png)

<br>

## Cian App

Repositorio de la aplicación, hecha en Ionic 5. Contiene la APK. - [Aquí](https://github.com/rubenpachecomatas/Cian-App)

<br>

## Cian Web

Repositorio de la landing page, hecha para el módulo Desarrollo de interfaces. Todo lo que se necesita saber está dentro. - [Aquí](https://github.com/rubenpachecomatas/Cian-Web)

<br>

## Cian Back

Tanto el back como la base de datos están desplegados en Heroku, pero puedes encontrar el código aquí. - [Aquí](https://github.com/rubenpachecomatas/Cian-Back)

<br>

## Cian DB

Cian usa dos bases de datos. Realtime database de Firebase, para las notificaciones, chats e información más personal del usuario, y PosgreSQL, para el resto de cosas básicamente. Cuenta con 7 tablas (Users, Follows, Posts, Posts_Tags, Tags, Comments y Likes), y como he dicho arriba se encuentra desplegada en Heroku. Esto debería cubrir el módulo Sistemas de gestión empresarial. - [Aquí](https://github.com/rubenpachecomatas/Cian-DB)

<br>

# Diario de Desarrollo

[Vídeo Explicativo 19-03-2020](https://youtu.be/zaqWnU6Uq5k)

Tanto la APK como el vídeo explicativo checkpoint (10-05-2020) están en el repositorio de la propia [app](https://github.com/rubenpachecomatas/Cian-App).

# Viernes 27-03

✨ Cosas en las que he perdido el tiempo.

  - Proyecto creado.

  - Estructura de carpetas.

  - Servicio de autenticación. Incluye login, registro, logout, recuperación de contraseñas y un método para sacar toasts con los errores.

  - Páginas de bienvenida, login, registro y home provisionales.
  
📚 ¿Bibliografía?

  - [AngularFire](https://github.com/angular/angularfire) 🔥
 
# Viernes 03-04

✨ Cosas en las que he perdido el tiempo.

  - Un SideMenu para la app SÚPER guay (En un componente aparte).

  - Página de Perfil, aunque por ahora solo muestra tu información de usuario.

  - Imágenes de perfil predeterminadas en base al nombre (creo que hay hasta 5000 posibilidades, se supone que tienen que ser adorables pero algunas dan un poco de miedo) para cada usuario.

  - Base de datos PostgreSQL creada con pgAdmin, aunque aún faltan por crear bastantes tablas.
  
📚 ¿Bibliografía?

  - [AngularFire](https://github.com/angular/angularfire) 🔥
  
# Viernes 17-04

✨ Cosas en las que he perdido el tiempo.

  - He remodelado las páginas Welcome, Login, Register, Home (Aún sin terminar) y Profile (Le queda poquito), además de todos los componentes (dialogs, menus...).

  - Cambios en el sistema de navegación. Básicamente ahora hay una barra de tabs, el sidemenu solo se usa en una página.

  - Creación del Backend con express. No tiene mucho, solo lo he conectado a la base de datos y he hecho un par de llamadas de prueba, parece que tira.
  
📚 ¿Bibliografía?

  - [Express](https://expressjs.com/) :running:
  
# Domingo 26-04

Para esta semana no hay mucho.

✨ Cosas en las que he perdido el tiempo.

  - Bug que congelaba la app al usar el menu lateral que usa la página de perfil arreglado.

  - Un par de tablas creadas en la base de datos, más información en el respectivo repositorio.

  - Servicio para las llamadas al back en ionic, ya estaría todo conectado aunque estoy teniendo algunos problemas tontos. **De los que te quitan las ganas de existir**.
  
  
📚 ¿Bibliografía?

  - Nada en especial, solo stackoverflow y algunos de mis proyectos anteriores para las dudas. 🤠
  
# Domingo 03-05

Más rediseño que otra cosa.

✨ Cosas en las que he perdido el tiempo.

  - El diseño de la página de home está cerquita de estar terminado, y digo cerquita porque conociéndome habrá cosas que cambie y vuelva a cambiar. Está quedando bien chulo.

  - Página para añadir nuevas publicaciones.

  - Componente para añadir tags a la publicación, un popover con una barra de búsqueda.
  
  - Pipe para filtrar tags.
  
  - Transiciones entre Home y New-post.
  
  - Cambios menores en el estilo del sidemenu usado en el perfil.
  
  - Ahora el perfil muestra los datos del usuario almacenados en Posgre.
  
📚 ¿Bibliografía?

  - Podría decir la documentación de Ionic, pero supongo que se da por hecho. Por si [acaso](https://ionicframework.com/docs/). 💝
  
# Domingo 10-05

✨ Cosas en las que he perdido el tiempo.

  - Llamadas del backend para añadir tanta las nuevas publicaciones como sus respectivos posts.

  - Control de errores en registro y creación de publicaciones.

  - Últimas 10 publicaciones en la página principal.
  
  - Página que va cargando todas las publicaciones de una categoría por un scroll infinito.
  
  - Base de datos rediseñada.
  
📚 ¿Bibliografía?

  - Podría decir la documentación de Ionic, pero supongo que se da por hecho. Por si [acaso](https://ionicframework.com/docs/). 💝

# Domingo 17-05

✨ Cosas en las que he perdido el tiempo.

  - Publicaciones del usuario en el perfil.
  
  - Layout de la página para modificar datos de tu cuenta.
  
  - Avance en el layout de la página de detalles de una publicación.
  
📚 ¿Bibliografía?

  - Podría decir la documentación de Ionic, pero supongo que se da por hecho. Por si [acaso](https://ionicframework.com/docs/). 💝
  
# Domingo 24-05

✨ Cosas en las que he perdido el tiempo.

  - Filtro por categorías en Home.
  
  - Ahora se puede cambiar el nombre, la contraseña y borrar la cuenta desde la página de Settings.
  
  - En Home se cargan varias publicaciones de las categorías más usadas haciendo uso del scroll.
  
  - La página de detalles permite al autor borrar la publicación.
  
  - Cambios en el sistema de navegación.
  
📚 ¿Bibliografía?

  - Podría decir la documentación de Ionic, pero supongo que se da por hecho. Por si [acaso](https://ionicframework.com/docs/). 💝
  
# Domingo 31-05

✨ Cosas en las que he perdido el tiempo.

  - Editar publicaciones.
  
  - Ahora se pueden comentar las publicaciones, teniendo esos comentarios varias opciones como aprobar (si eres el autor del post), borrarlo o visitar el perfil de la persona que lo comentó.
  
  - Página de perfil completamente remodelada, ha quedado super chula.
  
  - Página para visitar otros perfiles.
  
  - Botón flotante que se oculta o se muestra dependiendo de en que dirección estés scrolleando para las páginas de post-details y visitor-profile, teniendo las opciones de dar me gusta (o quitarlo en caso de haberlo dado), mostrar la lista de personas que han dado me gusta, seguir a la persona (o dejarla de seguir) y volver a la pantalla principal.
  
  - Y, como pone arriba, ahora se puede dar me gusta a las publicaciones y seguir a otros usuarios.
  
  - Página para mostrar listas de usuarios (se usa para seguidos, seguidores y me gustas).
  
  - Categoría Trending funcional (En función de los me gusta en un periodo de tiempo).
  
  - Todas las llamadas al back-end que implica todo eso, que no son pocas.
  
  - Todas las tablas de la base de datos que implica eso, que no son tantas.
  
  - Paleta de colores actualizada, haciendo justicia al nombre.
  
📚 ¿Bibliografía?

  - Podría decir la documentación de Ionic, pero supongo que se da por hecho. Por si [acaso](https://ionicframework.com/docs/). 💝

# Domingo 08-06

✨ Cosas en las que he perdido el tiempo.

  - Traducción Inglés-Español.
  
  - Página de notificaciones.
  
  - Página de la biblioteca (Publicaciones favoritas).
  
  - Página de Información / Créditos.
  
  - Categoría Siguiendo (Muestra las publicaciones de la gente a la que sigues).
 
  - Ícono y Splash de la app.
  
📚 ¿Bibliografía?

  - Podría decir la documentación de Ionic, pero supongo que se da por hecho. Por si [acaso](https://ionicframework.com/docs/). 💝


