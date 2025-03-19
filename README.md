# Juego-amigo-secreto-challage
Descripción del Proyecto
En este desafío, se desarrollará una aplicación web para realizar un sorteo aleatorio de "Amigo Secreto". Los usuarios podrán ingresar nombres de amigos en una lista, y la aplicación seleccionará un nombre aleatorio para determinar quién es el "amigo secreto". La aplicación incluirá un campo de texto para ingresar nombres, un botón para agregar cada nombre a la lista, y un botón para realizar el sorteo.

Funcionalidades
Agregar nombres: Los usuarios pueden ingresar los nombres de sus amigos en un campo de texto y agregarlos a la lista mediante un botón "Adicionar".
Validar la entrada: Si el campo de texto está vacío, la aplicación muestra una alerta solicitando un nombre válido.
Visualizar la lista: Los nombres ingresados se mostrarán en una lista debajo del campo de texto.
Sorteo aleatorio: Un botón "Sortear Amigo" seleccionará aleatoriamente un nombre de la lista y lo mostrará en la pantalla.
Tareas Específicas
1. Crear un Array para Almacenar los Nombres
Crear un array llamado amigos para almacenar los nombres ingresados por el usuario.
2. Implementar una Función para Agregar Amigos
Crear una función para agregar nombres al array amigos.
Validar que el campo de texto no esté vacío antes de agregar el nombre.
Si el nombre es válido, se agregará al array y se actualizará la lista visible en la página.
3. Implementar una Función para Actualizar la Lista de Amigos
Seleccionar el elemento HTML donde se mostrará la lista de amigos usando document.getElementById() o document.querySelector().
Limpiar la lista antes de agregar nuevos elementos usando innerHTML = "".
Recorrer el array amigos con un bucle for y crear un nuevo elemento <li> para cada amigo, luego agregarlo a la lista.
4. Implementar una Función para Sorteo de Amigos
Crear una función que seleccione aleatoriamente un amigo del array amigos.
Validar que el array no esté vacío antes de realizar el sorteo.
Generar un índice aleatorio usando Math.random() y Math.floor() para seleccionar un índice del array.
Obtener el nombre sorteado y mostrarlo en la pantalla utilizando document.getElementById() e innerHTML.
5. Desafío Extra: Crear el README
Este archivo README describe los objetivos y las funcionalidades de la aplicación, así como las tareas específicas para implementar las funciones.

Requisitos
HTML: Para la estructura básica de la página.
CSS: Para estilizar la página (opcional, pero recomendable para una mejor experiencia visual).
JavaScript: Para la lógica de la aplicación (funciones para agregar amigos, actualizar la lista y sortear aleatoriamente).
Instrucciones de Uso
Abre el archivo index.html en tu navegador.
Ingresa un nombre en el campo de texto y haz clic en "Adicionar" para agregarlo a la lista.
Continúa agregando nombres hasta que todos los amigos estén en la lista.
Haz clic en "Sortear Amigo" para seleccionar aleatoriamente un amigo secreto de la lista.
El nombre del amigo secreto seleccionado aparecerá en la pantalla.
Estructura de Archivos
bash
Copiar
Editar
/amigo-secreto
│
├── index.html         # Estructura HTML básica de la página
├── style.css          # Estilos CSS para la interfaz de usuario
├── script.js          # Lógica de JavaScript para manejar las funcionalidades
└── README.md          # Este archivo de documentación
Contribuciones
Si deseas mejorar o contribuir al proyecto, por favor sigue los siguientes pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y haz un commit (git commit -am 'Agregada nueva funcionalidad').
Haz un push a tu rama (git push origin feature/nueva-funcionalidad).
Crea un nuevo Pull Request.
Licencia
Este proyecto está bajo la Licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente, siempre y cuando se incluya una copia de este archivo de licencia.
