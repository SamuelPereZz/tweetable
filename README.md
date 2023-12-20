# Tweeteable

Tweeteable es una simulación de Twitter (X) desarrollada con Ruby on Rails y utilizando el patrón de arquitectura de software MVC (Modelo-Vista-Controlador). Esta aplicación replica las principales funciones de Twitter, incluyendo la publicación de tweets, la posibilidad de comentar y dar "me gusta" a los tweets, y la gestión de perfiles de usuario. Además, implementé un sistema de inicio de sesión utilizando GitHub, permitiendo a los usuarios crear nuevas cuentas.

## Vista previa de la aplicación

 ![Home Tweeteable Image](https://i.imgur.com/wd5fPuD.png)
 
# Características Destacadas

### Interactividad Similar a Twitter

- **Likes y Comentarios**: Experimenta la misma emoción de Twitter al dar likes y comentar en los tweets. La interactividad es clave, y en Tweetable, hemos replicado esa experiencia a la perfección.

 ![Likes y comentarios Tweeteable Image](https://i.imgur.com/Ki1hIc0.png)

- **Exploración de Perfiles**: Exploración de Perfiles: Sumérgete en la red social explorando perfiles de usuarios. Descubre quiénes son, qué están tuiteando y mantente conectado con tus seguidores y seguidos.

 ![Home Tweeteable Image](https://i.imgur.com/NZDEuTf.png)

- **Flujo de Actividad Personalizado**: Accede a tu propio perfil para revisar y revivir tus tweets antiguos, así como aquellos en los que has sido mencionado. Tweetable pone tu actividad al alcance de tu mano.

 ![Home Tweeteable Image](https://i.imgur.com/3EqtUIr.png)

# Configuración Rápida

Para sumergirte en la magia de Tweetable, sigue estos sencillos pasos:

1. **Clonar el repositorio**: Comienza clonando el repositorio en tu máquina local:

   ```shell
   git clone git@github.com:SamuelPereZz/tweetable.git
   cd tweetable
   ```


2. **Verificar tu versión de Ruby**: Asegúrate de tener la versión correcta de Ruby instalada (3.1.2):

   ```shell
   ruby -v
   ```      
   Si no tienes la versión correcta, puedes instalarla utilizando rbenv:
   
   ```shell
   rbenv install 3.1.2
   ```
   
4. **Instalar las dependencias**: Ejecuta el siguiente comando para instalar las dependencias necesarias:

   ```shell
   bundle install
   ```

5. **Inicializar la base de datos**: Prepara la base de datos para la acción:

   ```shell
   rails db:create db:migrate db:seed
   ```

6. **Iniciar el servidor**: Lanza el servidor de Tweetable y comienza tu viaje de microblogging:

   ```shell
   rails s
   ```

