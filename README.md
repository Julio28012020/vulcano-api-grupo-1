# VULCANO-API

[Plataforma de gamificación educativa para fortalecer la lógica de programación mediante desafíos interactivos]

## Introducción / Contexto

Descripción del problema: Los estudiantes de la carrera técnica en desarrollo de software enfrentan dificultades para consolidar conocimientos teóricos de la carrera de forma motivadora.

Justificación: Es relevante para promover la interacción y motivación mediante dinámicas lúdicas, reduciendo la brecha entre la teoría y la práctica creativa.

Descripción del dominio: El proyecto se centra en la educación técnica laboral, específicamente en el desarrollo de software y lógica de programación.

## Objetivos

Objetivo General
Desarrollar e implementar una plataforma web de gamificación académica orientada a la carrera técnica laboral en desarrollo de software, con el propósito de fortalecer el aprendizaje de los contenidos teóricos vistos durante la formación, mediante una arquitectura cliente–servidor que integre una interfaz interactiva desarrollada con React, JavaScript y Tailwind CSS, junto con una API REST construida con Java Spring Boot, JPA y Maven, gestionando el control de versiones del proyecto mediante GitHub.

Objetivos Específicos

OE1: Diseñar y planificar actividades lúdicas, tanto grupales como individuales, que refuercen los conocimientos adquiridos en las diferentes materias de la carrera, integrándolas en una interfaz web dinámica y responsiva.

OE2: Aplicar metodologías ágiles durante el desarrollo de la plataforma web para garantizar la adaptación continua a los requerimientos del sistema, optimizando los procesos de desarrollo, integración y despliegue.

OE3: Evaluar y ajustar de forma continua el funcionamiento de la plataforma mediante pruebas funcionales y retroalimentación de los usuarios, con el fin de mejorar la interacción entre el estudiante y los contenidos académicos.

OE4: Implementar funcionalidades interactivas mediante JavaScript que permitan la gestión de reseñas, la ejecución de desafíos académicos y la ejecución de código en tiempo real, apoyadas por una API REST desarrollada con Java Spring Boot para la administración de datos y lógica del sistema.

## Alcance del Proyecto (Scope)

Qué se va a desarrollar

1. Plataforma web interactiva
   Aplicación web construida con React y JavaScript, con diseño responsivo implementado mediante Tailwind CSS, orientada a la gamificación del aprendizaje en la carrera técnica en desarrollo de software.

2. Arquitectura cliente–servidor
   Implementación de una arquitectura basada en una API REST desarrollada con Java Spring Boot, utilizando JPA para la persistencia de datos y Maven para la gestión de dependencias y construcción del proyecto.

3. Gestión de datos con Prisma
   Integración de Prisma como motor de gestión de base de datos para el modelado, acceso y administración estructurada de la información académica (usuarios, reseñas, desafíos y progreso), garantizando persistencia y consistencia de los datos.

4. Sistema CRUD académico
   Desarrollo de funcionalidades completas de creación, consulta, actualización y eliminación (CRUD) para reseñas, contenidos académicos y desafíos, consumiendo la API REST desde el cliente React.

5. Módulo de desafíos interactivos
   Implementación de un módulo de retos académicos con editor de código en el navegador, validación de soluciones y visualización de resultados en tiempo real.

6. Sistema de autenticación de usuarios
   Formularios de registro e inicio de sesión con validaciones en el cliente y gestión de usuarios a través de la API backend.

7. Interfaz moderna y experiencia de usuario optimizada
   Diseño de componentes reutilizables, navegación responsiva, animaciones interactivas y estructura modular orientada a la escalabilidad del sistema.

8. Control de versiones y colaboración
   Gestión del código fuente mediante Git y GitHub, aplicando control de versiones, seguimiento de cambios y trabajo colaborativo bajo buenas prácticas de desarrollo.

Qué NO se va a desarrollar en esta versión (Fuera de Alcance)

1. Entorno de ejecución de código en servidor con sandbox seguro para múltiples lenguajes.

2. Sistema avanzado de evaluación automática con inteligencia artificial.

3. Aplicación móvil nativa.

4. Integraciones con plataformas educativas externas.

5. Sistema de analítica avanzada o panel administrativo con métricas complejas.

6. Despliegue en infraestructura productiva de alta disponibilidad.

## Tecnologías y Herramientas (Tech Stack)

1. Backend:
   API REST desarrollada con Java Spring Boot, utilizando JPA para la gestión de la persistencia de datos y Maven como herramienta de administración de dependencias, automatización de compilación y gestión del ciclo de vida del proyecto.

2. Frontend:
   Aplicación web construida con React y JavaScript (ES6+), con manejo de asincronía mediante Promises y Async/Await. La interfaz de usuario se implementa con Tailwind CSS para lograr un diseño responsivo, modular y escalable basado en componentes reutilizables.

3. Base de datos:
   Prisma como motor de acceso y modelado de datos, encargado de la comunicación estructurada con la base de datos relacional y de la gestión de entidades del sistema como usuarios, reseñas, desafíos y progreso académico.

4. Control de versiones y colaboración:
   Uso de Git para el control de versiones y de GitHub como plataforma central para la gestión del repositorio, seguimiento de cambios, integración del equipo de desarrollo y aplicación de buenas prácticas de trabajo colaborativo.

Otras herramientas y recursos técnicos:

Arquitectura cliente–servidor basada en consumo de API REST.

Diseño de componentes reutilizables y estructura modular del sistema.

Validaciones de formularios en el cliente.

Implementación de animaciones e interacciones dinámicas en la interfaz.
