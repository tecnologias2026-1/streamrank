

🌐 Stream Rank

Escribe aquí una descripción corta del proyecto.

👥 Integrantes


Paula Yurany Romero Rojas
Laura Segura Castañeda-1202752
Nicole Camila Enciso Velandia-1202795


🎯 1. Objetivo General

El objetivo del proyecto es diseñar y desarrollar una aplicación web llamada StreamRank, capaz de recolectar automáticamente información pública de rankings de películas y series en portales especializados como IMDb y Rotten Tomatoes, procesarla y presentarla en listados dinámicos y personalizados. Con este sistema se busca solucionar el problema de la sobreoferta de contenido audiovisual distribuido en múltiples plataformas, que dificulta a los usuarios encontrar rápidamente opciones relevantes según sus intereses. La aplicación permitirá no solo explorar tendencias actuales mediante filtros por género, duración, popularidad o plataforma, sino también organizar el consumo personal de contenido a través de herramientas como listas de “Ver después”, registro de películas vistas, calificaciones personales y creación de rankings propios. De esta manera, el sistema combina descubrimiento de tendencias con gestión personalizada, ofreciendo una solución integral para navegar de forma clara y estructurada en el creciente universo audiovisual.


🌍 2. Contexto de Uso

El sistema está orientado a usuarios que consumen regularmente películas y series y que desean descubrir tendencias actuales sin perder tiempo en búsquedas dispersas entre distintas plataformas. Se utilizará principalmente como una aplicación web accesible desde cualquier navegador en computadores, tablets y dispositivos móviles, con una interfaz moderna, intuitiva y adaptable (responsive design). Los usuarios podrán consultar rankings dinámicos, aplicar filtros avanzados, explorar categorías específicas como estudios, franquicias o plataformas, visualizar trailers y organizar su propio contenido mediante watchlists, calificaciones y rankings personalizados. El sistema será útil tanto para quienes buscan recomendaciones rápidas y confiables como para aquellos que desean llevar un registro detallado de su consumo audiovisual, convirtiéndose en una herramienta práctica para explorar, decidir y gestionar películas y series en un solo espacio centralizado.

📋 3. Requerimientos del Sistema
3.1 Requerimientos Funcionales

RF1. Registro de usuario
	 El sistema debe permitir al usuario crear una cuenta para guardar su información y listas personales.
   
RF2. Inicio de sesión
 	El sistema debe permitir al usuario autenticarse para acceder a sus listas y configuraciones.
  
RF3. Gestión de perfil
	 El usuario debe poder acceder a su perfil para visualizar sus listas, calificaciones y contenido guardado.
   
RF4. Visualización de rankings
	 El sistema debe mostrar Top 10 dinámicos de películas y series obtenidos mediante web scraping.
   
RF5. Filtrar por tipo de contenido
	 El sistema debe permitir filtrar contenido por:
Películas
Series

RF6. Filtrar por género
	 El sistema debe permitir filtrar contenido por género:
Acción
Drama
Comedia
Terror
Otros disponibles

RF7. Filtrar por duración
 	El sistema debe permitir filtrar películas por duración:
Cortas (< 90 min)
Medias (90 – 120 min)
Largas (> 120 min)

RF8. Ordenar rankings
	 El sistema debe permitir ordenar los resultados por:
Rating
Popularidad

RF9. Explorar Top por estudio
	 El sistema debe permitir visualizar rankings por estudios o productoras.
Ejemplo:
Warner
Pixar

RF10. Explorar Top por plataforma
	 El sistema debe permitir visualizar rankings por plataforma de streaming.
Ejemplo:
Netflix
Amazon Prime

RF11. Explorar Top por franquicia o saga
	 El sistema debe permitir visualizar rankings de películas pertenecientes a universos o sagas.
Ejemplo:
Star Wars
Harry Potter

RF12. Visualización de tarjetas de contenido
	 El sistema debe mostrar la información de cada película o serie en tarjetas que incluyan:
Imagen
Título
Rating
Sinopsis corta
Plataforma disponible

RF13. Visualización de trailer
	 El sistema debe permitir reproducir el trailer al hacer clic en la imagen de la película o serie.
   
RF14. Búsqueda de películas o series
	 El sistema debe permitir al usuario buscar contenido por nombre.
   
RF15. Visualización de resultados de búsqueda
	 El sistema debe mostrar la información de la película o serie encontrada.
   
