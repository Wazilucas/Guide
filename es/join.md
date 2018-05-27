# Configurando el mensaje de bienvenida

Zira necesitará el permiso `Enviar Mensajes` en el canal donde quieras enviar el mensaje.

## Canal

### Uso del comando

z/join channel #canal

### Descripción

Establece el canal donde se enviarán los mensajes.

#### Ejemplo

>![Ejemplo](https://stuff.zira.pw/files/1527371353188.png)

Para dejar de enviar los mensajes usa `z/join channel stop`

>![Stop](https://stuff.zira.pw/files/1527371363985.png)

## Mensaje

### Uso del comando

z/join message Mensaje

Variables que puedes usar en el mensaje:
* $user - nombre de usuario
* $mention - mención al usuario
* $guild - nombre del servidor
* $membercount - cantidad de miembros

### Descripción

Establece el mensaje a enviar cuando un usuario se une.

#### Ejemplo

>![Mensaje](https://stuff.zira.pw/files/1527371566321.png)
