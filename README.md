# IDENTIFY AI — GuardaMsg

**Proyecto Integrador Intermedio 1**  
Sistema de detección de fraudes en mensajería instantánea con Inteligencia Artificial  
Universidad Privada Franz Tamayo (UNIFRANZ) · Bolivia · 2025

---

## 🔗 Demo en producción

**[https://identify-ai-pi.vercel.app/](https://identify-ai-pi.vercel.app/)**

---

## 📌 Descripción

GuardaMsg es una simulación web interactiva de un sistema de detección de fraudes en mensajería (WhatsApp, Facebook Messenger). Utiliza técnicas de NLP y Machine Learning (BERT, Naive Bayes, SVM) para clasificar mensajes según su nivel de riesgo: alto, medio o bajo.

---

## ✨ Funcionalidades

- **Bandeja de mensajes** — 5 mensajes pre-cargados con análisis IA y semáforo de riesgo
- **Analizador IA** — escribe cualquier mensaje y obtén su clasificación con pipeline animado
- **Estadísticas** — métricas del modelo (Precisión 94.7%, Recall 96%, F1 93%)
- **Arquitectura** — 6 módulos del sistema explicados interactivamente
- **Registro de usuario** — flujo completo de 3 pasos con validación

---

## 🛠 Tecnologías

| Componente | Tecnología |
|------------|------------|
| App móvil | Android (Kotlin) |
| Modelo NLP | BERT, Naive Bayes, SVM |
| Móvil ML | TensorFlow Lite |
| Backend | FastAPI (Python) |
| Base de datos | PostgreSQL |
| Preprocesamiento | NLTK, spaCy |
| Despliegue | Vercel |
| Metodología | Scrum |

---

## 🚀 Despliegue en Vercel

### Requisitos
- Cuenta en [GitHub](https://github.com)
- Cuenta en [Vercel](https://vercel.com)

### Pasos

1. **Clona o descarga el repositorio**
   ```bash
   git clone https://jhesicaflorescondori099-ship-it.github.io/identify-ai-sistemas/
   ```

2. **Sube el proyecto a GitHub**  
   Asegúrate de que el repositorio sea público y contenga `index.html` y `vercel.json`

3. **Conecta con Vercel**
   - Ingresa a [vercel.com](https://vercel.com) e inicia sesión con GitHub
   - Clic en **"Add New Project"**
   - Selecciona el repositorio `Identificar_IA`
   - Vercel detecta automáticamente que es un sitio estático
   - Clic en **"Deploy"**

4. **Listo**  
   Vercel genera una URL pública en menos de 1 minuto.

### Configuración incluida

El archivo `vercel.json` ya está configurado para despliegue estático:

```json
{
  "version": 2,
  "builds": [
    { "src": "index.html", "use": "@vercel/static" }
  ],
  "routes": [
    { "src": "/(.*)", "dest": "/index.html" }
  ]
}
```

---

## 💻 Ejecución local

### Opción 1 — Live Server (VS Code)
1. Abre la carpeta del proyecto en VS Code
2. Instala la extensión **Live Server** (ritwickdey.liveserver)
3. Clic derecho en `index.html` → **"Open with Live Server"**
4. Se abre en `http://127.0.0.1:5500`

### Opción 2 — Directo en navegador
1. Descarga el repositorio
2. Abre `index.html` directamente en tu navegador

---

## 📁 Estructura del proyecto

```
Identificar_IA/
├── index.html       # Aplicación completa (HTML + CSS + JS)
├── vercel.json      # Configuración de despliegue en Vercel
└── README.md        # Este archivo
```

---

## 👥 Equipo

Desarrollado como **Proyecto Integrador Intermedio 1**  
Ingeniería en Sistemas — UNIFRANZ El Alto · 2025