RF16. Crear lista de “Ver después” (Watchlist)
 	El sistema debe permitir guardar películas o series para ver más adelante.
  
RF17. Marcar contenido como visto
	 El sistema debe permitir marcar películas o series como vistas.
   
RF18. Calificación personal
	 El usuario debe poder calificar el contenido visto mediante un sistema de estrellas.
   
RF19. Ordenar contenido por calificación personal
	 El sistema debe permitir ordenar el contenido visto según la calificación del usuario.
   
RF20. Seguimiento de series
	 El sistema debe permitir al usuario registrar:
temporada actual
episodio actual

RF21. Crear Top 10 personal
	 El sistema debe permitir al usuario crear listas personalizadas de películas o series.
   
RF22. Agregar contenido a Top personal
	 El usuario debe poder agregar películas o series a sus rankings personales.
   
RF23. Ordenar manualmente el ranking
	 El usuario debe poder organizar manualmente el orden del Top 10.
   
RF24. Web scraping automático
	 El sistema debe recolectar información pública de sitios como IMDb y Rotten Tomatoes mediante scraping.
   
RF25. Extracción de datos
 El sistema debe extraer y almacenar información como:
título
rating
género
duración
imagen
sinopsis
enlace
trailer
plataforma (si aparece)


3.2 Requerimientos No Funcionales

RNF1. Usabilidad
La aplicación deberá contar con una interfaz clara, intuitiva y de fácil navegación, permitiendo al usuario explorar rankings, aplicar filtros y organizar su contenido personal de forma sencilla.

RNF2. Rendimiento
El sistema deberá generar los rankings y resultados de búsqueda en un tiempo de respuesta adecuado (máximo 3 segundos), evitando la ejecución de procesos de scraping en tiempo real durante cada consulta del usuario.

RNF3. Disponibilidad
La aplicación deberá estar disponible como un sistema web accesible desde cualquier navegador con conexión a internet.

RNF4. Escalabilidad
El sistema deberá permitir la incorporación futura de nuevas categorías, plataformas, fuentes de datos o criterios de filtrado sin requerir una reestructuración completa del sistema.

RNF5. Mantenibilidad
La aplicación deberá estar desarrollada bajo una arquitectura modular que facilite el mantenimiento, actualización de funcionalidades y mejora del sistema.

RNF6. Seguridad
El sistema deberá proteger la información de los usuarios registrados, evitando accesos no autorizados a sus listas personales, calificaciones y datos almacenados.

RNF7. Compatibilidad
La aplicación deberá funcionar correctamente en los principales navegadores web modernos, como Google Chrome, Mozilla Firefox, Microsoft Edge y Safari.

RNF8. Actualización de información
El sistema deberá actualizar periódicamente la información obtenida mediante scraping y permitir visualizar la fecha de la última actualización de los datos.

RNF9. Responsive Design
La interfaz de la aplicación deberá adaptarse correctamente a diferentes tamaños de pantalla, incluyendo computadores, tablets y dispositivos móviles.

RNF10. Persistencia de datos
El sistema deberá almacenar de manera segura la información generada por los usuarios, incluyendo:
watchlists
calificaciones
rankings personales
progreso de series.

RNF11. Integridad de datos
El sistema deberá garantizar que la información obtenida mediante scraping sea procesada y almacenada correctamente sin duplicaciones o inconsistencias.

RNF12. Eficiencia del scraping
Los procesos de scraping deberán ejecutarse de forma programada o en segundo plano para evitar sobrecargar el sistema o afectar la experiencia del usuario.

RNF13. Accesibilidad
La aplicación deberá mantener una estructura visual clara y legible que facilite la interacción de los usuarios con el contenido mostrado.


🧠 4. Diagramas UML

Diagrama de Casos de Uso

<img width="1064" height="399" alt="caso1" src="https://github.com/user-attachments/assets/c5866633-679b-4b75-92e0-b4a7c22ae646" />


Diagrama de Secuencia

Explicar qué proceso representa.

🎨 5. URL del Prototipo

Colocar aquí el enlace público de Figma:

https://figma.com/xxxxx


🗄️ 6. Diseño de Base de Datos

Agregar imagen del modelo.
Tablas principales

🧩 7. Documentación del Sistema
Estructura de Carpetas
/css
/js
/assets

Explicar brevemente qué contiene cada carpeta.

🚀 8. Instalación y Ejecución

Explicar cómo correr el proyecto.
