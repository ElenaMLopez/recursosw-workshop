# #5 Cloud Firestore + Cloud Storage

## Cloud Firestore
https://firebase.google.com/docs/firestore/?hl=es-419

> Cloud Firestore es base de datos NoSQL flexible, escalable y en la nube para almacenar y sincronizar datos.  
Se puede usar en el lado del cliente o en el servidor.  
A diferencia de una base de datos SQL, no hay tablas ni filas. En su lugar, almacenas los datos en documentos, que se organizan en colecciones.

![firestore1](./assets/img/firestore1.png)
<br>
![firestore2](./assets/img/firestore2.png)

🔗Explicación: [Firestore](https://firebase.google.com/docs/firestore/data-model?hl=es-419)

## Cloud Storage
https://firebase.google.com/docs/storage/?hl=es-419

> Cloud Storage para Firebase es un servicio de almacenamiento de objetos (imágenes, audio, video, etc) de Google. 
Puedes subir y descargar archivos directamente del cliente.  
Si la conexión a la red es deficiente, el cliente puede reintentar la operación donde la dejó de inmediato, lo cual les ahorra tiempo y ancho de banda a los usuarios.

<p align="center">
  <img src="./assets/img/cloud_storage.png" height="200" />
</p>

---

###### Descripción: 
En este paso vamos a crear el formulario que nos permite dar de alta un recurso en la base de datos y subir la imagen correspondiente.  
En el bloque #6 explicaremos las cloud functions, aunque hagamos uso de ellas en este paso.  

--- 
### Formulario: 

Template - https://gist.github.com/baumannzone/02f9836d55c51fd1cc3adb1ee9330df0

---
Vamos a la rama `step5A_firestore`

---
![footer](./assets/img/footer.png)
