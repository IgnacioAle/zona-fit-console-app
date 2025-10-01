# 🏋️‍♂️ Zona Fit - App de Consola con Spring Boot

**Zona Fit** es una aplicación de consola desarrollada con **Spring Boot** que simula la gestión de clientes de un gimnasio.  
Está conectada a una base de datos **MySQL** a través de **MySQL Workbench** y permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre los clientes.

---

## ✨ Funcionalidades principales

Al ejecutar la aplicación se despliega un menú interactivo en consola con las siguientes opciones:

1. 📋 Listar clientes  
2. 🔍 Buscar cliente por ID  
3. ➕ Agregar cliente  
4. ✏️ Modificar cliente  
5. 🗑️ Eliminar cliente  
6. 🚪 Salir de la aplicación  

---

## ⚙️ Tecnologías utilizadas

- ☕ **Java 17+**  
- 🌱 **Spring Boot**  
- 🗄️ **Spring Data JPA**  
- 🐬 **MySQL Workbench**  
- 📓 **SLF4J + Logger** para manejo de logs  

---

## 📂 Estructura principal

- `modelo/Cliente.java` → Entidad que representa a un cliente del gimnasio.  
- `servicio/IClienteServicio.java` → Interfaz con las operaciones CRUD.  
- `ZonaFitApplication.java` → Clase principal, implementa `CommandLineRunner` y maneja la lógica del menú.  

---
