# Single Spa Microfrontend

## Indice

* [Pre-requisitos](#prerequisites)  
    * [Nvm](#prerequisites_nvm)  
    * [Node.js](#prerequisites_node)  
    * [Create single spa](#prerequisites_create_spa)  
--------
    
<a name="prerequisites"/>

#### Pre-requisitos
Necesitarás tener instalado un entorno de desarrollo de `Node.js®` y `npm` en tu sistema operativo, para eso instalar lo siguiente:

<a name="prerequisites_nvm"/>

###### Nvm
Para gestionar y configurar diferentes entornos de Node

- Para comprobar version, ejecutar `nvm --version` en consola.
- En caso de no tener instalado `nvm` ir a [NVM](https://github.com/nvm-sh/nvm) para su instalación.

<a name="prerequisites_node"/>

###### Node.js
Tecnologia con la cual corre el proyecto, actualmente estamos utilizando la `Node v12.13.1` actualmente definida en el `package.json`

- Para comprobar versión, ejecutar `node -v` en consola.
- En caso de no tener instalado `NodeJs` ir a [nodejs.org](https://nodejs.org/) para su instalación
- Instalar versión v12.13.1 `nvm install v12.13.1 && nvm use v12.13.1`

<a name="prerequisites_create_spa"/>

###### Create-single-spa

Cliente para la generación y administración de la configuración para webpack, babel, jest, etc.
> Doc: https://single-spa.js.org/docs/create-single-spa/
```bash
npm install --global create-single-spa
```
