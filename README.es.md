<!--hide-->
# ¡Lista de tareas pendientes CLI sincronizada con la nube!
<!--endhide-->

<p align="center"><img src="https://github.com/breatheco-de/todo-list-cli-with-cloud/blob/master/preview.gif" width="500" /></p>

Hoy construirás una lista TODO usando API's para sincronizarla con la nube.

Practicarás:
1. Listas / arrays de Python.
2. Diccionarios de Python.
3. Usar el paquete requests para la comunicación de API.
4. Protocolo HTTP.

Vamos a usar la [API de TODO de BreatheCode](https://playground.4geeks.com/apis/fake/todos/) para cargar y descargar los TODO, por favor consulta las lecciones de HTTP y REST como una investigación de fondo rápida para el proyecto.

- Obtener TODO llamando: `[GET] /todos/user/<username>`
- Inicializar la lista TODO: `[POST] /todos/user/<username>`
- Actualizar tu lista TODO: `[PUT] /todos/user/<username>`

## 🌱 Cómo comenzar este proyecto

No clones este repositorio.

1. El primer paso para comenzar a codificar es clonar el [boilerplate de python](https://github.com/4GeeksAcademy/flask-rest-hello) en tu computadora local o abrirlo usando gitpod.

a) Si usas Gitpod, puedes clonar el boilerplate haciendo [clic aquí](https://github.com/4GeeksAcademy/flask-rest-hello).
b) Si trabajas localmente, escriba el siguiente comando desde tu línea de comandos: `git clone https://github.com/4GeeksAcademy/flask-rest-hello`.

💡 Importante: recuerda crear un nuevo repositorio, actualizar el remoto (`git remote set-url origin <your new url>`) y cargar el código a tu nuevo repositorio `add`, `commit` y `push`.

2. Instala los paquetes de dependencia escribiendo:

```sh
$ pipenv install --python 3
```

3. Entra a tu entorno virtual escribiendo:

```sh
$ pipenv shell
```

4. Puedes ejecutar el proyecto escribiendo:

```sh
$ python src/app.py
```

5. También puedes ejecutar las pruebas para el proyecto:

```sh
$ python src/test.py
```

## 📝 Instrucciones

- Tu aplicación debe funcionar desde la línea de comandos [así](https://github.com/breatheco-de/todo-list-cli-with-cloud/blob/master/preview.gif).
- El usuario debe poder agregar nuevas tareas.
- El usuario puede agregar tantas tareas como desee.
- El usuario puede eliminar tareas especificando la posición de la tarea en la lista.
- La aplicación debe poder guardar los TODO en la nube usando la [API de TODO de BreatheCode](https://playground.4geeks.com/apis/fake/todos/)
- La aplicación debe poder descargar (cargar) los TODO desde la [API de TODO de BreatheCode](https://playground.4geeks.com/apis/fake/todos/)


