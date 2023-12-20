# Tweetable

Tweetable es una simulación de Twitter, desarrollada utilizando `Ruby on Rails` para el backend y HTML/CSS para el frontend. Todas las características principales de Twitter fueron replicadas con éxito, proporcionando a los usuarios una experiencia similar.

## Vista previa de la aplicación

![Imagen de la aplicación](./images/app-preview.png)

## Empezando

Para sumergirte en la magia de Tweetable, sigue estos sencillos pasos:

1. **Clonar el repositorio**: Comienza clonando el repositorio en tu máquina local:

   ```shell
   git clone git@github.com:SamuelPereZz/tweetable.git
   cd tweetable
   ```


2. **Verificar tu versión de Ruby**: Asegúrate de tener la versión correcta de Ruby instalada (3.1.2):

   ```shell
   ruby -v
   rbenv install 3.1.2
   ```      
Si no tienes la versión correcta, puedes instalarla utilizando rbenv:

   ```shell
   rbenv install 3.1.2
   ```      

3. **Instalar las dependencias**: Ejecuta el siguiente comando para instalar las dependencias necesarias:

   ```shell
   bundle install
   ```

4. **Inicializar la base de datos**: Prepara la base de datos para la acción:

   ```shell
   rails db:create db:migrate db:seed
   ```

5. **Iniciar el servidor**: Lanza el servidor de Tweetable y comienza tu viaje de microblogging:

   ```shell
   rails s
   ```

