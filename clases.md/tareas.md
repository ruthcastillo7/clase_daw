#Tarea:
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)

##Tipos de INPUT
- `type="button"`:
- `checkbox`:
- `color`: 
- `date`:
- `datetime`:
- `datetime-local`:
- `email:` al utilizar este atributo obligamos al usuario a que ingrese su email, en caso no ingrese su gmail le aparecera un mensaje de error.
- ![alt text](image-5.png)
- `file`:
- `hidden`:
- `image`: 
- `month`: 
- `number`: similar a un campo de texto que solo permite números de punto flotante, y normalmente proporciona botones deslizadores para incrementar o reducir el valor del control. (puedes limitar los valores mínimo y máximo permitidos definiendo los atributos **min y max**.)
![alt text](image-8.png)
- `password:` 
- `radio`:
- `range`:
- `reset`: 
- `search`: se utiliza como cajas de busqueda (como el buscador de google) en paginas y aplicaciones.A menudo los campos **search** se muestran con bordes redondeados; y a veces también muestran una "Ⓧ".
- `submit`: 
- `tel:` se crea un campo de un teclado numerico.
![alt text](image-6.png)
- `text`: 
- `time`: 
- `url`: se crea un tipo especial de campo para introducir URLs. En caso no se valide se mostrara un error por no ingresar en protocolo **https:**
![alt text](image-7.png)
- `week`: 

>[!TIP]
Puedes utilizar el **atributo multiple** en combinación con el tipo **input email** para permitir que sean introducidas varias direcciones de correo electrónico separadas por comas en el mismo input:
```html
<input type="email" id="email" name="email" multiple />
```