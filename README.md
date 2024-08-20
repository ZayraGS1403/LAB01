 # LABORATORIO 01
“INTEGRANTES
Andres Serrato
Zayra Gutierrez

 ### PARTE I (Trabajo Individual).
1. Crea un repositorio localmente.
  
![alt text](<Screenshot 2024-08-17 104808.png>)

2. Agrega un archivo de ejemplo al repositorio, el README.md puede ser una gran opción.
![alt text](<Screenshot 2024-08-17 105046.png>)

3. Averigua para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”

git add: Mueve los cambios del directorio de trabajo al área del entorno de ensayo

git commit: captura una instantánea de los cambios preparados en ese momento del proyecto.

4. Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional

![alt text](image.png)

5. Crea un repositorio en blanco (vacío) e GitHub.

![alt text](image-1.png)

6. Configura el repositorio local con el repositorio remoto.

git commit -m "first commit"

![alt text](image-2.png)
![alt text](image-3.png)

7. Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3 Utiliza los siguientes comando en el directorio donde tienes tu proyecto.

![alt text](image-4.png)

8. Configura el correo en git local de manera correcta

![alt text](image-5.png)

9. Vuelve a subir los cambios y observa que todo esté bien en el repositorio remoto (en GitHub).
dsad

Todo esta perfecto en el repositorio.

### Parte II (Trabajo en Parejas)

1. Se escogen los roles para trabajar en equipo, una persona debe escoger ser "Owner" o Propietario del repositorio y la otra "Collaborator" o Colaborador en el repositorio.

el owner será el repositrio de Zayra y el colaborador será Andres.
![alt text](image-7.png)

![alt text](image-6.png)


2. El owner agrega al colaborador con permisos de escritura en el repositorio que creó en la parte 1

![alt text](<Screenshot 2024-08-17 113651.png>)

4. El colaborador acepta la invitación al repositorio

![alt text](image-9.png) 

5. Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo.


6. que sucedio ?
salto el siguiente error que genero un conflicto de la fusion con la linea de comando

![alt text](image-7.png)

8. Volver a repetir un cambio sobre el README.md ambas personas al tiempo para volver a tener conflictos.

![alt text](<Screenshot 2024-08-17 121549.png>)

9. Resuelvan el conflicto con IntelliJ si es posible, Resolver conflictos en Visual

![alt text](<Screenshot 2024-08-17 121614.png>)


### PARTE III (Trabajo de a parejas)

1. ¿Hay una mejor forma de trabajar con git para no tener conflictos?
Si, utilizando las ramas se evitan los conflictos o haciendo pull request.

2. ¿Qué es y como funciona el Pull Request?

Un pull request es una petición que el propietario de un fork de un repositorio hace al propietario del repositorio original para que este último incorpore los commits que están en el fork. En el caso que nos ocupa, el usuario  le enviará la petición  para que este último incorpore los commits que tiene en su fork.

3. Creen una rama cada uno y suban sus cambios
   
![alt text](image-10.png)

![alt text](image-11.png)

4. Tanto owner como colaborador hacen un cambio en el README.md y hacen un Pull Request (PR) a la rama main/master

![alt text](image-12.png)

5. Teniendo en cuenta la recomendación, mezclen los cambios a la rama main a través de PR con el check/review/approval del otro compañero (Cuando se hace merge se deberían borrar las ramas en github)

![alt text](image-13.png)

![alt text](image-11.png)
![alt text](image-12.png)
![alt text](image-10.png)
