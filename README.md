# Actividades-Introductorias-Bootcamp-Web

✅ ACTIVIDAD 1 – ¿Esto es una web o una app web?
🎯 Objetivo: Comprender la diferencia entre un sitio web estático y una aplicación web interactiva.

1. Ejemplos de sitios web informativos:
Wikipedia: Enciclopedia digital colaborativa con contenido estático.

BBC News: Portal de noticias internacionales.

National Geographic: Sitio educativo sobre ciencia, naturaleza e historia.

2. Ejemplos de aplicaciones web:
Gmail: Plataforma para enviar, recibir y gestionar correos electrónicos.

Trello: Herramienta de gestión de tareas y proyectos con tableros dinámicos.

Spotify Web: Reproductor en línea con acceso a música, playlists y control de reproducción.

3. Justificación de la clasificación:
Sitios web informativos están pensados para entregar contenido al usuario. Su interacción es mínima: leer artículos, hacer clic en enlaces o navegar entre páginas. No requieren una lógica compleja en el navegador, y muchas veces son HTML, CSS y algo de JavaScript para mejorar la experiencia visual.

Aplicaciones web, en cambio, permiten una interacción continua con los datos: puedes enviar información (como escribir un correo), recibir respuestas en tiempo real, modificar contenido, guardar configuraciones, etc. Utilizan lógica de programación tanto en el cliente (navegador) como en el servidor, y están diseñadas para comportarse como programas completos dentro del navegador.

4. Reflexión: ¿Qué hace que una aplicación web sea interactiva?
Una aplicación web es interactiva porque:

Permite al usuario manipular información en tiempo real (ej. crear tareas, enviar mensajes, reproducir contenido, etc.).

Cambia su contenido o comportamiento sin necesidad de recargar la página.

Responde a eventos del usuario como clics, entradas de texto, movimientos del mouse, etc.

Tecnologías comunes detrás de una aplicación web:

HTML, CSS, JavaScript (para la estructura, estilo e interactividad básica).

Frameworks de JavaScript: React, Vue, Angular.

Lenguajes del lado del servidor: Node.js, Python, PHP, Ruby, Java.

Bases de datos: MySQL, MongoDB, PostgreSQL.

APIs: permiten que la app se comunique con servidores u otros servicios.

AJAX / Fetch / WebSockets: para enviar y recibir datos sin recargar la página.

✅ ACTIVIDAD 2 – Anatomía de una aplicación web moderna
🎯 Objetivo: Comprender los componentes principales de una app web (frontend, backend, base de datos).
1. Conceptos clave:
🔸 Frontend
Es la parte visible de la aplicación con la que el usuario interactúa directamente.
Incluye: botones, formularios, textos, imágenes, animaciones, etc.
Lenguajes comunes: HTML, CSS, JavaScript y frameworks como React, Vue o Angular.

🔸 Backend
Es la parte "invisible", que procesa la lógica de negocio, valida datos y se comunica con la base de datos.
Lenguajes comunes: Node.js, Java, Python, PHP.
Ejecuta en el servidor y responde a las solicitudes del frontend.

🔸 Base de datos
Es donde se almacenan y organizan los datos de la aplicación: usuarios, contraseñas, publicaciones, productos, etc.
Ejemplos: MySQL, PostgreSQL, MongoDB.

2. Diagrama simple en formato Mermaid
Puedes copiar este código en https://mermaid.live para visualizarlo:

graph LR
A[👤 Usuario] --> B[🌐 Frontend (HTML, CSS, JS)]
B --> C[💻 Backend (Lógica del servidor)]
C --> D[(🗂️ Base de Datos)]

C --> B

Explicación del flujo:
El usuario interactúa con la interfaz (Frontend).

El frontend envía solicitudes (por ejemplo, para iniciar sesión) al Backend.

El backend procesa la solicitud y consulta o actualiza la Base de Datos si es necesario.

El backend responde al frontend con los datos solicitados o el resultado de una acción (como un mensaje de éxito).

El frontend muestra esta respuesta al usuario.

✅ ACTIVIDAD 3 – Explorando las herramientas de desarrollo
🎯 Objetivo:
Familiarizarse con las DevTools (herramientas de desarrollo) del navegador.

📝 Instrucciones:
1. ¿Cómo abrir DevTools?
Según tu sistema operativo:

Windows: Presiona F12 o Ctrl + Shift + I

Linux: Presiona Ctrl + Shift + I

Mac: Presiona Cmd + Option + I

Esto abrirá una interfaz de herramientas para inspeccionar el sitio web.

