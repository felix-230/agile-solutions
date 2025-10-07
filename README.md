💻 Agile Solutions - Panel de Control (CRUD Básico)
Este proyecto simula un sistema de inicio de sesión y un panel de control administrativo sencillo para la gestión de servicios, implementado completamente con HTML, Tailwind CSS para el diseño, y JavaScript puro para la lógica de autenticación y las operaciones CRUD (Crear, Leer, Actualizar, Eliminar).

🚀 Estructura del Proyecto
El proyecto se compone de dos archivos principales que deben estar ubicados en la misma carpeta para que la navegación funcione:

login.html: Contiene el formulario de inicio de sesión y la lógica de validación de credenciales.

dashboard.html: Es el panel de control, donde se encuentra la interfaz CRUD para gestionar los servicios de la plataforma.

🔑 Credenciales de Acceso
Para ingresar al sistema y acceder al panel de control, se utilizan las siguientes credenciales de prueba codificadas directamente en el archivo login.html:

Campo

Valor

Usuario (Email)

admin

Contraseña

toor

Cualquier otra combinación resultará en un mensaje de error.

🛠️ Cómo Ejecutar Localmente
Dado que esta aplicación se basa en archivos HTML estáticos y JavaScript, es muy fácil de ejecutar:

* Descarga o copia los archivos login.html y dashboard.html.

* Haz doble clic en el archivo login.html.

* El archivo se abrirá automáticamente en tu navegador predeterminado.


⚙️ Funcionalidades del Dashboard (dashboard.html)
Una vez dentro, podrás interactuar con el módulo de Gestión de Servicios:

Operación

Descripción

Crear (C)

Usa el formulario superior para añadir un nuevo servicio (Nombre, Precio y Descripción).

Leer (R)

La tabla muestra la lista de todos los servicios disponibles, incluyendo datos de ejemplo.

Actualizar (U)

El botón "Editar" precarga los datos del servicio en el formulario para modificarlos y guardarlos.

Eliminar (D)

El botón "Eliminar" solicita una confirmación y luego remueve el servicio de la lista.

Nota sobre la persistencia: La información de los servicios se guarda únicamente en el array services de JavaScript, por lo que los datos se perderán cada vez que la página se recargue. Para mantener los datos permanentemente, se requeriría una base de datos real (como Firestore o MySQL).