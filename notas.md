# Notas Ruta GO-cloud
## Día 1 
- instale go VS code
- Git: los 4 comandos basicos
**Idea general:**git es un sistema de control de versiones. Guarda el historial de mi proyecto, como"fotos"de como estaba el codigo en cada momento, y me permite volver atras si algo sale mal. github es le sitio en internet donde guardo una copia en la nube. 
### 'git init' convierte una carpeta en un repositorio. crea una carpeta oculta.'git' donde git guarda todo el historial. Se ejecuta **una sola vez**por proyecto
### 'git add' pasa mis archivos al**area de preparacion** (stating). Es como decidir que archivos van en la proxima foto. El punto ('.') significa "todos los archivos con cambios". Tambien puedo agregar uno solo: 'git add main.go'.
### 'git commit -m "mensaje"' Guarda la foto en el historial **de mi computador**, con un mensaje que explica que cambie. Cada commit tiene un identificador unico (por ejemplo 'a275f55'). el mensaje debe ser claro y corto: 'agrego notas del dia 1".
### 'git push'
Sube mis commits a github (la copia en la nube). Sin este paso, mi codigo solo existe en mi computador. La primera vez se usa 'git push -u origin main';  el '-u' deja guardada la conexion y despues basta con 'git push'.
### 'flujo de trabajo'
modifico archivos -> 'git add . -> 'git commit -m "..." -> 'git push'
###comandos de ayuda
- 'git status