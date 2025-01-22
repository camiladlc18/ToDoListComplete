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

```bash
git clone --recurse-submodules https://github.com/camiladlc18/ToDoListCompleto.git

## **Inicializar submódulos después de clonar**

Si ya clonaste el repositorio sin submódulos, inicialízalos con:

```bash
git submodule update --init --recursive
