---
title: Proposito
---

Documentar el tablero de control tal y como lo tengo ahora y las futuras modificaciones y mejoras planteadas.

### Trucos
* las `category` para el menú de navegación lateral no pueden tener espacios en blanco o si se usan deben usarse comillas dobles.
  * por ejemplo base de datos no es valido pero database y "base de datos" si que lo es.  
  
  ```
  category: "base de datos"
  ```
* en `_config.yml` es necesario seguir unas estrictas reglas de [validación](https://help.github.com/articles/page-build-failed-config-file-error/) pués de otra forma no se generan las páginas y a veces llega un correo a hotmail con la indicación del error.
  * por ejemplo no de usan espaciós y si tabulaciones
  
   ```
   author:  
     name: javier  
     email:  
     twitter: # twitter username without the @ symbol  
   ```
   
  * author no admite valor 

