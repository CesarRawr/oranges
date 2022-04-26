# A Hombros de Gigantes
_Ejercicio saludar dividido. Reverse proxy. Docker Compose_

### Como correr

_Abrir Docker y ejecutar el siguiente comando:_
```
git clone https://github.com/CesarRawr/oranges && cd oranges && docker-compose up
```
_Una vez corriendo aparecerán varios puertos arriba de la página del docker playground, tocar el puerto 80_
_Cuando cargue la página, en la url de la misma poner alguno de los siguientes paths_

```
/saludar
/borrar
/buscar
/modificar
```
_Ejemplo:_
```
http://ip172-18-0-31-c9jm57p4lkkg00deerog-80.direct.labs.play-with-docker.com/saludar
```

_Al dar enter te redirige al wsdl de saludar y dependiendo del path te redirigirá al servicio requerido_
