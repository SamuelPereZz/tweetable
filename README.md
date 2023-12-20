# Tweetable

Tweetable es una emocionante simulación de Twitter que ha sido desarrollada con el poderoso framework `Ruby on Rails` para el backend y HTML/CSS para el frontend. Esta aplicación reproduce con éxito todas las características clave de Twitter, brindando a los usuarios una experiencia auténtica en el mundo del microblogging.

## Características Destacadas

### Interactividad Similar a Twitter

- **Likes y Comentarios**: Experimenta la misma emoción de Twitter al dar likes y comentar en los tweets. La interactividad es clave, y en Tweetable, hemos replicado esa experiencia a la perfección.

- **Exploración de Perfiles**: Exploración de Perfiles: Sumérgete en la red social explorando perfiles de usuarios. Descubre quiénes son, qué están tuiteando y mantente conectado con tus seguidores y seguidos.

- **Flujo de Actividad Personalizado**: Accede a tu propio perfil para revisar y revivir tus tweets antiguos, así como aquellos en los que has sido mencionado. Tweetable pone tu actividad al alcance de tu mano.
 
## Vista previa de la aplicación

![Imagen de la aplicación](./images/app-preview.png)

## Configuración Rápida

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

