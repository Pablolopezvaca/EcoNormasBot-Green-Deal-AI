# 🌱 EcoNormasBot: IA Generativa para Consultas sobre el Pacto Verde Europeo

_EcoNormasBot_ es un asistente basado en **IA Generativa** que permite realizar **consultas en lenguaje natural** sobre el **Pacto Verde Europeo**, utilizando documentos oficiales de la Unión Europea.  
Este proyecto fue desarrollado como parte del **Capstone Project del GenAI Intensive Course (Google x Kaggle)**.

## 🚀 Objetivo

Facilitar el acceso a contenido normativo complejo mediante una interfaz conversacional alimentada por tecnologías de **Retrieval-Augmented Generation (RAG)**.

El sistema permite que cualquier persona —desde ciudadanos hasta responsables públicos o expertos— pueda preguntar en lenguaje natural sobre los compromisos, avances o estrategias del Green Deal Europeo, obteniendo respuestas fundamentadas con **referencias documentales claras y verificables**.

## 🧠 Tecnologías utilizadas

- **Google Gemini 1.5 Pro** – Para generación de texto y embeddings semánticos.
- **FAISS (Facebook AI Similarity Search)** – Para la búsqueda vectorial eficiente.
- **PyMuPDF** – Extracción de texto desde documentos PDF oficiales.
- **Python (Jupyter Notebook)** – Desarrollo, flujo RAG y preprocesamiento de datos.
- **Documentos oficiales de la UE** – Comunicación del Green Deal, Plan Industrial y Reportes de Progreso.

## 🗂 Estructura del proyecto

📁 EcoNormasBot/ │ ├── EcoNormasBot.ipynb <- Notebook principal del proyecto (Kaggle) ├── README.md <- Este archivo └── /docs (opcional) <- Imágenes, capturas o esquemas adicionales


## 🔎 Ejemplo de uso

**Consulta**:  
*¿Cuáles son los objetivos del Pacto Verde Europeo hacia 2030?*

**Respuesta generada**:  
> El Pacto Verde Europeo busca reducir al menos un 55% las emisiones de gases de efecto invernadero para 2030, en comparación con los niveles de 1990. Este compromiso está respaldado por la Ley Europea del Clima y acciones como el Plan de Acción "Contaminación Cero".

Fuentes: Comunicación del Pacto Verde 2019, Informe de Progreso 2023, pág. 25.

## 🌍 Aplicaciones potenciales

- Acceso abierto a políticas públicas
- Gobierno abierto y transparencia institucional
- Herramientas de educación ambiental y jurídica
- Soporte a equipos legales, técnicos o de gobernanza

## 📎 Enlace al notebook en Kaggle

📘 [Ver notebook ejecutable en Kaggle] (https://www.kaggle.com/code/pablolpezvaca/econormasbot-consultas-al-pacto-verde-con-gen-ai)

## ⚖️ Licencia

Este proyecto se distribuye bajo la licencia MIT. Ver `LICENSE`.

---

> Desarrollado con el objetivo de unir tecnología, sostenibilidad y gobernanza pública.
