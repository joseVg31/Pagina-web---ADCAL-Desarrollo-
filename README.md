# 🌿 ADCAL — Sitio Web Oficial

<img width="1906" height="920" alt="image" src="https://github.com/user-attachments/assets/40b5075f-7e0f-43da-bba8-4c2983fff959" />
<img width="1905" height="846" alt="image" src="https://github.com/user-attachments/assets/36123daa-da90-4411-815e-3747cfb61c07" />
<img width="1719" height="678" alt="image" src="https://github.com/user-attachments/assets/b50cf550-6d38-4d84-ad9b-5f63be133a2f" />
<img width="1560" height="794" alt="image" src="https://github.com/user-attachments/assets/40f14e03-9832-4aff-b74a-6d5398c3132b" />
<img width="1718" height="338" alt="image" src="https://github.com/user-attachments/assets/1856a2ca-38c3-4248-8f99-3e328793cabd" />


Landing page oficial de **ADCAL**, una asociación comprometida con el desarrollo agrícola y rural sostenible. El sitio presenta la misión, servicios y comunidad de ADCAL con un diseño moderno, animaciones suaves y video de fondo en la portada.

---

## 📋 Contenido del sitio

| Sección | Descripción |
|--------|-------------|
| 🎬 **Hero** | Portada con video de fondo, overlay verde y botón de acción |
| 🌱 **Qué es ADCAL** | Misión, visión y valores de la asociación |
| 🛠️ **Qué Ofrece** | Servicios de capacitación, insumos, certificación y más |
| 👥 **A quién va dirigido** | Agricultores, ganaderos, cooperativas y comunidades rurales |
| 📬 **Footer** | Navegación rápida y contacto directo por email |

---

## ✨ Características

- 🎬 Video de fondo en el hero con fallback a gradiente verde
- 📱 Diseño **responsive** — adaptado a móvil, tablet y escritorio
- 🎞️ Animaciones **fade-in** al hacer scroll
- 🔝 Navbar fija con efecto **blur** y scroll suave
- 🎨 Paleta de colores verde natural coherente en todo el sitio
- 🔠 Tipografías **Playfair Display** + **Lato** (Google Fonts)

---

## 🗂️ Estructura del proyecto

```
PAGINA_WEB_ADCAL/
│
├── static/
│   ├── audio/
│   ├── css/
│   │   ├── style.css          # Estilos personalizados
│   │   ├── tailwind.css       # Tailwind compilado
│   │   └── input.css          # Entrada de Tailwind
│   ├── icon/
│   ├── image/
│   │   ├── invernadero.jpg
│   │   ├── ganado.jpg
│   │   └── productos.jpg
│   ├── js/
│   │   └── main.js            # Animaciones y lógica
│   └── video/
│       └── hero-adcal.mp4     # Video de fondo del hero
│
├── template/
│   └── index.html             # Plantilla principal Jinja2
│
├── app.py                     # Servidor Flask
├── postcss.config.js
├── tailwind.config.js
├── package.json
├── sitemap.xml
└── README.md
```

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|-----------|-----|
| **Python / Flask** | Servidor web y rutas |
| **Jinja2** | Motor de plantillas HTML |
| **TailwindCSS** | Framework de estilos base |
| **CSS personalizado** | Estilos, animaciones y diseño |
| **JavaScript vanilla** | Animaciones scroll y menú móvil |
| **Google Fonts** | Tipografías Playfair Display y Lato |

---

## 📄 Licencia

© 2025 ADCAL · Todos los derechos reservados
