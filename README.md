
## Kubernetes (Orquestacion de Contenedores)

La Orquestacion de contenedores 
garantiza que los contenedores sean redundante y esten disponibles para que las aplicaciones experimente un tiempo de inactividad minimo.

Kubernetes es una plataforma portable, extensible y open-source

Que es Kubernetes?

1. Es un Software de Codigo abierto, colaboradores de todo el mundo y una variedad de empresas e industrias , contribuyen a Kubernetes. El Codigo , la hoja de ruta y mucho mas se pueden encontrar en linea 

2. Kubernetes esta Diseñado especificamente como una plataforma de orquestacion de contenedores

3. Facilita la Gestion declarativa esto quiere decir que se puede expresar un estado deseado 

Ejemplo: el numero de replicas de una aplicacion especifica y kubernetes trabajara para garantizar que el estado observado coincida con el estado deseado 

4. Opcion de Facto para la orquestacion de los contenedores 

5. Kubernetes no limita los Tipos de aplicaciones que se pueden ejecutar en el y una premisa importante es si una aplicacion se ejecuta en contenedores puede ejecutarse en Kubernetes


## Arquitectura de Kubernetes

Una Implementacion de Kubernetes se denomina cluster.

Caracteristicas que un cluster de kuberenetes debe tener:

1. Seguridad
2. Facilidad de uso
3. Capacidad de expansion

### Elementos que conforman un cluster de Kubernetes

Se puede visualizar en 2 Partes: el plano de control y las maquinas informaticas o nodos, siendo cada nodo propio del entorno Linux y esta puede ser una maquina virtual o fisica , los nodos ejecuta los pods los cuales estan conformados por contenedores 
