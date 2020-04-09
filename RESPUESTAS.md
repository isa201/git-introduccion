#***¿Que es git?***

----------


*Es un sistema de control de versiones.Controla y administra las distintas versiones de un programa.Es utilizado para proyectos que van a ir cambiando y creciendo a medida que pasa el tiempo.Es decir se pueden controlar los cambios o modificaciones que se van realizando a medida que avanza el proyecto en el que se esta trabajando.*    
  
####***¿Por que utilizarlo?***  

*Porque facilita el trabajo no solo individual, sino que tambien colectivamente ayuda a cordinar con otros desarrolladores que esten trabajando en el mismo proyecto desde cualquier parte.Se pueden tener registros de los cambios o aportes hechos por los demas y ademas revertir los cambios hechos en el caso de que sea necesario.*   

####***El bash de git***

*El git bash, es una herramienta de tipo consola que básicamente permite manipular y gestionar todo el proceso a realizar con el proyecto.*

####***Estados en GIT***
* * *

- **Working directory**: es donde se trabaja con los archivos 

- **Stagin area**: es donde se agregan todos los archivos que se preparan para el guardado.

- **Repository**: es donde se almacenan los archivos con los cambios ya guardados.  

* * *

####***Crear un nuevo repositorio en git***

- ***1)**  Se debe iniciar el bash de git acceder a la carpeta de nuestro proyecto y una vez estando en la direccion inicializar un nuevo repositorio con el comando ***git init***.*  
 
- ***2)** Podemos consultar los archivos que tenemos agregados a nuestro entorno de trabajo (stagin area) con el comando ***git status****. 
 
- *3) Si no tenemos los archivos que necesitamos los podemos agregar con el comando ***git add*** seguido del nombre del archivo*.  
  
- ***4)** Luego con el comando ***git commit*** guardamos los cambios realizados, aqui podemos agregar tambien un comentario y se almacenara todo en el repositorio.*

- ***5)** Si hemos almacenado mas de un cambio en el repositorio, con el comando ***git log*** podemos ver todos estos en orden, con los datos de quien lo realizo y los comentarios que se hicieron.Si se quiere revertir un cambio realizado, el comando ***git chekout --*** seguido del nombre del archivo, nos permite realizarlo y volver a un estado anterior.*  
 
- ***6)** Y por ultimo en el caso de que quisiera agregar los nuevos cambios, deberia volver a usar un ***git add*** y subirlo al repositorio con el ***git commit***.*

####***Ignorar archivos*** 

*Para ignorar archivos o carpetas debemos crear un archivo que se llame .gitignore, dentro del mismo colocar el nombre de los archivos y las carpetas que quiero ignorar.Una vez hecho esto debo agregarlo al entorno de trabajo(stagin area) con el comando **git add** y por ultimo subirlo al repositorio con el ***git commit***.*

####***git branch***

*Podemos crear una version alternativa o rama de nuestro codigo.Para hacerlo usamos el comando ***git branch*** + el nombre de la version.Para seleccionar esta version usaremos el comando ***git checkout*** seguido del nombre de la misma.En esta version creada tambien podremos agregar archivos con el comando add,ademas otra forma de agregarlos es con el comando ***git add.***  , este comando agrega directamente todos los archivos nuevos sin tener que ir uno por uno.*

*La siguiente imagen muestra como se crea otra version llamda miRama y se seleciona con el comando git branch y checkout.*

![](https://i.ytimg.com/vi/GokGokPSZlM/maxresdefault.jpg)



























