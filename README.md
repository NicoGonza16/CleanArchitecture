* Este repositorio contiene la implementación de un proyecto basado en el patrón de Clean Architecture, desarrollado en .NET con el objetivo de construir una aplicación modular, mantenible y escalable.

La arquitectura separa las responsabilidades del sistema en diferentes capas, permitiendo mantener un bajo acoplamiento entre componentes y facilitando el mantenimiento, las pruebas y la evolución del software.

El proyecto implementa buenas prácticas de ingeniería de software como:

Clean Architecture

Repository Pattern

Dependency Injection

Entity Framework Core

Principios SOLID

Este repositorio forma parte de un proceso de aprendizaje y desarrollo dentro del área de Ingeniería de Sistemas, aplicando conceptos modernos de arquitectura de software.

* Arquitectura del Proyecto

El proyecto sigue el modelo de Clean Architecture, donde cada capa tiene responsabilidades claramente definidas.

CleanArchitecture
│
├── Domain
│   ├── Entities
│
├── Application
│   ├── Interfaces
│   ├── UseCases
│
├── Infrastructure
│   ├── Data
│   │   ├── Repositories
│   │   └── DbContext
│
└── API / Presentation

* Capas de la arquitectura
Domain

Contiene las entidades del dominio y la lógica central del negocio.

Application

Define los casos de uso del sistema y las interfaces que deben implementar las capas externas.

Infrastructure

Contiene las implementaciones técnicas, como el acceso a datos, repositorios y configuración de servicios.

Presentation / API

Capa encargada de la exposición de endpoints o interfaz de usuario.

Esta separación permite que la lógica de negocio sea independiente de frameworks o tecnologías externas.

* Tecnologías utilizadas

Este proyecto utiliza las siguientes tecnologías:

C#

.NET

ASP.NET Core

Entity Framework Core

SQL Server

Dependency Injection

Repository Pattern

Git

* AUTOR 

Nicolás González Varela

Estudiante de Ingeniería de Sistemas De la Universidad Unincca De Colombia, enfocado en desarrollo de software, arquitectura de aplicaciones y buenas prácticas de programación.
