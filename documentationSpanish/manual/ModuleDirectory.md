<!--- Copyright (C) 2009-2016 Lightbend Inc. <https://www.lightbend.com> -->
# Módulos de Play

Play usa módulos públicos para aumentar la funcionalidad por default.

Para crear su propio módulo público o para migrar desde un `play.api.Plugin`, por favor vea [[ScalaPlayModules]]
o [[JavaPlayModules]].

## Hosting de API

### swagger-play
* **Sitio web:** <https://github.com/swagger-api/swagger-play>
* **Descripción breve:** Genera una especificación de API Swagger a partir de su archivo de rutas de Play y anotaciones de Swagger.

### iheartradio/play-swagger
* **Sitio web:** <https://github.com/iheartradio/play-swagger>
* **Descripción breve:** Escribe una especificaciòn de Swagger en su archivo de rutas.

### zalando/play-swagger
* **Sitio web:** <https://github.com/zalando/play-swagger>
* **Descripción breve:** Genera código de Play a partir de una especificaciòn de Swagger.


## Activos

### play2-sprites
* **Sitio web:** <https://github.com/koofr/play2-sprites/>
* **Descripción breve:** play2-sprites es un plugin de sbt que genera sprites a partir de imágenes.

### Plugin para Sass
* **Sitio web:** <https://github.com/jlitola/play-sass>
* **Descripción breve:** Manejo de activos para archivos de [Sass](http://sass-lang.com/)

### Plugin para Typescript
* **Sitio web:** <https://github.com/ArpNetworking/sbt-typescript>
* **Descripción breve:** Un plugin para SBT que usa sbt-web para compilar archivos de typescript.

## Autenticación (Login y registro) y autorización (accesso restringido)

### Silhouette (Scala)

* **Sitio web:** <http://silhouette.mohiva.com/>
* **Documentación** <http://silhouette.mohiva.com/docs/>
* **Descripción breve:** Una librerìa de autenticación que soporta varios métodos de autenticación, incluyendo OAuth1, OAuth2, OpenID, Credenciales, Autenticación básica, Autenticación de dos factores o esquemas de autenticación a la medida.

### Plugin para Deadbolt 2

* **Sitio web (docs, sample):** <https://github.com/schaloner/deadbolt-2>
* **Descripción breve:** Deadbolt es un mecanismo de autorización para definir derechos de acceso a ciertos métodos controladores o partes de una vista usando una sintaxis simple AND/OR/NOT.

### Play-pac4j (Java y Scala)

* **Sitio web:** <https://github.com/pac4j/play-pac4j>
* **Documentación** <https://github.com/pac4j/play-pac4j/blob/master/README.md>
* **Descripción breve:** Cliente de Play en Scala y Java con soporte para autenticación OAuth/CAS/OpenID/HTTP y recuperación de perfiles de usuario.

### Módulo de autenticación y autorización (Scala)

* **Sitio web:** <https://github.com/t2v/play20-auth>
* **Documentación(inglés):** <https://github.com/t2v/play20-auth/blob/master/README.md>
* **Documentación(japonés):** <https://github.com/t2v/play20-auth/blob/master/README.ja.md>
* **Descripción breve** Este módulo proporciona una manera de autenticación y autorización.

### Play! Authenticate (Java)

* **Sitio web:** <https://joscha.github.io/play-authenticate/>
* **Documentación** <https://github.com/joscha/play-authenticate/blob/master/README.md>
* **Descripción breve:** Un módulo altamente personalizable para Play

### SecureSocial (Java y Scala)

* **Sitio web:** <http://securesocial.ws/>
* **Descripción breve:** Un módulo de autenticación con soporte para esquemas de autenticación Auth, OAuth2, OpenID, NombreDeUsuario/Contraseña y personalizados.

## Datastore

### Plugin Flyway

* **Sitio web:** <https://github.com/flyway/flyway-play>
* **Documentación** <https://github.com/flyway/flyway-play/blob/master/README.md>
* **Descripción breve:** Soporta migración de base de datos con Flyway.

### Plugin MongoDB Jongo (Java)
* **Sitio web (docs, sample):** <https://github.com/alexanderjarvis/play-jongo>
* **Descripción breve:** Proporciona acceso controlado a MongoDB y mapeo de objetos usando [Jongo](http://jongo.org/)

### Plugin MongoDB ReactiveMongo (Scala)
* **Sitio web (docs, sample):** <http://reactivemongo.org/releases/0.11/documentation/tutorial/play2.html>
* **Descripción breve:** Proporciona un módulo de Play 2.x para ReactiveMongo, que es un driver asíncrono y reactivo para MongoDB.

### Play-Slick
* **Sitio web (docs, sample):** <https://github.com/playframework/play-slick>
* **Descripción breve:** Este plugin hace de Slick, un ciudadano de primera clase de Play.

### Plugin Redis (Java y Scala)
* **Sitio web (docs, sample):** <https://github.com/typesafehub/play-plugins>
* **Descripción breve:** Proporciona una implementación de un cache basado en Redis, y también le permite APIs específicas de Redis.

### Plugin ScalikeJDBC (Scala)

* **Sitio web:** <https://github.com/scalikejdbc/scalikejdbc-play-support>
* **Descripción breve:** Proporciona otra API para acceso a base de datos para Play.


## Deployment

### WAR Module

* **Sitio web:** <https://github.com/dlecan/play2-war-plugin>
* **Documentación** <https://github.com/dlecan/play2-war-plugin/blob/develop/README.md>
* **Descripción breve:** Permite empaquetar aplicaciones Play! 2.x en paquetes WAR estándar.

## Localización

### Plugin FolderMessages

* **Sitio web:** <https://github.com/germanosin/play-foldermessages>
* **Descripción breve:** Permite la separación de archivos de mensajes de localización en diferentes archivos (más manejables).

### JsMessages

* **Sitio web:** <https://github.com/julienrf/play-jsmessages>
* **Descripción breve:** Permite calcular mensajes localizados en el lado del cliente.

### Messages Compiler Plugin (Scala)

* **Sitio web:** <https://github.com/tegonal/play-messagescompiler>
* **Documentación** <https://github.com/tegonal/play-messagescompiler/blob/master/readme.md>
* **Descripción breve:** Proporciona seguridad en los tipos para los mensajes del proyecto.

### Play I18n HOCON

* **Sitio web:** <https://marcospereira.github.io/play-i18n-hocon/>
* **Documentación** <https://marcospereira.github.io/play-i18n-hocon/>
* **Descripción breve:** Un módulo del framework Play para usar HOCON para i18n en lugar de propiedades de Java.

## Rendimiento

### Compresor de HTML de Google (Java and Scala)
* **Sitio web:** <https://github.com/mohiva/play-html-compressor>
* **Documentación** <https://github.com/mohiva/play-html-compressor/blob/master/README.md>
* **Descripción breve:** Compresor de HMTL de Google para Play 2.

### Plugin Memcached

* **Sitio web:** <https://github.com/mumoshu/play2-memcached>
* **Descripción breve:** Proporciona una implementación de cache basada en memcached.

## Templates and View

### Google Closure Template Plugin
* **Sitio web (docs, sample):** [https://github.com/gawkermedia/play2-closure](https://github.com/gawkermedia/play2-closure)
* **Descripción breve:** Proporciona soporte para Google Closure Templates (plantillas)

### Módulo de Tags HTML5 (Java y Scala)
* **Sitio web:** <https://github.com/loicdescotte/Play2-HTML5Tags>
* **Documentación** <https://github.com/loicdescotte/Play2-HTML5Tags/blob/master/README.md>
* **Descripción breve:** Estas tags añaden capacidades de validación del lado del cliente, basadas en restricciones de modelo (por ejemplo, requerido, patrón de correo electrónico, longitud minima|máxima...) y campos de entrada específicos (fecha, número telefónico, url...) a las plantillas de Play.

### Módulo PDF (Java)

* **Sitio web:** <https://github.com/innoveit/play2-pdf>
* **Documentación** <https://github.com/innoveit/play2-pdf/blob/master/README.md>
* **Descripción breve** Genera salida en formato PDF a partir de plantillas HTML.

### Play-Bootstrap (Java y Scala)
* **Sitio web:** <https://adrianhurt.github.io/play-bootstrap/>
* **Repository:** <https://github.com/adrianhurt/play-bootstrap>
* **Descripción breve:** Una librería para Bootstrap que le proporciona una solución lista para usarse con un conjunto de ayudas para entradas y constructores de campos.

### Play Dok

* **Sitio web:** <https://go.fudok.com/en/>
* **Documentación** <https://github.com/cchantep/play-dok/>
* **Descripción breve:** Librería para integrar el servicio de plantillas PDF Fukdok a su aplicación Play.

### Módulo Thymeleaf (Scala)
* **Sitio web:** <https://github.com/dmitraver/scala-play-thymeleaf-plugin>
* **Documentación** <https://github.com/dmitraver/scala-play-thymeleaf-plugin/blob/master/README.md>
* **Descripción breve:** Le permite usar el motor de plantillas [Thymeleaf](http://www.thymeleaf.org/) como una alternativa a Twirl

## Utilidades

### Plugin para envío de correos (Java y Scala)
* **Sitio web (docs, sample):** <https://github.com/playframework/play-mailer>
* **Descripción breve:** Proporciona un servicio de envío de correos basado en commons-email de apache.

### Geolocalización (Java)

* **Sitio web:** <https://edulify.github.io/play-geolocation-module.edulify.com/>
* **Documentación** <https://github.com/edulify/play-geolocation-module.edulify.com/blob/master/README.md>
* **Descripción breve:** Módulo para la obtención de datos de Geolocalización basado en la IP.

### Filtro JSONP

* **Sitio web:** <https://github.com/julienrf/play-jsonp-filter>
* **Descripción breve:** Le permite usar JSONP en su API HTTP.

### Generador de mapa del sitio (Java)

* **Sitio web:** <https://edulify.github.io/play-sitemap-module.edulify.com/>
* **Documentación** <https://github.com/edulify/play-sitemap-module.edulify.com/blob/master/README.md>
* **Descripción breve:** Generador automático [sitemaps](http://www.sitemaps.org/) para Play.


## Servicios en la nube

### Módulo Amazon SES (Scala)

* **Sitio web:** <https://github.com/Rhinofly/play-mailer>
* **Documentación** <https://github.com/Rhinofly/play-mailer/blob/master/README.md>
* **Descripción breve:** Una envoltura para la API de SES (*Simple Email Service*, servicio simple de correo electrónico) para Play

### Módulo Amazon S3 (Scala)

* **Sitio web:** <https://github.com/Rhinofly/play-s3>
* **Documentación** <https://github.com/Rhinofly/play-s3/blob/master/README.md>
* **Descripción breve:** Envoltorio para la API de S3 (*Simple Storage Service*, servicio simple de almacenamiento) API para Play

### Pusher
* **Sitio web:** <https://pusher.com/>
* **Documentación** <https://github.com/tindr/Play2Pusher>
* **Descripción breve:** Le permite interactuar de manera sensilla con el servicio Pusher en su aplicación Play.