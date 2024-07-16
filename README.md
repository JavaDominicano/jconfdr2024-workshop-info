# jconfdr2024-workshop-info

## English:

### Workshop Preparation :
There are laptop config and setup requirements for your workshop. Please take a look at these here. PLEASE DOWNLOAD ANY REQUIRED SOFTWARE  BEFORE YOU CAN COME ONSITE. 
This will expedite your day and help you get the most out of it.

## Spanish

### Requisitos para los talleres:

Existen requisitos de configuración e instalación para participar en su taller. Revíselos AQUÍ. 
DESCARGUE EL SOFTWARE NECESARIO ANTES DE VENIR AL TALLER. 

Esto agilizará su jornada y le ayudará a sacarle el máximo provecho.

## Workshops / Talleres

1. ### Infraestructura como código para todos
   
* Tener una cuenta de Digital Ocean. Si no la tienes, puedes registrarte aqui https://m.do.co/c/823262eb863f y tener un bono de $200 por 60 días.

* Instalar SDKMAN: https://sdkman.io/install (Si aún no tienes Java/Maven en tu maquina)

* Instalar java y maven con la herramienta previamente instalada. 

 ```
  sdk install java 21.0.3-tem 
  sdk install maven 3.9.4
 ```

* Instalar Docker https://docs.docker.com/engine/install/ 
* Descargar imagen base con las herramientas que usaremos

```
docker image pull hectorvent/iac-for-everyone
```

**Nota:**
 Vamos a usar una imagen de docker para agilizar y evitar problemas que pueden aparecer en nuestros entornos. Esta imagen contiene: **Ansible**, **OpenTofu** y el cliente de Digital Ocean **dotcl**.

### Unlocking the Power of Multitenancy (Quarkus and Vaadin Flow)
[Repo](https://github.com/JavaDominicano/quarkus-vaadin-multi-tenancy)

### Unlock the potential of Jakarta REST to build RESTful Web Services
[Repo]()

### Integración de Spring Boot con PayPal y Buenas Prácticas
* [Repo](https://github.com/geovannymcode/workshop-participant/tree/main/mod_01_configuracion_entorno)
* [GeoLabs Bookstore Workshop Guide](https://geovannymcode.github.io/geolabs-bookstore.github.io)
