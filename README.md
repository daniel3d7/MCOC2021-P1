# MCOC2021-P1
Optimización estructural de un puente reticular


Informe Entrega 7

Al comenzar, partimos con nuestro codigo de la entrega pasada y proseguimos a rellenar "05_ejemplo_chequear_diseño.py", y logramos agregar todos los nodos y barras.
A continuación, se veran las imagenes de los calculos. 

![image](https://user-images.githubusercontent.com/88512479/135766467-606a87c3-38bb-4e33-9e24-d8f0c1ff3971.png)
![image](https://user-images.githubusercontent.com/88512479/135766485-c4d1e06f-9455-4f9c-a367-31bd6b287fd3.png)
![image](https://user-images.githubusercontent.com/88512479/135766512-4ef5a618-247d-48fc-9443-8edaf321733a.png)
![image](https://user-images.githubusercontent.com/88512479/135766529-5bc5abdf-72bb-4bf9-8f62-28d4f8106938.png)

Luego tuvimos varios errores, como por ejemplo este en "reticulados.py" que tenia un error en perfiles. 

![image](https://user-images.githubusercontent.com/88512479/135766640-590eaefc-5ad6-4cd9-bf0e-2aeefb8f0150.png)

Lo corregimos cambiando perfil por seccion. 

Luego, estuvimos mucho tiempo sin poder el siguiente error. 

![image](https://user-images.githubusercontent.com/88512479/135766786-63c3f452-7014-4a29-b4a8-5a5ea3c13d06.png)

Lo arreglamos introduciendo "float" en Area y Peso. Pero nos seguia apareciendo el error. 

![image](https://user-images.githubusercontent.com/88512479/135766815-b5a4ec4f-bf47-420c-ace0-9163065cb810.png)

Por lo que nos dimos cuenta que habia que quitarle los parentesis () al area y peso. 

.
.
.
.
.





Al corrernos por primera vez, pesaba 420990.5991925834 kg.

Esto se hizo con secciones H1100x350x400.4

![image](https://user-images.githubusercontent.com/88512479/135768832-5f0a8f6a-ccd7-4d7a-87c9-fb675462f5bd.png)


Con eso ya listo, nos dispusimos a bajar el peso del puente. Con esto, comenzamos a probar con distintas secciones que se aprecian en la foto. 

Luego de hacer lo cambios, proseguimos con el segundo intento y llegamos al valor de 161578.90482444424 kg.

Esto se hizo con secciones H800x350x148.2 y H1100x350x188.5

![image](https://user-images.githubusercontent.com/88512479/135768906-ce441e75-4bb0-4e64-b29f-ce24b7e61996.png)


Pero aun asi nos dispusimos a bajar mas el peso y seguimos modificando. 

En el tercer intento llegamos al valor de 114936.27114383684 kg.

Esto se hizo con secciones H300x200x103.2 y H800x350x148.2

![image](https://user-images.githubusercontent.com/88512479/135768963-2a2aacdd-0722-4958-8292-c9cf4b2e2fa2.png)


Seguimos tratando de bajar el peso introduciendo barras chicas, medianas, grande y supergrande de distintas dimenciones. 

Añadimos las siguientes barras. 

![image](https://user-images.githubusercontent.com/88512479/135769815-dc9edb97-c203-45b1-ac3f-d21fa8f265d0.png)

Con estas nuevas barras nos subio el peso a 123085.71508306783 kg.

![image](https://user-images.githubusercontent.com/88512479/135769840-1660bf7e-97a8-4d4a-a912-cfbb2b676c41.png)


Nos dimos cuenta que subio, pero seguimos modificando las barras. 

![image](https://user-images.githubusercontent.com/88512479/135769925-4d12569c-116d-47ee-82f5-19187b772ac1.png)

Con estas modificaciones bajamos mucho el peso, llegando a 84033.14362704242 kg.

![image](https://user-images.githubusercontent.com/88512479/135769958-cbe48168-b3d3-40a8-a3ed-4b87bd864ac8.png)

Seguimos modificando las barras hasta llegar a nuestro diseño final, con las siguientes barras. 

![image](https://user-images.githubusercontent.com/88512479/135770135-d99fe2fa-0eba-487b-b929-c2a17da5fb3c.png)

Con esas barras, llegamos al valor FINAL de 63928.63075902012 kg.

![image](https://user-images.githubusercontent.com/88512479/135770156-3f6e9e51-51ba-4f08-ac8e-c272841a0842.png)

Por lo que, nuestro diseño final consta de un valor total de 63928.63075902012 kg. 

![image](https://user-images.githubusercontent.com/88512479/135770268-5017a1bb-4a6d-4104-bed7-0fee0085f983.png)


































