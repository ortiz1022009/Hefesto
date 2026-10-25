# Privacidad

Versión 2 · 18 de octubre de 2026 · Vale para Hefesto 1.0 y posteriores.

## Lo esencial

Hefesto no recoge tus datos. No tiene cuentas, no tiene contadores de uso, no tiene publicidad ni analítica, y no hay ningún servidor del proyecto que reciba lo que haces en la app. Todo se queda en tu teléfono salvo lo que tú mandes fuera, y aquí está escrito, punto por punto, cuándo pasa eso.

## Qué se guarda en tu teléfono

- Tus proyectos, sus archivos, sus chats con el agente, su memoria (MEMORIA.md) y su papelera, en el almacenamiento privado de la app.
- Tus ajustes: apariencia, idioma, agente elegido, temas que guardes, fondos y portadas (se guarda una copia reducida de las imágenes que elijas).
- Tus claves de IA y de las fuentes de la Biblioteca, y el acceso a GitHub si lo conectas, cifrados y fuera de las copias de seguridad de Android.
- El entorno Linux, las herramientas del Ágora y los modelos que instales.
- El registro de actividad de la app y los informes de cierres inesperados, para que puedas revisar un fallo. No salen de ahí si no los envías tú.

Nada de esto se envía a ningún sitio por su cuenta. Al desinstalar la app, Android lo borra todo.

## Cuándo sale algo del teléfono

Solo cuando tú lo pides, y siempre a quien tú elijas:

- Agente con tu clave de IA: tu petición, el contexto del proyecto que el agente necesite leer y los adjuntos que le des van al proveedor de esa clave (OpenAI, Google, Anthropic, OpenRouter o el que configures), bajo sus condiciones. Hefesto no ve ni guarda esa conversación fuera de tu teléfono.
- Agentes externos (Antigravity, OpenCode, etc.): los instalas tú desde el Ágora y hablan con sus propios servicios con tu cuenta. Rigen sus condiciones.
- Modelos locales: corren en el teléfono. Descargarlos es una conexión con Hugging Face; usarlos no conecta a nada.
- GitHub: clonar, subir cambios o abrir pull requests usa tu cuenta de GitHub. Para conectarla sin meter secretos en la app, el canje de la autorización pasa por un pequeño intermediario del proyecto (un Worker de Cloudflare) que guarda el estado de ese paso durante cinco minutos y luego lo borra; nunca ve tu código ni tus archivos.
- Ágora y Biblioteca: descargar una herramienta o un material es una conexión con el servidor donde vive (GitHub, los repositorios de Ubuntu, Hugging Face, Sketchfab, Pexels, Pixabay, Freesound, Poly Haven…). Las fuentes con clave usan la clave que tú pusiste.
- Comprobar versión nueva: una consulta a GitHub por la lista de versiones publicadas. No lleva nada tuyo aparte de lo que cualquier conexión lleva (tu dirección IP).
- Reportar un problema: lo envías tú. Incluye lo que escribas, la versión de Hefesto y de Android, el modelo del teléfono, la memoria, el agente activo y las últimas líneas del registro. Las claves, tokens y contraseñas se tachan antes de salir, también si las pegaste sin querer. Ves el texto completo antes de enviarlo. Llega al correo del autor a través de un servicio de formularios; también puedes copiarlo o compartirlo por donde quieras en lugar de enviarlo.
- Apoyar el proyecto: el botón abre la página de Ko-fi en tu navegador. Lo que pase allí es entre Ko-fi y tú.

## Permisos

- Internet: para todo lo de arriba.
- Micrófono: solo para dictar en el chat, con el reconocedor de voz de tu teléfono. Se pide la primera vez que tocas el micrófono y se puede negar: la app sigue funcionando.
- Notificaciones: para avisarte cuando el agente termina, pide permiso o falla, y para seguir trabajando con la pantalla apagada.
- Cámara: Hefesto no pide el permiso de cámara. «Tomar foto» abre la app de cámara del teléfono y recibe la foto.
- Archivos: Hefesto usa el selector de Android. Solo toca los archivos que tú elijas abrir, importar o exportar.
- Instalar aplicaciones: para que puedas instalar los APK que compiles. Siempre a través del instalador de Android.
- Sin límites de batería (opcional): para que Android no corte una compilación o una respuesta larga.

## Menores

Hefesto no está dirigido a menores de 16 años y no pide datos a nadie.

