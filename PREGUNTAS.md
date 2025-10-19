Reflexión final:
1.	¿Por qué es mejor usar variables de entorno que hardcodear credenciales?
R// Es por varias funciones como lo son: Seguridad ya que no quedan visibles en el código original, Flexibilidad: podemos cambiar la BD sin modificar el código, Escalabilidad: podemos mover la aplicación a otra maquina y el código sigue funcionando.
2.	¿Qué ventaja ofrece Docker Compose frente a ejecutar contenedores por separado?
R// Los que podemos ver son los siguientes: múltiples contenedores, dependencias, red interna automática. En otras palabras, en lugar de abrir dos terminales y ejecutar “Docker run” por separado, Compose lo hace todo con un solo comando.
3.	¿Qué sucede si eliminas el volumen db_data ?
R// Se perderán todos los datos que están en PostgreSQL, esto creara un nuevo almacenamiento vacío al iniciar de nuevo todo, es decir, el contenedor sigue funcionando, pero la base de datos estará limpia. 
