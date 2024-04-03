<h1> Sistema de Registro </h1>
- Estado del proyecto: En construcción.

Para ejecutar el sistema, debes poner:

```npm install react```

No existe regla especifica para hacer commits, pero se recomienda usar el imperativo al comienzo de los commits.
Sin embargo cada empresa puede hacer uso de una sintaxix estándar.

# Git clone #

El comando git clone es usado para seleccionar un repositorio existente y crear un clon o una copia de él en un repositorio local.

Además puede crear una copia de un repositorio git existente, y este repositorio puede ser local o remoto.
 
Esta copia es un repositorio git completo, con tu propio historial, gestionamiento de tus propios archivos y es un ambiente aislado como un todo del repositorio original. 

Con el git clone también puedes clonar el repositorio para una carpeta específica:

```git clone <repositorio> <mi-proyecto-clone>```

También puedes configurar el git clone y clonar el repositorio desde una branch específica, diferente a la original, de esta manera:

```git clone -branch new_feature <repositorio>```

# Git log #

Git log te ayuda a verificar el historial de cambios, los mensajes de commit, el nombre de la persona autora y otras informaciones sobre el proyecto.

Tambien podemos ver los hashs inherentes de cada commit.

Con el siguiente comando podemos observar alteraciones del commit:

``` git log -p ``` 

Buscar información de la persona autora del commit con el comando:

``` git log -author="user_name" ``` 

Buscar información por fecha:

``` git log --since=1.month.ago --until=1.day.ago ``` 

Formatear la visualización de las informaciones del commit, este a su vez trae el hash seguido del mensaje de commit, y es con el comando:

``` git log --pretty="format:%h %s" ``` 

# Git pull #

Bajar los cambios realizados en el repositorio remoto al repositorio local

``` git pull" ``` 

# Git add #

Agregar las nuevas modificaciones realizadas en el código al repositorio local.

``` git add ." ``` 

# Git commit #

Almacenar los cambios que ha realizado en el repositorio local.

``` git commit -m "name" ``` 

# Git push #

Enviar los cambios realizados en el repositorio local al repositorio remoto.

``` git push" ``` 

# Git diff #

Permite observar los cambios entre codigo anterior y posterior a un commit  

