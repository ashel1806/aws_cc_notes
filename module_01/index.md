# Módulo 01

**Tabla de contenido**

- [Modelo Cliente - Servidor](#Modelo%20Cliente%20-%20Servidor)
- [Cómputo en la nube](#C%C3%B3mputo%20en%20la%20nube)
	- [Modelos de informática en la nube](#Modelos%20de%20inform%C3%A1tica%20en%20la%20nube)
		- [Infraestructura como servicio (IaaS)](#Infraestructura%20como%20servicio%20(IaaS))
		- [Plataforma como servicio (PaaS)](#Plataforma%20como%20servicio%20(PaaS))
		- [Software como servicio (SaaS)](#Software%20como%20servicio%20(SaaS))
	- [Modelos de implementación](#Modelos%20de%20implementaci%C3%B3n)
		- [Implementación basada en la nube](#Implementaci%C3%B3n%20basada%20en%20la%20nube)
		- [Implementación en las instalaciones](#Implementaci%C3%B3n%20en%20las%20instalaciones)
		- [Implementación híbrida](#Implementaci%C3%B3n%20h%C3%ADbrida)
- [Beneficios del cómputo en la nube](#Beneficios%20del%20c%C3%B3mputo%20en%20la%20nube)

## Modelo Cliente - Servidor

El `cliente` puede ser desde un navegador web hasta una persona. Lo importante es que este cliente realiza una solicitud al `servidor`, donde este último puede ser un servidor virtual, físico o algún servicio de AWS, como por ejemplo AWS EC2.

![Modelo Cliente Servidor](client_server_model.png)

**Ejemplo:** Para poder entender mejor este modelo pensemos en un restaurante, donde la persona que hace su pedido vendría a ser el `cliente`, y la cocina que se encarga de revisar si hay disponibilidad y entregar el pedido si es así, vendría a ser el `servidor`.

## Cómputo en la nube

El concepto de **nube** hace referencia a los recursos TI que pueden ser entregados bajo demanda y solicitados a través de internet con un modelo de precio de pago por uso.

Es decir, AWS (la nube en este caso) nos brinda los recursos que queremos cuando los necesitamos. De igual forma, si ya no queremos algún recurso, simplemente con un clic lo deshabilitamos e inmediatamente dejamos de pagar por ese recurso.

### Modelos de informática en la nube

Existen tres modelos principales de informática en la nube. Cada modelo representa una parte distinta de la pila de informática en la nube.

#### Infraestructura como servicio (IaaS)

La infraestructura como servicio (IaaS) constituye los bloques esenciales para la infraestructura en la nube, proporcionando acceso a funciones de red, máquinas virtuales, almacenamiento de datos y ofreciendo un alto nivel de flexibilidad y control en la gestión de recursos de TI. Se asemeja a los recursos de TI tradicionales, siendo familiar para muchos departamentos de TI y desarrolladores.

**Ejemplos**: Amazon Web Services (AWS), Microsoft Azure, Google Cloud Platform (GCP)

#### Plataforma como servicio (PaaS)

Las plataformas como servicio (PaaS) liberan a las empresas de la gestión de la infraestructura subyacente, permitiéndoles concentrarse en la implementación y administración de aplicaciones. Esto mejora la eficacia al eliminar preocupaciones como el aprovisionamiento de recursos, la planificación de capacidad y el mantenimiento de software, simplificando la ejecución de aplicaciones.

**Ejemplos**: [Heroku](https://www.heroku.com/what), [Google App Engine](https://cloud.google.com/appengine?hl=es-419), [Microsoft Azure App Service](https://learn.microsoft.com/es-es/azure/app-service/overview)
#### Software como servicio (SaaS)

El software como servicio (SaaS) proporciona un producto completo gestionado por el proveedor del servicio, especialmente aplicaciones de usuario final. Con SaaS, los usuarios no deben preocuparse por el mantenimiento del servicio o la gestión de la infraestructura subyacente. Solo necesitan centrarse en el uso de la aplicación. Un ejemplo común es un programa de correo electrónico basado en la web, donde los usuarios pueden enviar y recibir mensajes sin preocuparse por la administración de funciones ni el mantenimiento de servidores y sistemas operativos.

**Ejemplos**: Microsoft 365, [Salesforce](https://www.salesforce.com/mx/products/what-is-salesforce/), Google Workspace (Docs, Sheets, Presentations, Gmail, etc)
### Modelos de implementación

Existen tres modelos de implementación de la nube: implementación basada en la nube, implementación en las instalaciones e implementación híbrida.

#### Implementación basada en la nube

- Ejecución de todas las partes de una aplicación en la nube
- Migración de las aplicaciones existentes a la nube
- Diseño y creación de nuevas aplicaciones en la nube

Por ejemplo: una empresa podría crear una aplicación compuesta por servidores virtuales, bases de datos y componentes de red totalmente basados en la nube.

#### Implementación en las instalaciones

También conocida como implementación en la ***nube privada***.

- Implementación de recursos mediante herramientas de virtualización y administración de recursos
- Aumento de la utilización de recursos mediante tecnologías de virtualización y administración de aplicaciones

**Por ejemplo**: es posible que tenga aplicaciones que se ejecutan con tecnología que se almacena por completo en su centro de datos local. Aunque este modelo se parece mucho a la [infraestructura de TI heredada](https://blog-es.lac.tdsynnex.com/infraestructura-heredada-por-que-puede-costar-muy-caro-y-como-solucionar-el-problema), su incorporación de tecnologías de virtualización y administración de aplicaciones ayuda a aumentar la utilización de los recursos.
#### Implementación híbrida

- Conexión de los recursos basados en la nube a la infraestructura en las instalaciones
- Integración de los recursos basados en la nube con aplicaciones TI heredadas

**Por ejemplo**: supongamos que una empresa desea utilizar servicios en la nube que pueden automatizar el procesamiento y el análisis de datos por lotes. Sin embargo, la empresa tiene varias aplicaciones heredadas que son más adecuadas en las instalaciones y no se migrarán a la nube. Con una implementación híbrida, la empresa podría mantener las aplicaciones heredadas en las instalaciones y beneficiarse de los servicios de datos y análisis que se ejecutan en la nube.

## Beneficios del cómputo en la nube

#### Cambiar gastos iniciales por gastos variables

Gastos iniciales implican inversiones previas en infraestructura, mientras que los gastos variables en la nube permiten pagar solo por lo que se consume, favoreciendo la innovación y ahorro de costos empresariales.

####  Dejar de gastar dinero en la ejecución y mantenimiento de centros de datos

El cómputo en centros de datos implica mayores costos y tiempo dedicado a la gestión de infraestructura y servidores. En contraste, la computación en la nube ofrece la ventaja de liberar recursos para concentrarse menos en estas tareas y más en el desarrollo de aplicaciones y la satisfacción de los clientes.

#### Dejar de hacer conjeturas sobre la capacidad
  
La computación en la nube permite adaptar la capacidad de infraestructura según la demanda real al lanzar instancias con servicios como Amazon EC2. Pagar únicamente por el tiempo de cómputo utilizado evita costos en recursos infrautilizados, brindando flexibilidad para ajustar la capacidad en respuesta a cambios de demanda, ya sea reduciendo o escalando horizontalmente.

#### Obtener beneficios de grandes economías de escala

La adopción del cómputo en la nube permite obtener un costo variable más bajo en comparación con la gestión independiente. La capacidad de agregar el uso de cientos de miles de clientes en la nube posibilita a proveedores como AWS beneficiarse de economías de escala, resultando en tarifas más bajas gracias a la mayor eficiencia y distribución de costos a lo largo de una amplia base de usuarios.
#### Aumentar velocidad y agilidad

La flexibilidad de la computación en la nube facilita el desarrollo e implementación de aplicaciones, brindando más tiempo para experimentar e innovar. A diferencia de los centros de datos, donde obtener nuevos recursos puede llevar semanas, la nube permite acceder a ellos en cuestión de minutos.

#### Convertirse en una empresa global en cuestión de minutos
  
La amplia presencia global de la nube de AWS permite una rápida implementación de aplicaciones para clientes de todo el mundo, garantizando baja latencia. Esto posibilita que los clientes accedan a las aplicaciones con mínimos retrasos, incluso si se encuentran en diferentes partes del mundo. 