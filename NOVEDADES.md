## 1.0.8 — Ágora honesta, Leer PDF, ruff y «Donar» con su palabra

**Descargar:** [Hefesto-v1.0.8.apk](https://github.com/ortiz1022009/Hefesto/releases/download/v1.0.8/Hefesto-v1.0.8.apk) · 125,0 MB · Android 8.0+ · 64 bits

### Nuevo

- **Leer PDF en Ágora:** saca el texto de un PDF, cuenta sus páginas o pasa una a imagen, sin abrir otro programa.
- **ruff en Ágora:** revisa el Python del proyecto y corrige solo lo que son tonterías, antes de que lo veas tú.

### Corregido

- **Ágora deja de mentir:** si un programa se cae a mitad, ya no pone «terminó bien». Explica si fue la descarga o si el programa no arranca en tu teléfono, y dice si merece la pena reintentar.
- **Chromium:** dejaba de estar «instalado» sin tener el navegador dentro, y al pulsar no pasaba nada. Ahora solo cuenta como instalado cuando el navegador está de verdad.
- **La app gasta menos batería en segundo plano:** un registro interno despertaba cuatro veces por segundo aunque no hubiera nada que apuntar.
- **Espacio:** si una pieza no cabe en el teléfono, la app lo dice antes de empezar a bajarla y te lleva a liberar espacio, en vez de dejar una descarga que se muere a medias sin explicar nada.
- **Descargas:** el panel enseña cada herramienta con su icono, como en Ágora, en vez del mismo dibujo de nube para todas.
- **Los iconos de Leer PDF y de ruff:** ahora cada una tiene el suyo, distinto del resto.
- **Chromium ya se instala:** el instalador moría con un error de sintaxis en el guion antes de bajar nada, y cuando la descarga fallaba lo tapaba. Ahora si falla dice por qué y cómo arreglarlo.
- **ruff ya se instala:** decía que la descarga no cuadraba con su huella cuando el problema era que la app no la había rellenado. Tu descarga estaba bien.
- **Donar:** fuera «invitar un café» (nadie que no conozca Ko-fi entiende qué es) y fuera el botón escondido de la barra. Ahora está en el menú ⋮ con su palabra, y en Ajustes › Apoyar el proyecto, con las formas de ayudar que no cuestan nada.
- **Logo de Ko-fi:** era una imitación con un corazón pegado. Ahora es el de verdad, con su naranja #FF5A16.
- **Después de un trabajo largo:** si sale bien, un renglón pregunta si quieres donar. Una vez cada quince días, y «Ahora no» lo apaga para siempre.
- **El botón de donar:** dice «Donar» con su palabra en la barra, y los botones de GitHub ya no salen cortados («Dale una»).

## 1.0.7 — tu idioma, tu modelo propio y Ágora que avisa

**Descargar:** [Hefesto-v1.0.7.apk](https://github.com/ortiz1022009/Hefesto/releases/download/v1.0.7/Hefesto-v1.0.7.apk) · 125,0 MB · Android 8.0+ · 64 bits

### Nuevo

- **Idioma con ficha propia:** en Ajustes tiene su sitio, ya no está escondido dentro de Apariencia, y se busca como los demás ajustes.
- **glTF-Transform en Ágora:** mira qué lleva dentro un modelo 3D, límpialo y aligéralo sin abrir otro programa.
- **Foto de perfil de GitHub:** tu tarjeta de la cuenta enseña tu foto; si no hay foto o no hay conexión, queda la inicial de siempre.
- **Modelo propio (.gguf):** ahora con su apartado, debajo del catálogo, y «Borrar caché» en Ajustes › Almacenamiento.
- **Contar un problema con fotos y vídeos:** se puede enseñar lo que pasó. Hasta 3 archivos, con el correo opcional para poder responderte.

### Mejoras

- **Hefesto habla tu idioma:** los agentes contestan en el idioma en que les escribes, aunque la app esté en otro.
- **Ajustes se encuentra solo:** el buscador entiende palabras a medias («notif» encuentra las notificaciones) y pone primero lo que más encaja.
- **Todo a mano mientras el agente trabaja:** enviar, aprobar un plan, deshacer cambios, instalar una pieza o pedir correcciones ya no se bloquean.
- **La interfaz se queda quieta:** los nombres largos del chat se cortan con puntos suspensivos y la cola de mensajes ocupa un solo renglón.
- **El avance de una descarga ya no se queda en 0 %:** sale de lo que dicen las herramientas y es la misma cifra en la ficha y en el aviso.
- **Piezas con nombre propio:** glTF-Transform, Node.js, pandoc, FFmpeg… con lo que hacen debajo; «no cabe» pasa a «no va en este teléfono», con su explicación.
- **Actualizaciones con nombre propio:** la ficha dice «Actualizable» con su peso y la descarga se llama «Actualizando…». El catálogo tiene su filtro.
- **Archivos abre antes:** la lista primero y los recuentos después. Apariencia, ordenada en cuatro grupos.
- **Ágora avisa desde lejos:** el punto del icono late mientras algo baja o espera en la cola, y Ágora enseña lo que baja, lo que espera, lo que se puede actualizar y lo último que falló.
- **Cambiar de agente sin salir de donde estás:** «Usar» elige el motor y te deja en la misma pantalla; para ir al chat está su botón.
- **Instalar ya no se queda a medias:** el botón dice «Instalando…» y no acepta un segundo toque mientras la pieza trabaja.

### Corregido

- **Nombres cortados:** el motor y el modelo ya no se quedan a medias en la barra del chat cuando el texto no cabe.
- **Voz y avisos:** al pausar o parar la lectura la app ya no se queda parada unos segundos, y los avisos de Git dicen qué falló.
- **APK externo sin permiso:** el aviso dice qué activar y trae «Abrir Ajustes», en vez de no pasar nada y tener que tocar dos veces.
- **Hefesto local se desinstala de verdad:** borra su servidor y lo cuenta paso a paso; antes avisaba y no quitaba nada, y la ficha seguía como si estuviera puesto.
- **Panel de descargas con tarjetas:** cada pieza con su icono y su estado, se puede abrir mientras baja o al terminar, y «Comprobar de nuevo» dice qué encontró.

## 1.0.6 — contexto local y correcciones de agentes

**Descargar:** [Hefesto-v1.0.6.apk](https://github.com/ortiz1022009/Hefesto/releases/download/v1.0.6/Hefesto-v1.0.6.apk) · 124,8 MB · Android 8.0+ · 64 bits

### Corregido

- **Contexto y rendimiento local:** Configura el contexto, los hilos y la caché comprimida desde la ficha de Hefesto local. Consulta el contexto efectivo del modelo y cuándo se aplican los cambios.
- **Peticiones locales más ajustadas:** El cálculo reserva espacio para las herramientas, además de las instrucciones y la conversación, para reducir errores por falta de contexto.
- **Avisos de contexto:** Se corrige la recomendación de un contexto insuficiente y se añade un acceso a su configuración desde el aviso.
- **Razonamiento de Antigravity:** Consulta los niveles compatibles y guarda la elección por modelo. Si no se pueden comprobar, permite usar el predeterminado sin ofrecer niveles sin confirmar.
- **Mantenimiento de agentes:** Actualiza OpenCode desde su ficha y consulta la cuota de Antigravity y sus renovaciones.
- **Conexiones e informes:** Las pruebas fallidas muestran detalles copiables con las claves tachadas. Ayuda permite consultar y preparar el informe de un cierre inesperado para enviarlo voluntariamente.

## 1.0.5 — gdtoolkit y más control sobre archivos y vistas

**Descargar:** [Hefesto-v1.0.5.apk](https://github.com/ortiz1022009/Hefesto/releases/download/v1.0.5/Hefesto-v1.0.5.apk) · 124,8 MB · Android 8.0+ · 64 bits

### Nuevo

- **Nueva pieza gdtoolkit:** Revisa y formatea GDScript sin sustituir las pruebas de Godot.
- **Guardar archivos:** Guarda un archivo en el destino que elijas, sin exportar todo el proyecto.
- **Código y resultado:** Alterna entre el código y su resultado en SVG, HTML, Markdown, JSON y CSV. HTML y SVG se muestran sin ejecutar scripts.

### Mejoras

- **Zoom y gestos:** Las imágenes se amplían sin tapar las barras. Pellizca, arrastra, toca dos veces o desliza sin zoom para pasar a otra imagen de la carpeta.
- **Hojas y secuencias:** Primero se muestra la imagen completa. Elige una hoja con su cuadrícula o una secuencia numerada; la rejilla señala el fotograma real y los controles son compactos.
- **Novedades con títulos:** Cada punto de esta versión tiene un título propio y una explicación completa, sin repetirla ni convertirla en un título recortado.
- **Caché de compilación:** Las nuevas plantillas Android permiten a Gradle reutilizar las tareas que no han cambiado.
- **Mensajes completos:** Los mensajes del usuario se muestran íntegros y permiten seleccionar y copiar su texto.
- **Documentos grandes:** Documentos por páginas y menos recorridos repetidos al abrir Archivos y detectar proyectos.
- **Chat más completo:** Listas anidadas, citas, tareas y tablas con desplazamiento propio. Lectura por partes, borradores y cola recuperable por conversación.
- **Colores de código:** Se amplía el resaltado y se prepara de forma incremental, sin recortar las líneas largas.
- **Taller compacto:** Taller más ordenado, acciones compactas y último destino recordado por proyecto.

### Corregido

- **Actividad de Antigravity:** Las herramientas avisan al empezar y terminar. La espera sin señales ya no se atribuye a saturación del modelo sin pruebas.
- **Visor SVG y carpetas:** El visor SVG mantiene los controles ante un fallo; las carpetas muestran su cantidad de elementos también cerradas, sin bloquear la interfaz.
- **Emuladores de 64 bits:** Ubuntu x86_64 incluido en el APK para preparar el entorno Linux en emuladores compatibles de 64 bits.
- **Salida de Vista:** Al salir desde Vista se libera el visor; al volver a la aplicación se abre Chat.
- **Archivos protegidos:** Protección de archivos grandes en Plan y Revisar, también al detener; se conservan los cambios aprobados.
- **Respuestas de OpenCode:** OpenCode deja de mostrar resúmenes internos como respuestas y evita recargas por simples consultas.
- **Entorno y diagnóstico:** Arquitectura real del dispositivo, preservación de la base Ubuntu anterior y botón para copiar el registro.
- **Reintentos y Godot:** Reintentar pide conservar lo hecho; Godot no recibe la orden de exportar si no lo pediste.

## 1.0.4 — El Ágora con cara nueva y avisos que llegan

- **Ágora más bonita:** Las portadas de la tienda se funden con la página, las cartas flotan con una sombra suave y cada pieza muestra su estado y su peso de un vistazo.
- **uv:** Nueva pieza que maneja las dependencias de Python en segundos, compatible con pip.
- **Avisos fuera de la app:** Si el agente te pide un permiso mientras estás en otra app, Hefesto te avisa con una notificación y puedes responder desde ahí, con confirmación de dos toques para que nada pase por accidente.
- **Terminal y teclado:** La terminal se adapta al teclado al escribir y no deja nada tapado.
- **PostgreSQL arreglado:** Vuelve a crear y arrancar su servidor en los teléfonos donde se quedaba a medias.
- **Se instala encima:** No se pierde nada.

## 1.0.3 — Ágora se instala bien y más formas de arreglarlo

- **Instalador más robusto:** Las herramientas del Ágora vuelven a instalar bien en los teléfonos donde fallaban con «código 100» (PHP, .NET, Godot, Chromium…). La pieza que faltaba (dbus) viene ahora de fábrica en el Linux de Hefesto, y si un paquete se queda a medias, el instalador lo reconfigura y reintenta solo.
- **Soporte y red:** Al contar un problema puedes dejar tu correo para recibir respuesta. Si tu red no deja bajar las herramientas grandes (Gradle, Node, Kotlin…), puedes importar el archivo oficial bajado en otro equipo: la ficha lo deja instalado y la tienda lo reconoce.
- **Se instala encima:** No se pierde nada.

## 1.0.2 — La terminal vuelve a funcionar

- **WebView compatible:** En teléfonos donde la terminal se quedaba en blanco por un WebView antiguo del sistema, ahora vuelve a funcionar en Android 8 y posteriores.
- **Errores visibles:** Si algo llega a fallar, la propia pantalla indica el motivo y cómo salir del paso — nunca otra pantalla muda.
- **Se instala encima:** No se pierde nada.

## 1.0.1 — Arreglo para proveedores compatibles con OpenAI

- **Servidor siempre visible:** Los proveedores personalizados compatibles con OpenAI (Zhipu GLM, OpenRouter, servidor propio...) ya tienen siempre visible el campo «Servidor» junto a la clave. Antes estaba oculto tras el modo desarrollador. Se instala encima de la 1.0, sin perder nada.

## 1.0 — la primera versión estable

La 1.0, con cara nueva. Esto es lo que hay dentro:

- Hefesto 1.0 está aquí: la primera versión estable. Pides con tus palabras y el agente crea páginas
  web, aplicaciones Android y videojuegos Godot 4: escribe, ejecuta, corrige y compila — el APK sale
  del teléfono.
- Dentro hay un taller: Ubuntu con terminal de pestañas, apt, Python, Node, Go, Rust y PHP. El Ágora
  instala herramientas con un toque (Godot, Blender, intérpretes) y el agente las usa si las necesita.
- El agente a tu manera: Antigravity y OpenCode con tu cuenta, o el agente de Hefesto con tu clave
  (OpenAI, Google, Anthropic, OpenRouter) o un modelo local en el teléfono. Revisar, Plan y Auto: tú
  decides cuánta rienda.
- El agente mira y corrige: ve la vista previa y el juego, y arregla lo que falla. Git y GitHub van
  dentro: clonar, ramas, pull requests y publicar tu web en Pages.
- Pensada para el día a día: biblioteca de material libre con visor 3D, catorce idiomas, apariencia a
  tu gusto, copias de seguridad cada pocos días — y muchas más mejoras de calidad de vida en cada
  rincón de la app.
