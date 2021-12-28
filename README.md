# PhotoGaleryAngularReact
Integrantes:
- John Vásconez
- Alexis Yépez
- Joel Díaz
  
APKs y Bundles de la aplicación Photo Galery en Angular y React.

Se utilizará Android Studio, y tanto para Angular y React, los pasos para el despliegue son los que se detallan a continuación:

1) Compilamos el proyecto con el comando: ionic build
2) Creamos el proyecto para Android con el comando: ionic cap add android
3) Despues copiamos los cambios al diectorio web con el comando: ionic cap copy
4) Para sincronizar los cambios utilizamos el comando: ionic cap sync
5) Ejecutamos el comando: ionic cap open android
6) Verificamos que los permisos para la cámara esten correctos en android/app/src/main/:
![image](https://user-images.githubusercontent.com/38251240/147524025-a5764cde-2acf-4c36-8c8a-e847c687192f.png)
7) En la sección de permisos agregamos las siguientes líneas:

![image](https://user-images.githubusercontent.com/38251240/147524196-dd964cb8-aa50-4181-8ddf-470a24cc6a88.png)

8) Una vez que el proyecto se ha cargado en Android Studio generamos el APK como se muestra en la imagen:
![image](https://user-images.githubusercontent.com/38251240/147526029-ee5a6292-abac-4708-8916-8856626e84aa.png)
9) De la misma manera lo hacemos para en bundle:
![image](https://user-images.githubusercontent.com/38251240/147526085-b31af1b9-04e9-4d70-85ab-bf14f1344eab.png)
10) En la parte inferior derecha nos muestrará el mensaje cuando finalice la creación del APK y del Bundle. Podemos hacer clic en locate para ir al directorio donde se han generado:

![image](https://user-images.githubusercontent.com/38251240/147526233-3b89541e-5d5b-4247-9005-9d003f516f5c.png)
![image](https://user-images.githubusercontent.com/38251240/147526693-65005ac2-9fbd-4889-9448-cb0c87277493.png)

11) Finalmente ejecutamos las APKs en BlueStack5 para comprobar el funcionamiento:
![image](https://user-images.githubusercontent.com/38251240/147527680-0e0b04fe-5e51-4d51-bf99-6883bd425339.png)
![image](https://user-images.githubusercontent.com/38251240/147527695-41dab805-b514-4f8c-b0eb-ed265cb7c104.png)
![image](https://user-images.githubusercontent.com/38251240/147527706-fd297c58-108f-46b5-a5c9-c4b934d2140e.png)
![image](https://user-images.githubusercontent.com/38251240/147527714-f4675a32-4844-40ef-b37c-390ec01fc1fd.png)
