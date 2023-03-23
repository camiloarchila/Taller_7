# Taller_7

Creacion de un proyecto donde se utilizan dos instancias ec2 para realizar peticiones seguras en ambas direcciones desde el navegador

## Iniciando 

# Prerequisitos

* Git: Control de versiones de repositorio
* Maven: Administrador del ciclo de vida del proyecto
* AWS: Servicio de nube

## Explicacion del desarrollo

Para acceder al contenido de la url debe estar autenticado con un correo dentro del dominio de la Escuela Colombiana de Ingenieria Julio Garavito

```
https://pruebacorreoescuelaingeduco.sharepoint.com/:v:/s/VideosReco/Ecwgag9HQ6ZMkYn4YKab24MB6fqGwpUDi_cPU6kU4_mJqw?e=Qd8aXL
```

# Version

Verdion 1.0

# Author

* Esteban Camilo Archila Bastidas

# Descripcion Arquitectura

Se realiza el uso de dos instancias EC2 donde cada una de ellas tiene un servicio spark que por medio de conexiones seguras se realizan peticiones una instancia a la otra en ambas direcciones, para la seguridad se crearon certificados ssl firmados propiamente, se crean los contenedores de los certificados de cada intancia y de los certificados en lo que confia cada una.
