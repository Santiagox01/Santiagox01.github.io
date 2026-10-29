# Portafolio Profesional — Santiago Jaramillo Valencia

Portafolio web técnico y profesional orientado a reclutadores, ingenieros líderes y oportunidades de prácticas formativas en **Data Engineering**, **Data Science** y **Software Engineering**.

Desplegado en GitHub Pages: **[https://santiagox01.github.io](https://santiagox01.github.io)**

---

## 👨‍💻 Sobre el Perfil

* **Nombre:** Santiago Jaramillo Valencia
* **Ubicación:** Medellín, Antioquia, Colombia
* **Formación:**
  * **Ingeniería de Sistemas** — Universidad de Antioquia (UdeA)
  * **Ingeniería en Ciencia de Datos** — Instituto Tecnológico Metropolitano (ITM)
  * **Formación Técnica en Programación de Software** — SENA
* **GitHub:** [https://github.com/Santiagox01](https://github.com/Santiagox01)
* **Correo:** [santiagojaramillovalencia2@gmail.com](mailto:santiagojaramillovalencia2@gmail.com)

---

## 🚀 Proyectos Destacados e Integración Visual

El portafolio incluye capturas de pantalla reales, esquemas dimensionales y visualizaciones de los proyectos ejecutados localmente:

1. **Meteor Madness — Horizons Shield (NASA Space Apps Challenge 2025):**  
   Simulador orbital y de defensa planetaria 3D desarrollado con el equipo *Code Nebula*.  
   *Contribución individual:* Modelos físicos y matemáticos aplicados (energía cinética, escala geológica de cráteres, cálculo de magnitud sísmica acoplada, sobrepresión de 5 psi y leyes termodinámicas).
2. **Academic Data Warehouse:**  
   Data Warehouse con esquema en estrella y consultas OLAP sobre DuckDB con 60,000 registros sintéticos de matrícula y validación integral de integridad referencial.
3. **AirFusion TEMPO:**  
   Aplicación web interactiva que unifica datos de calidad del aire provenientes de sensores terrestres, la API de OpenAQ y observaciones del satélite NASA TEMPO.  
   *Contribución individual:* Interfaz web en React + TypeScript y pipelines de ingesta/unificación de datos vía API REST.
4. **EuroCoinClassifier:**  
   Pipeline de visión computacional con descriptores HOG, GLCM, forma y color, reducción de dimensionalidad con PCA (195 componentes, 95% varianza) y modelos SVM/k-NN alcanzando un 88.7% de exactitud en el conjunto de prueba reservado.
5. **Credit Risk Backend:**  
   Servicio backend en Java y Spring Boot con seguridad basada en Spring Security + JWT, persistencia en PostgreSQL y suite completa de pruebas automatizadas con MockMvc y JUnit 5.
6. **Information Systems Labs:**  
   Sistemas distribuidos en Spring Boot y Angular con documentación interactiva OpenAPI/Swagger y motor de reglas de negocio declarativas en Drools.
7. **Digital Inventory System:**  
   Proyecto industrial privado para control y balance de inventario de lubricantes, arquitectura offline-first con SQLite local y empaquetado como APK para Android mediante Expo EAS.

---

## 🎨 Características de Diseño y UX

* **Estética Tecnológica y Minimalista:** Modo oscuro con paleta slate/azul noche (`#060913`, `#0f172a`) y acentos en verde menta/turquesa (`#2dd4bf`).
* **Microinteracciones y Animaciones Discretas:** Pipeline interactivo en tiempo real en la sección Hero, badges de estado en vivo y efectos hover sutiles.
* **Visor Lightbox de Alta Resolución:** Permite a reclutadores inspeccionar en detalle las capturas reales de código, modelos y esquemas de cada proyecto.
* **Filtros Dinámicos de Proyectos:** Filtrado instantáneo por categoría (Data & ETL, Machine Learning, Software & Backend, NASA Hackathon).
* **100% Accesible y Responsive:** Optimizado para dispositivos móviles, tablets y monitores de escritorio.
* **Cero Dependencias de Construcción en Producción:** HTML5 semántico, CSS moderno y JavaScript modular nativo, compatible nativamente con GitHub Pages desde la raíz.

---

## 🛠️ Estructura del Repositorio

```text
Santiagox01.github.io/
├── index.html                   # Entrada principal del portafolio (Vanilla HTML5/CSS/JS)
├── README.md                    # Documentación del proyecto
└── assets/
    └── projects/                # Capturas reales y esquemas de los proyectos
        ├── academic-data-warehouse.png
        ├── academic-dw-plot-27.png
        ├── academic-dw-plot-28.png
        ├── airfusion-tempo.png
        ├── credit-risk-backend.png
        ├── digital-inventory-system.png
        ├── eurocoin-confusion-matrix.png
        ├── eurocoin-hog.png
        ├── eurocoin-model-comparison.png
        ├── eurocoin-segmentation.png
        ├── fsi-lab1-dashboard.png
        ├── fsi-lab1-swagger.png
        ├── fsi-lab2-drools.png
        ├── fsi-lab2-rules-result.png
        ├── meteor-madness-asteroids.png
        ├── meteor-madness-home.png
        ├── meteor-madness-impacts.png
        └── meteor-madness-simulation.png
```

---

## 🌐 Instrucciones para Despliegue en GitHub Pages

1. Abre una terminal en este directorio o confirma que los cambios estén listos:
   ```bash
   git status
   ```
2. Añade los archivos modificados y las capturas generadas:
   ```bash
   git add .
   ```
3. Realiza el commit:
   ```bash
   git commit -m "feat: complete portfolio redesign with real project captures, interactive ETL hero, and NASA Meteor Madness project"
   ```
4. Sube los cambios a la rama principal de GitHub:
   ```bash
   git push origin main
   ```
5. En GitHub, ve a **Settings > Pages** y asegúrate de que **Source** esté configurado en:
   * **Branch:** `main`
   * **Folder:** `/ (root)`
6. Tu portafolio estará inmediatamente disponible en:  
   👉 **`https://santiagox01.github.io/`**
