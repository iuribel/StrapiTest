
Video de prueba del programa:
https://drive.google.com/file/d/180znXVeE4ks6Om2_hXt1txOBnwI5I-nB/view?usp=sharing

Instrucciones:
1. clonar este proyecto en alguna carpeta de su computador 
2. Crear una base de datos en PostgreSQL llamada "users"
3. 4. Abrir el proyecto en visual estudio 
4. Actualizar las credenciales de la base de datos en el archivo dentro del repositorio para que no tengan problemas al correr el proyecto, en la imagen se muestra el archivo y la ubicación dentro del repo.
![image](https://user-images.githubusercontent.com/38962063/194182745-1b0cf509-46fa-4917-b374-a08b63540c21.png)
![image](https://user-images.githubusercontent.com/38962063/194189243-7688f989-65ea-4e15-aaad-4d7f7fcb354e.png)

5. Abrir el termial de comandos y escribir el comando "npm run develop"
![image](https://user-images.githubusercontent.com/38962063/194183138-4ee2b5fd-d5ae-4cd1-877d-64b7567c37d9.png)
6. el servidor va a correrse automaticamente si no hay conflictos con las credenciales de la base de datos.  
![image](https://user-images.githubusercontent.com/38962063/194183241-4f38242e-4362-470e-a11e-4a6e88771bab.png)
7. Podra ver que tiene un enlace donde va a poder entrar como administrador, una vez ingrese al enlace, podra crear un usuario de administrador y podrá ingresar a strapi para facil manejo del proyecto y la creación de las tablas y habilitación de metodos de peticiones para las mismas.

![image](https://user-images.githubusercontent.com/38962063/194190790-f3810805-d9de-47f2-9096-2bc34f298ff4.png)
En el caso de ustedes les pedira crear un usuario, en mi caso ya tengo un usuario creado que es el que usaré para ingresar.

Una vez adentro vamos a la opción Content type builder:
![image](https://user-images.githubusercontent.com/38962063/194191239-0d714c91-8c6d-40ff-8d4d-801e230323de.png)
Allí podremos crear una tabla para nuestra base de datos de forma interactiva.
![image](https://user-images.githubusercontent.com/38962063/194191301-0ffad5b0-0110-4e6b-8597-e9f5e2312360.png)
Creamos la tabla "Persona" y le agregamos 3 campos y sus respectivos tipos.
![image](https://user-images.githubusercontent.com/38962063/194191394-9b690b5d-fea9-4d16-a679-a5d8c8cb432a.png)

Seguido a esto, vamos a content manager y agregamos registros a la tabla Con el boton de la esquina que dice "Create new entry":
![image](https://user-images.githubusercontent.com/38962063/194191477-ab7653fa-9bf2-408d-ad5e-3167460ca895.png)
Estos registros deben aparecer en la base de datos que creamos en PostgreSQL:
![image](https://user-images.githubusercontent.com/38962063/194191672-7c45a753-721f-4da2-a3b6-fe18e8f46119.png)
Seguido a esto volvemos a Strapi y vamos a "settings" -> "Roles" -> "Public" y  Desplegamos las opciones debajo de la tabla que creamos (Persona):
y habilitamos todaslas peticiones a la base de datos como en la imagen:
![image](https://user-images.githubusercontent.com/38962063/194191854-e00172f0-85a0-47c9-b819-0bbe23784fc8.png)

Seguido a esto ya podemos probar desde Postman todas las peticiones a base de datos con los url que se nos especifica en strapi :

![image](https://user-images.githubusercontent.com/38962063/194191975-db7c1df0-e263-43cc-9aaf-71781020d57c.png)
![image](https://user-images.githubusercontent.com/38962063/194191992-c667ace6-c63d-4903-b109-16a45cd2d861.png)
![image](https://user-images.githubusercontent.com/38962063/194192013-22541b3d-d0f1-4262-9f7a-e7e42ccaac8b.png)
![image](https://user-images.githubusercontent.com/38962063/194192048-f988e882-77c6-4383-bd74-0a2406e5e1c2.png)

Ejemplo: 

![image](https://user-images.githubusercontent.com/38962063/194192169-4cd42e7e-54a7-4dbf-b5ef-0e6129ef0183.png)







