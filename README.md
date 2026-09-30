# Emmanuel Narro — Portafolio

Portafolio profesional de **Emmanuel Narro**, Ingeniero en Desarrollo y Gestión de Software.
Desarrollador **Junior Full Stack / Backend** enfocado en **.NET/C#, Python, SQL Server y APIs REST**.

🔗 **Sitio en vivo:** https://emmanuel121003.github.io/

---

## 👤 Sobre el proyecto

Sitio web de una sola página (single-page), moderno, responsive y accesible, construido con
**HTML, CSS y JavaScript puro** (sin dependencias ni frameworks) para máxima velocidad y portabilidad.
Todo el contenido está en un único archivo `index.html` autocontenido.

### Secciones

- **Hero** — presentación, perfil y llamadas a la acción.
- **Sobre mí** — perfil profesional.
- **Stack tecnológico** — tecnologías por categoría (Backend, Frontend, Bases de datos, Datos · Analítica, Mobile, Sistemas, Seguridad).
- **Proyectos** — proyectos propios (MedicalRecords, Sistema de Asistencia, Ganadero, Scanner-QR, etc.).
- **Colaboración en equipo** — trabajo profesional en E-GO (Scale II, Gens, PVM) y hackathon (AgroBot).
- **Experiencia y formación** — trayectoria laboral y académica.
- **Certificaciones** — 20 certificaciones (Google, Microsoft, IBM y SAS vía Coursera, Cisco, Santander Open Academy, EF SET, etc.).
- **Actividad en GitHub** y **Contacto** (email, WhatsApp, LinkedIn, GitHub).

---

## 🛠️ Stack técnico del sitio

| Área | Detalle |
|------|---------|
| Marcado | HTML5 semántico |
| Estilos | CSS3 (variables, grid, flexbox), tema claro/oscuro |
| Interacción | JavaScript (IntersectionObserver, menú móvil, toggle de tema) |
| Tipografía | Archivo, IBM Plex Sans, IBM Plex Mono (Google Fonts) |
| SEO | Meta tags, Open Graph, Twitter Card, JSON-LD, favicon SVG |
| Accesibilidad | HTML semántico, `aria-*`, foco visible, `prefers-reduced-motion` |

---

## 🚀 Ejecutar en local

No requiere build. Basta con abrir `index.html` en el navegador, o servirlo:

```bash
# Python
python -m http.server 8000
# luego abre http://localhost:8000
```

---

## 📁 Estructura

```
.
├── index.html               # Portafolio (single-page, autocontenido)
├── og-image.png             # Imagen para Open Graph / Twitter Card
├── CVs/                     # CV en LaTeX (ES/EN) + PDFs compilados
│   ├── CV_Emmanuel_Narro.tex        # versión completa (ES)
│   ├── CV_Emmanuel_Narro_EN.tex     # versión completa (EN)
│   ├── CV_Emmanuel_Narro_1pagina.tex    # versión de 1 página (ES)
│   ├── CV_Emmanuel_Narro_EN_1page.tex   # versión de 1 página (EN)
│   └── 1pagina/                     # PDFs de las versiones de 1 página
├── LinkedIn/                # Borradores de publicaciones (ES/EN) por certificación
└── README.md
```

Los PDFs de los CVs se regeneran con `pdflatex` (dos pasadas) desde la carpeta `CVs/`:

```bash
cd CVs && pdflatex CV_Emmanuel_Narro.tex && pdflatex CV_Emmanuel_Narro.tex
```

---

## 📫 Contacto

- **Email:** emmanuel.nare.12@gmail.com
- **WhatsApp:** [+52 618 270 4889](https://wa.me/526182704889)
- **LinkedIn:** [emmanuel-narro-8b4476170](https://www.linkedin.com/in/emmanuel-narro-8b4476170)
- **GitHub:** [@Emmanuel121003](https://github.com/Emmanuel121003)
- **Ubicación:** Guadalajara, Jalisco, México

---

<sub>Diseñado y desarrollado por Emmanuel Narro · Guadalajara, 2026</sub>
