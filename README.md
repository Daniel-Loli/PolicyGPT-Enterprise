# 🧠 PolicyGPT Enterprise — Full-Stack AI

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Azure OpenAI](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Status](https://img.shields.io/badge/Status-Deployed-success?style=for-the-badge)

**Plataforma Enterprise para el análisis automático de pólizas de seguros mediante Inteligencia Artificial Generativa.**

Extrae, interpreta y estructura información compleja de PDFs legales (coberturas, exclusiones, deducibles) convirtiéndola en datos JSON listos para la toma de decisiones.

> 🚀 **DEMO EN VIVO:** [👉 **Prueba la aplicación aquí**](https://enterprisefrontpoli.netlify.app/)

---

## 📸 Capturas de Pantalla (Flujo de la App)

Aquí puedes ver el funcionamiento de la aplicación:

<p align="center">
  <img src="./assets/imagen1.png" alt="Pantalla de Carga" width="31%">
  &nbsp;
  <img src="./assets/imagen2.png" alt="Procesamiento" width="31%">
  &nbsp;
  <img src="./assets/imagen3.png" alt="Resultado Final" width="31%">
</p>

---

## 🔗 Repositorios del Sistema (Código Fuente)

Este proyecto sigue una arquitectura de microservicios. El código fuente está dividido en los siguientes repositorios:

| Componente | Tecnologías | Repositorio |
| :--- | :--- | :--- |
| **🖥️ policygpt-frontend** | React, Vite, Tailwind, Zustand | **[🔗 Ver Repositorio Frontend](https://github.com/Daniel-Loli/policygpt-frontend.git)** |
| **🛡️ policygpt-backend-node** | Node.js, Express, Multer | **[🔗 Ver Repositorio Node.js](https://github.com/Daniel-Loli/policygpt-backend-node.git)** |
| **🧠 policygpt-backend-ia** | Python, FastAPI, Azure OpenAI | **[🔗 Ver Repositorio Python IA](https://github.com/Daniel-Loli/policygpt-backend-ia.git)** |

---

## 🏗️ Arquitectura del Flujo

El sistema utiliza un diseño desacoplado para escalabilidad y seguridad:

`[ Frontend (React) ]` → `[ API Gateway (Node.js) ]` → `[ IA Engine (FastAPI) ]` → `[ Azure OpenAI ]`

1.  **Frontend:** Interfaz moderna para carga de archivos y visualización de datos.
2.  **Node.js Gateway:** Orquestación, validación de archivos y enrutamiento.
3.  **FastAPI Engine:** Procesamiento de texto, limpieza y comunicación con la IA.
4.  **Azure OpenAI:** Extracción semántica y estructuración de datos (Function Calling).

---

## 🚀 Stack Tecnológico

* **Frontend:** React 18, TailwindCSS, Axios.
* **Backend:** Node.js (Express), Python (FastAPI).
* **IA / LLM:** Azure OpenAI Service (GPT-3.5-TURBO).
* **Infraestructura:** Render (Backends), Netlify (Frontend).

---

## 🧑‍💻 Autor

**Daniel Loli** — *Full-Stack AI Engineer*
