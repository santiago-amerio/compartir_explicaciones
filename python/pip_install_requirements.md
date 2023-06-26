# para que sirve?
## para instalar todas las librerias que el proyecto necesite cuando cambias de sistema o virtual enviroment


### en tu sistema, en el virtual enviroment del proyecto
con tu virtual enviroment activado en la consola escribis ```pip freeze``` y vas a recibir una lista asi:
![image](https://github.com/santiago-amerio/compartir_explicaciones/assets/136385908/be3c3cea-a88d-4471-b1cb-fa15a96cb5a7)

Copias la lista completa y la guardas en un archivo con extension .txt lo mas normal es llamarlo "requirements.txt".
ahora, este archivo contiene todas las dependencias que tenes instaladas en tu virtual enviroment.

### movemos el archivo .txt al otro sistema/carpeta

### ahora en el otro sistema/carpeta con el nuevo virtual enviroment ya creado
con el nuevo virtual enviroment activado corremos ```pip install -r requirements.txt```
esto va a instalar automaticamente todas las librerias creadas en el viejo virtual enviroment
