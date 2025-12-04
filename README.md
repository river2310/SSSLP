🏥 Catálogo CLUES - Servicios de Salud San Luis Potosí

Este proyecto es un tablero interactivo (Dashboard) diseñado para visualizar, filtrar y localizar geográficamente las Unidades Médicas del Catálogo CLUES (Clave Única de Establecimientos de Salud) en el estado de San Luis Potosí.

La aplicación permite a los usuarios consultar información detallada sobre infraestructura, recursos humanos y ubicación de cada centro de salud, facilitando el análisis de datos mediante gráficas y mapas interactivos.

✨ Características Principales

🗺️ Mapa Interactivo: Visualización de unidades médicas utilizando Leaflet.js, con agrupación de marcadores (clusters) para un mejor rendimiento visual.

🔍 Filtros Dinámicos: Búsqueda en tiempo real por nombre, CLUES, institución, municipio y tipo de unidad.

📊 Visualización de Datos: Gráficas estadísticas (Donut y Barras) generadas con Chart.js para analizar la distribución por institución y municipio.

🏥 Detalle de Unidad: Ventana modal con información profunda:

Domicilio completo.

Recursos (consultorios, médicos, enfermeras, equipamiento).

Integración con Google Street View.

📍 Geolocalización y Rutas: Función para obtener la ruta desde la ubicación actual del usuario hacia la unidad médica seleccionada.

📥 Exportación de Datos: Capacidad para descargar los datos filtrados en formato CSV.

📱 Diseño Responsivo: Interfaz moderna y adaptable a dispositivos móviles utilizando Tailwind CSS.

🛠️ Tecnologías Utilizadas

Este proyecto funciona directamente en el navegador sin necesidad de procesos de compilación (build steps), utilizando las siguientes librerías vía CDN:

React 18: Biblioteca principal para la interfaz de usuario.

Tailwind CSS: Framework de estilos utilitarios.

Leaflet: Mapas interactivos open-source.

Chart.js: Visualización de datos y gráficas.

D3.js: Procesamiento y parseo de archivos CSV.

Babel Standalone: Para interpretar JSX directamente en el navegador.

📂 Fuente de Datos

Base de Datos Principal: Catálogo CLUES publicado por la Dirección General de Información en Salud (DGIS).

Base de Datos de Recursos: Subsistema de Información de Equipamiento, Recursos Humanos e Infraestructura para la Atención de la Salud (SINERHIAS).

📄 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo LICENSE.md para detalles.

Desarrollado con ❤️ para mejorar el acceso a la información de salud en SLP.
