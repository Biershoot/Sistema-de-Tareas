# 🏗️ Aplicación de Patrones de Diseño con JavaFX y Spring Boot  

## 📌 Descripción  
Este proyecto implementa una arquitectura basada en los patrones de diseño **MVC, Factory y DAO** para desarrollar una aplicación de escritorio con **JavaFX** en el frontend y **Spring Boot** en el backend, utilizando **MySQL** como base de datos.  

## 🛠️ Tecnologías y Herramientas  
- **Lenguaje:** Java 17+  
- **Frontend:** JavaFX  
- **Backend:** Spring Boot  
- **Base de Datos:** MySQL  
- **Patrones de Diseño:**  
  - **MVC** (Separación clara entre modelo, vista y controlador)  
  - **DAO** (Abstracción de la capa de persistencia)  
  - **Factory** (Creación flexible de objetos)  
- **ORM:** Hibernate + JPA  
- **Control de versiones:** Git | GitHub  

## 🚀 Características  
✔ Implementación modular con **Spring Boot** y **JavaFX**.  
✔ Conexión segura y eficiente con **MySQL** mediante **DAO y JPA**.  
✔ Uso del patrón **Factory** para la creación flexible de instancias.  
✔ Arquitectura **MVC** para una mejor separación de responsabilidades.  

## 📂 Estructura del Proyecto  
```bash
📦 Aplicación-JavaFX-SpringBoot
 ┣ 📂 src
 ┃ ┣ 📂 main
 ┃ ┃ ┣ 📂 java/com/miapp
 ┃ ┃ ┃ ┣ 📂 controller  # Controladores (MVC)
 ┃ ┃ ┃ ┣ 📂 model       # Modelos de datos
 ┃ ┃ ┃ ┣ 📂 dao         # Implementación DAO
 ┃ ┃ ┃ ┣ 📂 factory     # Implementación Factory
 ┃ ┃ ┃ ┣ 📂 service     # Servicios de negocio
 ┃ ┃ ┃ ┗ 📂 view        # Interfaces JavaFX
 ┃ ┃ ┗ 📂 resources
 ┃ ┃ ┃ ┣ 📂 fxml        # Vistas en FXML
 ┃ ┃ ┃ ┗ 📂 css         # Estilos
 
