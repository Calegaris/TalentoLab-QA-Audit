# Proyecto QA: Auditoría de Calidad - Talento Lab

![Estado](https://img.shields.io/badge/Estado-Finalizado-success)
![Rol](https://img.shields.io/badge/Rol-QA%20Tester%20Manual-blue)
![Herramientas](https://img.shields.io/badge/Herramientas-Jira%20%7C%20Zephyr%20%7C%20Chrome%20DevTools-orange)

## 📄 Resumen Ejecutivo
Auditoría completa de Software (QA Manual) realizada a la plataforma *Talento Lab*.
El objetivo fue validar los flujos críticos de **Registro, Búsqueda de Empleos y Postulación**, asegurando la calidad tanto en Desktop como en Mobile.

> **⚠️ Veredicto Final:** NO-GO (No lanzar a producción).
> **Razón:** Se detectaron 6 defectos, incluyendo un error bloqueante (500) en el Login y fallos de responsividad.

---

## 📸 Evidencias Destacadas (En Video/GIF)

### 1. Fallo Crítico: Error 500 en Login
*El servidor devuelve un error interno al intentar ingresar con credenciales válidas.*
![Error 500 Login](evidencias/Desktop_Error_500.gif)

### 2. Defecto de Usabilidad: Botón 'Ver Contraseña'
*El botón del ojo no revela el texto enmascarado, impidiendo validar la contraseña.*
![Bug Ojo](evidencias/Desktop_Bug_BotonOjo.gif)

### 3. Validación de Archivos
*Prueba de carga de CV con formato inválido.*
![Carga CV Inválido](evidencias/Desktop_CargaCV_Invalid.gif)

---

## 🛠️ Actividades Realizadas
* **Diseño de Pruebas:** Creación de 10 Casos de Prueba (Happy Path y Edge Cases).
* **Ejecución:** Gestión de ciclo en **Zephyr Scale** (90% ejecutado).
* **Bug Tracking:** Reporte de defectos en **Jira**.
* **Métricas:** Análisis de cobertura y severidad.

---

## 📊 Hallazgos Principales (Bugs)
| ID | Título | Severidad | Estado |
| :--- | :--- | :--- | :--- |
| **BUG-001** | Fallo Crítico (500) en Login | 🔴 Crítica | Open |
| **BUG-002** | Registro permite emails duplicados | 🟠 Alta | Open |
| **BUG-004** | Grid de Ofertas roto en Mobile | 🟡 Media | Open |
| **BUG-005** | Sistema acepta archivos inválidos (PNG) | 🟡 Media | Open |

---

## 📂 Documentación Completa
Para ver el detalle técnico, métricas y el plan de pruebas completo:

- 📄 **[Leer Informe Final (PDF)](docs/Informe%20Final%20de%20Testing%20-%20Talento%20Lab.pdf)**
- 📊 **[Ver Matriz de Prueba y Bugs (Excel)](docs/Entrega_Final_Testing_Luis_Calegari.xlsx)**

---

## 👨‍💻 Autor
**Luis Angel Calegari**
*QA Tester Manual*
