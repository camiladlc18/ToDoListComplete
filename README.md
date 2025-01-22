# **ToDoListCompleto**


**ToDoListCompleto** es un proyecto que reúne el desarrollo completo de una aplicación de lista de tareas, compuesto por:

1. **Backend**: Implementado en Spring Boot. (Submódulo: `Backend`)
2. **Frontend**: Implementado en Angular. (Submódulo: `Frontend`)

---

## 🛠️ **Tecnologías utilizadas**

- **Backend**: Java, Spring Boot
- **Frontend**: Angular
- **Base de datos**: MySQL
- **Control de versiones**: Git y GitHub

---

## 📂 **Clonar el repositorio**

Este repositorio utiliza **submódulos de Git**, por lo que es necesario clonar también los submódulos junto con el repositorio principal. Sigue los pasos a continuación:

### **Clonar con submódulos**

Usando Git bash:
git clone --recurse-submodules https://github.com/camiladlc18/ToDoListCompleto.git

## **Inicializar submódulos después de clonar**

Si ya clonaste el repositorio sin submódulos, inicialízalos con:

git submodule update --init --recursive


## ⚙️ **Configuración**

### **1. Configurar el Backend**

1. Asegúrate de tener **Java 17** (o superior) y **Maven** instalados.
2. Accede al directorio del backend
3. Abre tu cliente de MySQL y ejecuta el siguiente comando para crear la base de datos:
   CREATE DATABASE bd_listatareas;
4. Ve al archivo application.properties dentro del directorio del backend y edítalo con tus credenciales de MySQL. 
5. Ejecuta el backend, estará disponible en http://localhost:8080

### **2. Configurar el Frontend**
1. Asegúrate de tener **Node.js** y **Angular CLI** instalados.
2. Ve al directorio del frontend 
3. Instala las dependencias necesarias:
   npm install
4. Ejecuta el servidor de desarrollo:
   ng serve
5. El frontend estará disponible en http://localhost:4200.


## 📋 **Licencia**
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
