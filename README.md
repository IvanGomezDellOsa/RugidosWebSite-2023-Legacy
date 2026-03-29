# RugidosWebSite — Sitio Web Comercial para Salón de Fiestas Infantiles (Legacy 2023)

Plataforma web completa para **Rugidos Fiestas Tandil**, un salón de fiestas infantiles ubicado en Tandil, Buenos Aires. El sitio estuvo deployeado y en producción desde su desarrollo hasta que fue reemplazado por una ([versión actualizada](https://github.com/IvanGomezDellOsa/RugidosWebSite))

---

## 🛠 Stack Tecnológico

| Capa | Tecnología |
|------|------------|
| **Estructura** | HTML5 semántico |
| **Estilos** | CSS3 (sin frameworks) |
| **Lógica** | JavaScript vanilla |
| **Hosting** | cPanel (deploy automático vía `.cpanel.yml`) |

---

## 🎯 Funcionalidades

**Interfaz y navegación**
- Navbar fija con efecto de resaltado dinámico según la sección visible (IntersectionObserver)
- Menú hamburguesa responsive para mobile
- Scroll suave entre secciones con `scroll-snap`

**Galería de fotos**
- Carrusel de 14 imágenes con navegación manual (prev/next) y automática (timer de 7s)
- Dots de navegación generados dinámicamente según cantidad de fotos
- Animación CSS por slide

**Servicios y Extras**
- Acordeones con animación para mostrar/ocultar información del salón, servicios y extras disponibles
- Animación de entrada por IntersectionObserver en los ítems destacados

**Integraciones externas**
- Feed de Instagram en vivo (Elfsight)
- Reseñas de Google en vivo (Elfsight)
- Mapa de Google Maps embebido
- Widget flotante de WhatsApp

**Accesibilidad y SEO**
- Etiquetas semánticas (`<header>`, `<main>`, `<section>`)
- Clases `.sr-only` para lectores de pantalla
- Meta description y author definidos

---

## 📸 Screenshots

### Inicio
![Inicio](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/1_S_Inicio.png)

### Galería de fotos
![Galería de fotos](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/2_S_Galeria_de_fotos.png)

### Servicios
![Servicios](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/3_S_Servicios.png)

### Reseñas
![Reseñas](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/4_S_Resenas.png)

### Extras
![Extras](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/5_S_Extras.png)

### Instagram
![Instagram](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/6_S_Instagram.png)

### Ubicación
![Ubicación](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/7_S_Ubicacion.png)

---

## 🎥 Demo

[Ver video en YouTube](https://youtu.be/5V_OWWT0yM4?si=LO-jUatl6iTJekt0)

---

## 🚀 Deploy

El deploy se realizaba automáticamente desde el repositorio a cPanel mediante el archivo `.cpanel.yml`, copiando el contenido directamente a `/public_html/`.

---

## 📝 Notas de Desarrollo

Proyecto desarrollado **sin asistencia de LLMs**, en 2023. Todo el código — estructura HTML, estilos CSS y lógica JavaScript — fue escrito manualmente.

---

## 👤 Autor

**Iván Gómez Dell'Osa**

- Email: [ivangomezdellosa@gmail.com](mailto:ivangomezdellosa@gmail.com)
- LinkedIn: [linkedin.com/in/ivangomezdellosa](https://www.linkedin.com/in/ivangomezdellosa/)
- GitHub: [IvanGomezDellOsa](https://github.com/IvanGomezDellOsa)
