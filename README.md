# AWS-S3-StaticWeb
Publicamos una  página web estática en AWS S3


Nombre del Bucket AWS S3: mypagepereira

Habilitamos las ACL privadas


![image](https://user-images.githubusercontent.com/104144485/188214920-d7c2c43d-bb9d-44e6-9209-6f75ed566580.png)


Desactivamos bloqueo de acceso al publico
Y activamos que reconocemos los riesgos que nuestros Bucket puedan volver publicos


![image](https://user-images.githubusercontent.com/104144485/188215482-0dbccf3d-7cb4-4500-957d-12575a2bace7.png)


Creamos el Bucket y cargamos los archivos de nuestro proyecto


![image](https://user-images.githubusercontent.com/104144485/188215905-496a9224-dfe5-4cf9-af1f-d863e9a28772.png)




![image](https://user-images.githubusercontent.com/104144485/188216159-19e27eaa-6e92-4854-a1d7-7fd407295009.png)



![image](https://user-images.githubusercontent.com/104144485/188216331-3121863c-fd86-402d-8ed1-23f2d3a8b26a.png)


Una vez creado, si entramos a nuestra pagina web index.html por nuestra IP
Notaras que no tendremos acceso.
Parasolventar esa falla tendremos que habilitar el ACL publico

![image](https://user-images.githubusercontent.com/104144485/188216647-060a2a63-1fe1-4b4d-abbd-1934aefca353.png)



![image](https://user-images.githubusercontent.com/104144485/188216766-61559fba-b3ef-4a08-afd7-354741fc2909.png)

Repetimos el mismo paso para toda la caprpeta, habilitar el ACL publico.


![image](https://user-images.githubusercontent.com/104144485/188216966-8db2e709-512e-4f84-991d-5d616941c39b.png)

Entramos en nuestro proyecto index.html

![image](https://user-images.githubusercontent.com/104144485/188217180-ba936aa5-4796-4840-82c9-85820f0f46b5.png)


finalmente hemos cargado nuestra web estatica con s3

![image](https://user-images.githubusercontent.com/104144485/188217599-6a0e8cc7-8d84-446d-b660-96372e730a7b.png)



















