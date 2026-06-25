# Proyecto Django – Laboratorios 01 y 02

## Estudiante
**Nombre:** Benjamin Cabrera Yepez  

## Carrera y Semestre
**Carrera:** Ingeniería en Software  
**Semestre:** 4to  

---

## Descripción del proyecto
Este proyecto corresponde a los laboratorios 01 y 02 de la asignatura de Programación Orientada a Objetos, donde se realizó la configuración inicial de un proyecto Django con conexión a base de datos MySQL y aplicación de buenas prácticas de seguridad.

---

## Pasos realizados

### Laboratorio 01 – Configuración base del proyecto
- Creación del entorno virtual en Python.
- Instalación de Django.
- Creación del proyecto base con `django-admin startproject`.
- Ejecución del servidor local con `python manage.py runserver`.
- Verificación del funcionamiento en: http://127.0.0.1:8000/

---

### aboratorio 02 – Configuración de base de datos y seguridad
- Configuración de la base de datos MySQL en `settings.py`.
- Instalación del conector `mysqlclient` / `PyMySQL`.
- Creación del archivo `.env` para variables sensibles.
- Configuración de `SECRET_KEY` y `DEBUG` de forma segura.
- Ejecución de migraciones con `python manage.py migrate`.
- Validación del servidor Django conectado a la base de datos.

---

## Evidencia de ejecución

Servidor Django en ejecución:

<img width="1366" height="429" alt="image" src="https://github.com/user-attachments/assets/db56f994-8c91-495f-98e5-e5aea0d3adfb" />

<img width="1366" height="681" alt="image" src="https://github.com/user-attachments/assets/6d00ba31-5796-4398-ac01-ab779ed9b6a5" />



---

## Conclusión
Se logró configurar correctamente un proyecto Django, integrando base de datos MySQL, manejo de variables de entorno y ejecución del servidor local, cumpliendo con los objetivos de ambos laboratorios.
