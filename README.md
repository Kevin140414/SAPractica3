# Practica 4 - Software Avanzado

Esta aplicación es un cliente que consume el web service: https://api.softwareavanzado.world/index.php?webserviceClient=administrator&webserviceVersion=1.0.0&option=contact&api=hal&format=doc.

###### ESB
El objetivo del ESB es mejorar y ayudar al crecimiento de un negocio.
El Bus de Servicios Empresariales debe ser lo bastante robusto como para que permita administrar los cambios en los requerimientos sin que esto suponga en los servicios ya instalados incidencia alguna. Sistema de eventos e infraestructura deben ser capaces de conectar cualquier recurso de TI con independencia de qué tecnología emplee éste.


###### Microservicio cliente
- Solicitar pedido al restaurante
- Verificar estado del pedido al restaurante
- Verificar estado del pedido al repartidor

###### Microservicio Restaurante
- Recibir pedido del cliente
- Informar estado del pedido al cliente
- Avisar al repartidor que ya está listo el pedido

###### Microservicio Repartidor
- Recibir pedido del restaurante
- Informar estado del pedido al cliente
- Marcar como entregado

# Requisitos
  - PHP 5.6 o superior (puede funcionar con algunas versiones inferiores).
  - nodejs

### Instalación
```sh
$ apt-get install php
$ apt-get install node
$ apt-get install npm
```
### Ejecutar
```sh
$ php cliente.php
$ npm start
```
