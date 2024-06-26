# Propuesta TP DSW

## Grupo
### Integrantes
* 50310 - Berli, Nahuel
* 51189 - Gilardoni, Lucio
* 51192 - Godoy, Marcos
* 50311 - Jaca, Juan Pablo
* 51419 - Márquez, Matías

### Repositorio

* [frontend|backend app](https://github.com/DSW-3k02-GGJM/TP-3k02-Berli-Gilardoni-Godoy-Jaca-Marquez-App)
  
## Tema
### Descripción
 La aplicación a desarrollar pertenece a una empresa que se dedica a el alquiler de vehiculos. La empresa en cuestión es propietaria de una serie de vehiculos con distintas características que pone a disposición de clientes externos.

### Modelo
![Desarrollo de Software](https://github.com/DSW-3k02-GGJM/TP-3k02-Berli-Gilardoni-Godoy-Jaca-Marquez-Propuesta/assets/126622905/b2e64f7c-918f-45c9-82c8-2ff5f3c78972) (CAMBIAR) (TODO)
https://app.diagrams.net/#G1T8A3RHq2puBGWPst9cmb9irHvQW6AFIo#%7B%22pageId%22%3A%22C5RBs43oDa-KdzZeNtuy%22%7D

## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Cliente<br>2. CRUD Categoria<br>3. CRUD Marca<br>4. CRUD Modelo<br>5. CRUD EstadoVehiculo|
|CRUD dependiente|1. CRUD Vehiculo {depende de} CRUD Categoria<br>2. CRUD Alquiler {depende de} CRUD Vehiculo y Cliente<br>3. CRUD EstadoAsignado {depende de} CRUD Estado y Vehiculo|
|Listado<br>+<br>detalle| 1. Listado de alquileres filtrado por fecha <br> 2. Listado de vehiculos disponiblese filtrados por estado <br> 3. Listado de clientes |
|CUU/Epic|1. Reservar un vehiculo <br>2. Realizar el check-in de un alquiler <br>3. Realizar checkout de un alquiler|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |Todos los del MD|
|CUU/Epic|1. Reservar un vehiculo <br>2. Realizar el check-in de un alquiler <br>3. Realizar checkout de un alquiler <br>4. Cancelar Alquiler <br>5. Envio recordatorio de Alquiler<br>6. Comunicacion con clientes/mail.|


