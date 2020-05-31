# Cian
Proyecto Final, DAM.

[Vídeo Explicativo 19-03-2020](https://youtu.be/zaqWnU6Uq5k)

Tanto la APK como el vídeo explicativo checkpoint (10-05-2020) están en el repositorio de la propia [app](https://github.com/rubenpachecomatas/Cian-App).

Cian App - [Aquí](https://github.com/rubenpachecomatas/Cian-App)

Cian Web - [Aquí no]()

Cian Back - [Aquí](https://github.com/rubenpachecomatas/Cian-Back)

Cian DB  - [Aquí](https://github.com/rubenpachecomatas/Cian-DB)


# Diario de Trabajo

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



