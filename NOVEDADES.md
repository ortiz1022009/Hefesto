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