2. Explora estas pestañas clave:
🔸 Elementos (Elements)
Permite inspeccionar y modificar el HTML y CSS de la página en tiempo real.

🔸 Consola (Console)
Muestra errores, advertencias y mensajes de JavaScript. También puedes escribir código JS directamente.

🔸 Red (Network)
Muestra todas las solicitudes HTTP (archivos HTML, CSS, JS, imágenes, API, etc.), tiempos de carga y respuestas.

🔸 Almacenamiento (Storage)
Permite ver las cookies, el localStorage y sessionStorage, entre otros datos que guarda el navegador.

3. Tareas prácticas:
Abre cualquier sitio web (por ejemplo, google.com) y realiza lo siguiente:

✅ Captura 1: Una solicitud HTTP
Ve a la pestaña Network.

Recarga la página (F5) para ver las solicitudes en tiempo real.

Haz clic en alguna (por ejemplo, index.html o alguna imagen/logo).

Verás información como: método (GET/POST), status (200/404), tiempo de carga, encabezados, etc.

✅ Captura 2: Un error en la consola
Ve a la pestaña Console.

Si aparece un error (en rojo), toma un pantallazo.

Si no hay errores, puedes forzar uno escribiendo esto en la consola:

console.log(variableInexistente);

✅ Captura 3: El HTML de un elemento
Ve a la pestaña Elements.

Haz clic derecho sobre el logo o texto de la página y selecciona "Inspeccionar".

Verás el HTML resaltado. Puedes tomar un pantallazo de eso.

✅ ACTIVIDAD 4 – Soy nuevo y aprendí Java… ¿y ahora qué con HTML, CSS y JS?
🎯 Objetivo:
Dar una primera mirada sencilla a HTML, CSS y JavaScript.

1. ¿Qué hace cada tecnología en una web?
🔹 HTML (HyperText Markup Language)
Es el esqueleto de una página web. Define la estructura y el contenido: títulos, párrafos, imágenes, enlaces, formularios, etc.

📌 Ejemplo:

<h1>¡Hola Mundo!</h1>
<p>Esta es mi primera página web.</p>

🔹 CSS (Cascading Style Sheets)
Se encarga del diseño visual: colores, tamaños, posiciones, tipografías, animaciones, etc. Le da estilo al HTML.

📌 Ejemplo:

h1 {
  color: purple;
  text-align: center;
}

🔹 JavaScript (JS)
Es el cerebro o la lógica de la página. Permite que el sitio web sea interactivo: validaciones, animaciones, respuestas a clics, datos dinámicos, etc.

📌 Ejemplo:

alert("¡Bienvenide a mi sitio web!");

2. Java vs JavaScript – ¿En qué se parecen y en qué no?
Característica	Java	JavaScript

| Característica       | Java                                           | JavaScript                             |
| -------------------- | ---------------------------------------------- | -------------------------------------- |
| **Tipo de lenguaje** | Compilado, fuertemente tipado                  | Interpretado, débilmente tipado        |
| **Ejecuta en…**      | Máquina virtual (JVM)                          | Navegador (cliente) o Node.js          |
| **Sintaxis**         | Similar en lo básico                           | Parecida, pero más flexible            |
| **Uso típico**       | Backend, apps de escritorio, móviles (Android) | Web frontend, apps web, scripts        |
| **Velocidad**        | Más rápido y robusto                           | Más ligero, enfocado en interactividad |


📌 Ambos usan estructuras como funciones, bucles, condiciones… pero son mundos distintos.

3. README – HTML, CSS y JS para principiantes
# 💻 Introducción a HTML, CSS y JavaScript

Este README es una guía rápida para quienes vienen del mundo Java y quieren iniciarse en el desarrollo web.

## 🌐 HTML - Estructura
Define el contenido y la jerarquía de una página.

html
<!DOCTYPE html>
<html>
  <head>
    <title>Mi Sitio Web</title>
  </head>
  <body>
    <h1>¡Hola Mundo!</h1>
    <p>Hecho con HTML</p>
  </body>
</html>

🎨 CSS - Estilo
Aplica diseño visual a los elementos HTML.

body {
  background-color: #f0f0f0;
  font-family: sans-serif;
}

h1 {
  color: darkblue;
}

⚙️ JavaScript - Comportamiento
Agrega interactividad y lógica.

document.querySelector("h1").addEventListener("click", function () {
  alert("¡Clickeaste el título!");
});


🔁 ¿Y qué tiene que ver esto con Java?
Aunque Java y JS tienen nombres similares, en realidad son tecnologías diferentes. Si vienes de Java, te será fácil entender la lógica, pero deberás adaptarte a la flexibilidad y dinamismo de JS.

