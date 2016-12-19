---
title: Proposito
---

Documentar el tablero de control tal y como lo tengo ahora y las futuras modificaciones y mejoras planteadas.

### Trucos
* las `category` para el menú de navegación lateral no pueden tener espacios en blanco.
  * por ejemplo base de datos no es valido y database si que lo es.
  ```
  category: base_de_datos
  ```
* en `_config.yml` es necesario seguir unas estrictas reglas de [validación](https://help.github.com/articles/page-build-failed-config-file-error/) si no no se genera las páginas y a veces llega un correo a hotmail con la indicación.
  * por ejemplo no de usan espación y si tabulaciones
```
author:
  name: javier
  email:
  twitter: # twitter username without the @ symbol
```
  * author no admite valor 

