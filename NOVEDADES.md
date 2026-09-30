# Novedades

Lo que trae cada versión que se puede descargar. Cuentan lo que gana quien usa la app, no lo de
dentro.

## 0.5 (beta) — primera versión pública

Primera versión que se publica. **Está en pruebas**: puede cerrarse sola (sobre todo con el motor
local o al compilar, que es cuando más memoria se usa), alguna función puede quedarse a medias y hay
cosas por pulir. Lo que falle se puede contar desde la propia app, en **Ajustes → Ayuda y diagnóstico
→ Reportar un problema**, y sirve para arreglarlo en la siguiente versión.

**Agentes que trabajan de verdad**
- Cuatro motores: el agente integrado de Hefesto, Antigravity, OpenCode y **Hefesto local** (un modelo
  que funciona dentro del teléfono, sin internet y sin claves).
- El agente usa herramientas de verdad: leer y escribir archivos, ejecutar comandos, buscar y compilar.
- Modos de trabajo (plan, revisión y automático): se le puede pedir que avise antes de tocar archivos.

**Compilar en el teléfono**
- Entorno Linux propio dentro de la app (Alpine con proot): sin root y sin ordenador.
- Compilación de APK con Gradle, SDK de Android, Kotlin y Java, con el progreso a la vista y el error
  explicado cuando algo falla.
- Terminal y consola con los comandos reales.

**Hefesto local**
- Catálogo de modelos con tamaños para teléfonos modestos y para los que van sobrados.
- Aviso de tres colores de lo que aguanta tu teléfono, con la memoria y el espacio a la vista.
- Ajustes de memoria, contexto y procesador; borrar un modelo pide confirmación.
- Se pueden descargar desde la app o importar archivos `.gguf` que ya tengas.

**GitHub desde el móvil**
- Conectar la cuenta, clonar repositorios, commit, push y pull requests sin salir de la app.

**Archivos y proyectos**
- Editor, vista de árbol, búsqueda, proyectos fijados y copias de seguridad (proyecto, todos los
  proyectos o solo los ajustes).

**Idioma y aspecto**
- Español e inglés, tema claro y oscuro, y ajustes que se quedan guardados.

**Cosas de esta beta**
- Aviso de beta la primera vez que se abre cada versión, con lo que puede fallar y cómo reportarlo.
- Reporte de fallos desde la app: se manda con un toque, lleva el diagnóstico del teléfono y las
  claves de API se tachan solas antes de salir.
