# pythonprojects
Python Portfolio
Proyecto 1: Gestor de archivos personalizable CLI

    Fase 1: Básico
        Crear, leer, eliminar archivos y directorios.
        Listar el contenido de un directorio.
    Fase 2: Avanzado
        Renombrar, mover y copiar archivos y directorios.
        Crear estructuras de directorios recursivamente.
        Buscar archivos por nombre, extensión, contenido o fecha de modificación.
        Comprimir y descomprimir archivos.
    Fase 3: Personalización
        Configurar el gestor a través de un archivo de configuración (JSON o YAML).
        Agregar alias para comandos comunes.
        Crear plantillas para nuevos archivos y directorios.
    Fase 4: Cloud Storage
        Integrar con un servicio de almacenamiento en la nube (S3) para subir, descargar y sincronizar archivos.
        Implementar funcionalidades de backup y restauración.
    Fase 5: Metadatos
        Asociar metadatos a los archivos (etiquetas, descripciones, autores).
        Buscar archivos por metadatos.
    Fase 6: Versionado
        Implementar un sistema básico de control de versiones para los archivos.
        Guardar versiones anteriores de los archivos.
    Fase transversal
        Test unitarios y de integración.
        Gestión de versiones de código.
    Tecnologías: Python, manejo de archivos y directorios, S3, JSON, YAML, CLI, Docker, Pytest.

Proyecto 2: API REST para gestión de tareas

    Fase 1: CRUD básico
        Modelar tareas con propiedades básicas (título, descripción, fecha de vencimiento, prioridad).
        Crear, leer, actualizar y eliminar tareas.
        Modelar usuarios con propiedades básicas (nombre, rol).
        Crear, leer, actualizar y eliminar usuarios.
    Fase 2: Autenticación y autorización
        Implementar un sistema de autenticación basado en tokens (JWT).
        Definir roles de usuarios y permisos para acceder a diferentes recursos.
    Fase 3: Relaciones y etiquetas
        Agregar relaciones entre tareas (subtareas, dependencias).
        Implementar etiquetas para organizar las tareas.
        Asignar tareas a usuarios.
    Fase 4: Búsqueda y filtrado
        Implementar una búsqueda avanzada por título, descripción, etiquetas y otros criterios.
        Permitir filtrar las tareas por estado (pendiente, en progreso, completada).
    Fase 5: Escalabilidad
        Utilizar un ORM para gestionar la base de datos de forma más eficiente.
        Implementar paginación para manejar grandes conjuntos de datos.
    Fase 6: Notificaciones
        Enviar notificaciones por correo electrónico cuando se cumplan ciertas condiciones (tareas vencidas, nuevas tareas asignadas).
    Fase 7: Integración con calendarios
        Sincronizar las tareas con un calendario externo (Google Calendar, Outlook).
    Fase 8: Reportes
        Generar informes sobre el progreso de las tareas en PDF y HTML.
    Fase Transversal
        Test unitarios y de integración.
        Gestión de versiones de código.
    Tecnologías: FastAPI, bases de datos relacionales (PostgreSQL, MySQL), autenticación y permisos, JSON, templates, Docker, Pytest, Git.

Proyecto 3: Web scraper para análisis de datos

    Fase 1: Extracción simple
        Extraer texto y enlaces de una página web utilizando Beautiful Soup.
        Guardar los datos extraídos en un archivo CSV.
    Fase 2: Estructura de datos
        Parsear HTML utilizando parsers más robustos como lxml.
        Extraer datos de tablas, formularios y otros elementos HTML.
        Almacenar los datos en una base de datos (MongoDB).
    Fase 3: Limpieza y transformación
        Limpiar los datos (eliminar etiquetas HTML, normalizar texto, manejar valores faltantes).
        Transformar los datos para análisis (calcular estadísticas, crear nuevas características).
    Fase 4: Visualización
        Crear gráficos simples para visualizar los datos (histogramas, gráficos de línea).
    Fase transversal
        Gestión de versiones de código.
    Tecnologías: Beautiful Soup, Scrapy, bases de datos no relacionales (MongoDB), Python, Docker, Git.

Proyecto 4: Aplicación de clima basada en API

Este proyecto te permitirá practicar el consumo de APIs externas, el manejo de datos JSON y la creación de interfaces de usuario sencillas.

    Fase 1: Selección de la API
        Investiga y selecciona una API de clima gratuita (OpenWeatherMap, WeatherAPI, etc.).
        Familiarízate con la documentación de la API para entender cómo hacer las solicitudes y qué datos proporciona.
    Fase 2: Diseño de la interfaz
        Elige una biblioteca para crear la interfaz de usuario (Tkinter, PyQt, Kivy, etc.).
        Diseña una interfaz sencilla que permita al usuario introducir una ciudad y obtener información del clima.
    Fase 3: Consumo de la API
        Utiliza la biblioteca requests de Python para hacer solicitudes HTTP a la API.
        Parsea la respuesta JSON para extraer los datos relevantes (temperatura, humedad, condiciones climáticas, etc.).
    Fase 4: Presentación de datos
        Muestra los datos obtenidos de la API en la interfaz de usuario de forma clara y concisa.
        Puedes utilizar gráficos o iconos para visualizar los datos de manera más atractiva.
    Fase 5: Funcionalidades adicionales
        Pronóstico: Muestra el pronóstico del tiempo para los próximos días.
        Unidades de medida: Permite al usuario seleccionar entre diferentes unidades de medida (Celsius, Fahrenheit).
        Ubicación actual: Utiliza la geolocalización para obtener el clima de la ubicación actual del usuario.
        Almacenamiento de favoritos: Permite al usuario guardar sus ciudades favoritas para acceder a ellas rápidamente.
    Fase transversal:
        Gestión de versiones de código.
        Test unitarios y test de integración.
    Tecnologías: Python, requests, Biblioteca de interfaz gráfica: Tkinter, PyQt, Kivy, etc. JSON, Pytest.

Proyecto 5: Edición de un proyecto existente

PENDIENTE DE DEFINIR. La idea de este proyecto es dar un proyecto existente al que se le deben de resolver bugs y añadir nuevas funcionalidades.
