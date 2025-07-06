# Kaesar Stats Sports 🥊 (v1.8)

La herramienta de análisis de rendimiento definitiva para atletas de Boxeo, MMA y otros deportes de combate. Creada por un luchador, para luchadores.

![Captura de pantalla de Kaesar Stats Sports](https://cdn.discordapp.com/attachments/1390704865998799000/1391390157382619238/image.png?ex=686bb890&is=686a6710&hm=51740d14d23ff65bb1d0ab9e08a38c5d07b85575dfaf999cc493f53c2839489a&)
*(Nota: Sube una captura de pantalla de la v1.8 a un sitio como Imgur y reemplaza el enlace de arriba)*

---

## ¿Qué es Kaesar Stats Sports?

**Kaesar Stats Sports** es una aplicación de escritorio diseñada específicamente para las necesidades de los atletas de deportes de combate. Transforma los datos de frecuencia cardíaca de tus archivos de entrenamiento (`.fit` y `.tcx`) en un análisis profundo de tu rendimiento, tu estado de forma y tu capacidad de recuperación. Su motor de "Consejos IA" no se limita a mostrar datos, sino que interpreta tu estado físico actual y tu progreso para ofrecerte un informe claro y recomendaciones accionables, como si tuvieras un preparador físico personal analizando tu progreso.

## Características Principales

Esta aplicación está cargada de funcionalidades de nivel profesional, diseñadas para darte una visión completa de tu rendimiento:

* **Gestión de Perfiles Avanzada:**
    * Crea, carga y **elimina perfiles de forma segura**.
    * Cada perfil guarda su propia base de datos y configuración personal (FC Máxima).
    * La carpeta de perfiles (`.profiles`) se mantiene oculta para una mayor limpieza del directorio.

* **Importación de Datos Inteligente:**
    * **Importación Múltiple:** Añade varias sesiones de entrenamiento a la vez.
    * **Clasificación de Sesiones:** La aplicación te pregunta el tipo de entrenamiento (Boxeo, Correr, etc.) y aplica los análisis más profundos solo a las sesiones de combate.
    * **Etiquetado Visual:** Las sesiones se marcan con un prefijo (`[B]` para Boxeo, `[O]` para Otro) para una fácil identificación.
    * Soporte universal para archivos `.fit` y `.tcx`.

* **Visualización y Análisis de Élite:**
    * **Análisis Detallado para Combate:** Gráficos interactivos de frecuencia cardíaca con detección automática de picos (esfuerzo) y valles (descanso) para analizar cada asalto.
    * **Tabla de Recuperación entre Asaltos:** Cuantifica tu capacidad de recuperación entre rounds, una métrica clave.
    * **Comparativa de Sesiones:** Selecciona varias sesiones para comparar su carga, eficiencia y tiempo en zonas de FC en gráficos y tablas claras.

* **Métricas de Rendimiento Profesional:**
    * **TRIMP:** Cuantifica la carga de cada entrenamiento.
    * **CTL, ATL y TSB (Fitness, Fatiga y Forma):** Implementación del modelo de Bannister con medias móviles exponenciales para monitorizar tu estado de forma, predecir picos y evitar el sobreentrenamiento.
    * **Simulación de Forma:** Una gráfica que predice la evolución de tu estado físico en las próximas 2 semanas, ideal para planificar descansos (*tapering*).
    * **Desacoplamiento Cardíaco:** Métrica avanzada para evaluar tu resistencia aeróbica en sesiones de boxeo.

* **El Coach IA v2.0:**
    * Un motor de lógica mejorado que genera un **informe de rendimiento** en formato conversacional y fácil de entender.
    * **Análisis Contextual:** Ofrece diferentes consejos según el número de sesiones disponibles.
    * **Diagnóstico de Estado de Forma:** Te dice si estás fresco, en fase de carga, fatigado o en riesgo de sobreentrenamiento, usando un código de colores.
    * **Análisis de Tendencias:** Con suficientes datos, analiza la evolución de tu eficiencia para confirmar tu progreso.
    * **Recomendaciones Claras:** Basado en todos tus datos, te ofrece un plan de acción para tu siguiente entrenamiento (ej: "Prioriza el descanso", "Momento ideal para un entrenamiento de alta intensidad").

## ¿Para Quién Es Esta Aplicación?

Esta herramienta es ideal para cualquier luchador amateur o semi-profesional de **Boxeo, Kickboxing, Muay Thai, MMA** o cualquier arte marcial de alta intensidad que quiera:
* Entender en profundidad el efecto de cada entrenamiento.
* Monitorizar su progreso de forma objetiva.
* Equilibrar la carga de entrenamiento y el descanso para llegar a los combates en pico de forma.
* Llevar un registro detallado y profesional de todas sus sesiones.

## Descarga e Instalación

Al ser un proyecto de código cerrado, no se comparte el código fuente. Puedes descargar la última versión del programa ejecutable para Windows desde la sección **"Releases"** en esta misma página de GitHub.

1.  Ve a la pestaña **[Releases](https://github.com/tu-usuario/tu-repositorio/releases)**.
2.  Descarga el archivo `Kaesar_Stats_Sports_v1.8.zip` (o la versión más reciente).
3.  Descomprime el archivo y ejecuta el programa. ¡No necesita instalación!

## Guía Rápida de Uso

1.  Al abrir la app, **crea tu perfil** con tu nombre y año de nacimiento.
2.  Una vez cargado tu perfil, haz clic en **"Añadir Sesión (+)"** para importar uno o más archivos `.fit` o `.tcx`.
3.  Para cada archivo, especifica el **tipo de entrenamiento** (ej: "Boxeo").
4.  **Selecciona la sesión(es)** en la lista de la izquierda y explora las diferentes pestañas para ver el análisis.

## Feedback y Errores

Si encuentras algún error o tienes alguna sugerencia, por favor, abre un nuevo "Issue" en la pestaña **[Issues](https://github.com/tu-usuario/tu-repositorio/issues)** de este repositorio.

---

**Autor:** César García Galindo
