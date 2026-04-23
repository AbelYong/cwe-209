# CWE-209: Generation of Error Message Containing Sensitive Information #

Esta vulnerabilidad consiste en que por medio de una entrada maliciosa, el programa genera un mensaje de error que incluye información confidencial sobre su entorno, usuarios o datos asociados

En este ejemplo, al no realizar un control de excepciones apropiado, permite que un atacante pueda provocar un fallo que revele información valiosa que útil para lanzar otros ataques más graves.

Para este ejemplo, utilizaremos la plataforma Node.js junto con el paquete Express, la cual es un web application framework para Node.js mínimo y flexible que proporciona un conjunto sólido de funciones para desarrollar aplicaciones web y móviles. Facilita el rápido desarrollo de aplicaciones web basadas en Nodos. Las siguientes son algunas de las características principales del marco Express:

* Permite conGgurar middlewares para responder a solicitudes HTTP.
* DeGne una tabla de enrutamiento que se utiliza para realizar diferentes acciones según el método
HTTP y la URL.
* Permite representar dinámicamente páginas HTML basándose en pasar argumentos a plantillas.

Para implementar las vistas se utilizará el motor de plantillas EJS (JavaScript integrado)

## Requisitos ##

* NodeJS

## Ejecutando la vulnerabilidad ##

* Instale el proyecto

```bash
npm init
```

* Envie la solicitud

En Linux o Mac

```bash
curl -H "Host: " http://localhost:3000/ -X POST
```

En Windows

```bash
curl.exe -H "Host: " http://localhost:3000/ -X POST
```
