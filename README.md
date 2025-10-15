# 💻 Prueba Técnica – Desarrollador Jr.

¡Hola! 👋  
Gracias por tu interés en formar parte de nuestro equipo.  
Esta prueba técnica tiene como objetivo conocer tu forma de resolver problemas, tu lógica de desarrollo y tu nivel de dominio en algunas de las tecnologías que utilizamos en TIC Nacer Global.

---

## 🧠 Objetivo
Analizar un conjunto de datos, crear una base de datos en **MySQL** y desplegar un **reporte con PHP**, aplicando tus conocimientos y lógica de programación.

---

## 📦 Archivos y punto de partida

1. Descarga el archivo [`Data_PruebaTecnica.xlsx`](./Data_PruebaTecnica.xlsx)  
   o, si lo prefieres, **clona este repositorio** en tu entorno local.

2. Analiza la estructura y contenido del archivo — contiene diferentes hojas que deberás transformar en tablas de base de datos.

---

## 🗃️ Paso 1: Creación de la base de datos

1. Crea una base de datos en **MySQL**.  
2. Genera **una tabla por cada hoja** del archivo `Data_PruebaTecnica.xlsx`.  
3. Conéctate a la base de datos mediante **PHPMyAdmin** usando la siguiente URL: 127.0.0.1:8080/dashboard/


---

## 🧩 Paso 2: Proyecto PHP

1. Crea un nuevo proyecto en la ruta:  C:\xampp\htdocs
2. Usa tus iniciales como nombre del proyecto (por ejemplo: `C:\Server\htdocs\jprueba`)
3. Crea una **conexión a la base de datos con PHP** (usa `mysqli` o `PDO`, según prefieras)

---

## 🧮 Paso 3: Consulta SQL

Genera una consulta que **cruce las tablas** previamente creadas.  
El resultado deberá permitir generar un **reporte con los siguientes campos**:

| Campo | Descripción |
|-------|--------------|
| Matrícula | Identificador del alumno |
| Nombre completo | En una sola columna, formato: **Apellido Paterno, Apellido Materno, Nombres** |
| Carrera | Nombre del programa académico |
| Nivel | Grado o nivel educativo |
| Programa | Programa o plan correspondiente |
| Año y Periodo | Formato: **“1S-2024”** |
| Estatus | Estado actual del alumno |
| Clasificación | Tipo o categoría del registro |

🧾 **Orden de la consulta:**  
`Nivel → Programa → Carrera → Nombre del Alumno (Apellido Paterno, Materno, Nombres)`

---

## 🌐 Paso 4: Reporte HTML

- Despliega el resultado de la consulta en una **tabla HTML**.  
- Aplica estilos visuales con **Bootstrap 5 (CDN)** o el **framework CSS** de tu elección.  

---

## ⚙️ Herramientas y recomendaciones

- Puedes utilizar **VS Code** (ya instalado) o cualquier otro **IDE o editor** de tu preferencia.  
- Si prefieres trabajar en **otro lenguaje de programación**, no hay problema — solo notifícalo a **Iván**.

---

## 🚫 Reglas

🔍 Puedes investigar en internet lo que necesites.  
🚫 **No está permitido usar Chats de IA ni GitHub Copilot.**  
Confiamos plenamente en tu **integridad y honestidad profesional**.

---

## 📣 Comunicación

Si surge cualquier duda o comentario durante la prueba, **no dudes en comentarlo con Iván**.  
Estamos más interesados en **cómo resuelves los problemas**, que en una solución perfecta.

---

## ⭐ Criterios de evaluación

| Criterio | Descripción |
|-----------|-------------|
| Lógica y estructura del código | Claridad, orden |
| Comprensión del requerimiento | Que el resultado cumpla los objetivos |
| Conocimiento técnico | Uso correcto de SQL, PHP y HTML/CSS |
| Autonomía y razonamiento | Capacidad para investigar y resolver por cuenta propia |

---

### 💬 Consejo final

> “No busques hacerlo perfecto, busca hacerlo funcional y con propósito.”  
> ¡Mucha suerte! 🚀



