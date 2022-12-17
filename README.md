# despliegue_app
>> APLICACION BackEnd

![image](https://user-images.githubusercontent.com/91167211/208209184-434bea94-1572-41f3-a4c6-290544c66144.png)

- Colocamos el comando vi docker-compose.yml para verificar el codigo que copiamos (para guardar y salir ponemos ------> wq )

![image](https://user-images.githubusercontent.com/91167211/208209519-efe250a7-78fd-4e5e-a4e2-6450167eeab7.png)

Para verificar los contenedores que tenemos colocamos el comando docker ps

![image](https://user-images.githubusercontent.com/91167211/208212553-61b69576-2553-4c0b-a79f-42191cf776ef.png)

Colocamos el comando cat docker-compose.yml

![image](https://user-images.githubusercontent.com/91167211/208209802-d3aef88b-1dc0-4db3-aaa5-fc052fcf4d1f.png)

Colocamos el comando docker-compose up -d (sirve para descargar las librerias, si ya estan cargadas nos salen que ya estan corriendo)

![image](https://user-images.githubusercontent.com/91167211/208209906-f49891d9-5f0e-49fc-94a2-60183b198508.png)

Clonamos el repositorio con (git clone https://github.com/maguaman2/tendencias-mar22-security)

![image](https://user-images.githubusercontent.com/91167211/208210263-9c163056-7a21-476f-9778-54f655a9a631.png)

Colocamos un ls para ver los directorios que disponemos

![image](https://user-images.githubusercontent.com/91167211/208210410-9be75225-2af7-4f75-ba1d-7cefd16e778b.png)

Creamos un documento llamado Dockerfile (vi Dockerfile)

![image](https://user-images.githubusercontent.com/91167211/208210811-fc0d2637-14ce-45f4-98e5-f6afd11a2e53.png)

Colocamos el comando docker build -t myapp .

![image](https://user-images.githubusercontent.com/91167211/208211130-1dfb17e6-99c6-4e18-918e-ab4f8487e80e.png)

Colocamos el comando (docker run -d --network db_default -p 8081:8081 myapp) y verificamos en localhost:/users y nos deberia salir la tabla

![image](https://user-images.githubusercontent.com/91167211/208211357-1556d6a3-f9d2-4bc1-b30a-870f7e921b03.png)

>> APLICACION FrontEnd

Vamos a la carpeta local y colocamos lo siguiente Colocamos el comando de (git clone git clone https://github.com/maguaman2/securityfe )

![image](https://user-images.githubusercontent.com/91167211/208212091-5caa848d-7018-47ee-8fe1-d459a3436140.png)

Entramos en el nuevo gitclone y creamos un vi Dockerfile

![image](https://user-images.githubusercontent.com/91167211/208212367-8a0f89b5-4f97-4840-8c3a-6a08ee33b544.png)

Colocamos el comando (docker build -t myappfe:latest .) para crear una imagen

![image](https://user-images.githubusercontent.com/91167211/208212462-2907beab-f638-49d0-beb0-131fc3c9a2de.png)




