## Tematica
Sistema de reservas de hoteles y busqueda de sitios turísticos EN ARGENTINA 
  
# Sistema de busquedad de sitios turisticos y reservas de hoteles EN ARGENTINA
- Materia:  P.D.I.S.C
- Curso: 7°1
- Grupo: 7.1
- Docente: Pablo Gareis

## Lenguajes de Programación
- Python + Django
- HTML5
- CSS3
- JavaScript

## Integrantes
- Camila Soliz: Backend y Líder
- César López: Encargado del Frontend
- Sofía Balcazar: Documentación y Marketing


# Manual Técnico: Proyecto Argentina Viajes

## 1. Introducción
El proyecto **Argenina Viajes** es una plataforma orientada a la gestión y visualización de información turística en Argentina. Este documento detalla la estructura, arquitectura y configuración del sistema.

## 2. Arquitectura del Proyecto
El sistema sigue una arquitectura modular, organizada bajo la carpeta `/Project`:
* **Modulo de Navegación (`mapa_navegacion`)**: Responsable de la lógica de rutas y la interfaz de usuario para el desplazamiento entre puntos de interés.
* **Modulo de Turismo (`turismo_argentina`)**: Contiene la lógica de negocio, datos y gestión de destinos turísticos.

## 3. Tecnologías Utilizadas
Dado el contexto del repositorio (estructura de archivos web/git), se asume el uso de:
* **Frontend**: HTML5, CSS3, JavaScript (o frameworks asociados).
* **Control de Versiones**: Git (incluye carpeta `.git`).

## 4. Estructura del Proyecto
```text
argenviajes/
├── .git/               # Configuración del control de versiones
├── Project/            # Directorio raíz del código fuente
│   ├── mapa_navegacion/ # Componente de rutas/mapas
│   └── turismo_argentina/ # Componente de gestión turística
└── README.md           # Documentación principal del usuario
```

## 5. Configuración Básica
1.  **Clonar el repositorio**: `git clone <url-del-repositorio>`
2.  **Entorno**: Asegurarse de tener un entorno de ejecución adecuado para archivos estáticos o el framework seleccionado.
3.  **Ejecución**: Revisar el `README.md` para comandos específicos de instalación de dependencias (npm/yarn si aplica).

## Lenguajes y Tecnologías
Lenguajes: Python (Django), HTML5, CSS3, JavaScript.

Control de Versiones: Git.

## Estructura de Carpetas y Archivos
Plaintext
argenviajes/
├── .git/                 # Configuración del control de versiones
├── Project/              # Directorio principal del código
│   ├── mapa_navegacion/  # Módulo de rutas y navegación
│   └── turismo_argentina/# Módulo de destinos turísticos
│   └── manage.py         # Script de gestión del proyecto
└── README.md             # Documentación del proyecto 

## Datos de Acceso de Usuario
Usuario: admin

Contraseña: 123456

## Cómo ejecutar el proyecto (Terminal)
Para poner en marcha el proyecto, sigue estos pasos desde la raíz de la carpeta argenviajes:

1. Navegación a la carpeta del proyecto
Ingresa a los directorios correspondientes para acceder al archivo de gestión:

- cd Project
- cd turismo_argentina
2. Ejecución del servidor
Una vez ubicado en el directorio, ejecuta los siguientes comandos:
Aplicar migraciones (necesario para la base de datos):

- python manage.py migrate

Ejecutar el servidor local:
- python manage.py runserver