## Tus derechos

Como Hefesto no guarda datos tuyos en ningún sitio, no hay nada que pedir ni que borrar fuera de tu teléfono. Para borrar lo que hay dentro: elimina los proyectos que quieras, borra el registro desde Ajustes › Ayuda, o desinstala la app. Si enviaste un reporte y quieres que se elimine, escribe desde Ajustes › Ayuda y se borra.

## Cambios

Si este texto cambia, cambia su número de versión y su fecha, y la app lo enseña con las novedades de la versión. Las versiones anteriores quedan en el historial del repositorio público.

## Contacto

Ajustes › Ayuda › Reportar un problema, o el repositorio público de Hefesto en GitHub.

---

# Privacy

Version 2 · 18 October 2026 · Applies to Hefesto 1.0 and later.

## The essentials

Hefesto does not collect your data. It has no accounts, no usage counters, no advertising or analytics, and there is no project server that receives what you do in the app. Everything stays on your phone except what you send out yourself, and here it is written, point by point, when that happens.

## What is stored on your phone

- Your projects, their files, their chats with the agent, their memory (MEMORIA.md) and their trash, in the app's private storage.
- Your settings: appearance, language, chosen agent, themes you save, backgrounds and covers (a reduced copy of the images you pick is kept).
- Your AI keys and Library source keys, and GitHub access if you connect it, encrypted and excluded from Android backups.
- The Linux environment, the Agora tools and the models you install.
- The app's activity log and crash reports, so you can look into a failure. They do not leave unless you send them.

None of this is sent anywhere on its own. When you uninstall the app, Android deletes it all.

## When something leaves the phone

Only when you ask, and always to whom you choose:

- Agent with your AI key: your request, the project context the agent needs to read and the attachments you give it go to the provider of that key (OpenAI, Google, Anthropic, OpenRouter or whichever you configure), under its terms. Hefesto does not see or keep that conversation outside your phone.
- External agents (Antigravity, OpenCode, etc.): you install them from the Agora and they talk to their own services with your account. Their terms apply.
- Local models: they run on the phone. Downloading them is a connection to Hugging Face; using them connects to nothing.
- GitHub: cloning, pushing changes or opening pull requests uses your GitHub account. To connect it without putting secrets in the app, the authorization exchange goes through a small project intermediary (a Cloudflare Worker) that keeps the state of that step for five minutes and then deletes it; it never sees your code or your files.
- Agora and Library: downloading a tool or an asset is a connection to the server where it lives (GitHub, the Ubuntu repositories, Hugging Face, Sketchfab, Pexels, Pixabay, Freesound, Poly Haven…). Sources with a key use the key you entered.
- Checking for a new version: one query to GitHub for the list of published releases. It carries nothing of yours beyond what any connection carries (your IP address).
- Reporting a problem: you send it. It includes what you write, the Hefesto and Android versions, the phone model, memory, the active agent and the last lines of the log. Keys, tokens and passwords are redacted before it leaves, even if you pasted them by mistake. You see the full text before sending. It reaches the author's email through a form service; you can also copy or share it any way you like instead of sending it.
- Supporting the project: the button opens the Ko-fi page in your browser. What happens there is between Ko-fi and you.

## Permissions

- Internet: for everything above.
- Microphone: only to dictate in the chat, with your phone's speech recognizer. It is requested the first time you tap the microphone and can be refused: the app keeps working.
- Notifications: to tell you when the agent finishes, asks for permission or fails, and to keep working with the screen off.
- Camera: Hefesto does not request the camera permission. "Take photo" opens the phone's camera app and receives the picture.
- Files: Hefesto uses the Android picker. It only touches the files you choose to open, import or export.
- Install apps: so you can install the APKs you build. Always through the Android installer.
- No battery limits (optional): so Android does not cut off a build or a long answer.

## Minors

Hefesto is not aimed at people under 16 and asks no one for data.

## Your rights

Since Hefesto keeps none of your data anywhere, there is nothing to request or delete outside your phone. To delete what is inside: remove the projects you want, clear the log from Settings › Help, or uninstall the app. If you sent a report and want it deleted, write from Settings › Help and it is removed.

## Changes

If this text changes, its version number and date change, and the app shows it with the release notes. Previous versions remain in the public repository's history.

## Contact

Settings › Help › Report a problem, or Hefesto's public repository on GitHub.
