# 🎬 AXELFLIX

**AXELFLIX** es una aplicación web construida en **Java** utilizando el patrón de arquitectura **MVC**. Permite buscar y visualizar información de películas y series consumiendo datos desde la API pública de [OMDb](https://www.omdbapi.com/).

El frontend está desarrollado con **HTML**, **CSS** y **TailwindCSS**.

---

## 🛠️ Tecnologías utilizadas

- **Java** (Backend)
- **Servlets / JSP** (MVC)
- **HTML + TailwindCSS** (Frontend)
- **OMDb API** (Proveedor de datos de películas)

---

## 📁 Estructura del proyecto (resumen)

AXELFLIX/
├── src/
│ ├── controller/
│ ├── model/
│ └── view/
├── webapp/
│ ├── index.jsp
│ └── resultados.jsp
├── static/
│ └── tailwind.css
└── config.properties (o archivo .env)

yaml

---

## ⚙️ Configuración e instalación

### 1. Clona este repositorio

```bash
git clone https://github.com/axeljm0/axelflix.git
cd axelflix
2. Obtén tu clave de OMDb API
Visita https://www.omdbapi.com/apikey.aspx

Regístrate con tu correo

Recibirás una API Key gratuita en tu email

3. Configura tus variables de entorno
Agrega la clave y la URL base en el archivo config.properties o .env (según cómo lo implemente tu app):

properties
Copiar
Editar
API_KEY=tu_clave_recibida
URL_BASE=https://www.omdbapi.com/
🔒 No compartas tu API key en repositorios públicos

🚀 Cómo iniciar AXELFLIX
Abre el proyecto en tu IDE (Eclipse, IntelliJ, NetBeans, etc.)

Asegúrate de tener un servidor como Apache Tomcat configurado

Ejecuta o despliega el proyecto

Accede a http://localhost:8080/axelflix/

🧪 Uso
En la pantalla principal (index.jsp), introduce el nombre de una película o serie

Haz clic en "Buscar"

Se mostrarán los resultados en una nueva vista (resultados.jsp), estilizados con TailwindCSS

✨ Créditos
Proyecto creado por Axel, 2025

Datos proporcionados por OMDb API

📄 Licencia
Copiright © 2025 - Axel

¿Te gustaría que te incluya una pequeña demo en GIF o imagen para mostrar la app visualmente en el README también?
