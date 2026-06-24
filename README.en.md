[English](README.en.md) | [Español](README.md)

# RugidosWebSite — Commercial Website for a Children's Party Venue (Legacy 2023)

A complete web platform for **Rugidos Fiestas Tandil**, a children's party venue located in Tandil, Buenos Aires. The site was deployed and in production from its development until it was replaced by an ([updated version](https://github.com/IvanGomezDellOsa/RugidosWebSite))

---

## 🛠 Tech Stack

| Layer | Technology |
|------|------------|
| **Structure** | Semantic HTML5 |
| **Styling** | CSS3 (no frameworks) |
| **Logic** | Vanilla JavaScript |
| **Hosting** | cPanel (automatic deploy via `.cpanel.yml`) |

---

## 🎯 Features

**Interface and navigation**
- Fixed navbar with a dynamic highlight effect based on the visible section (IntersectionObserver)
- Responsive hamburger menu for mobile
- Smooth scroll between sections with `scroll-snap`

**Photo gallery**
- Carousel of 14 images with manual (prev/next) and automatic (7s timer) navigation
- Navigation dots generated dynamically based on the number of photos
- CSS animation per slide

**Services and Extras**
- Animated accordions to show/hide information about the venue, services and available extras
- Entry animation via IntersectionObserver on the featured items

**External integrations**
- Live Instagram feed (Elfsight)
- Live Google reviews (Elfsight)
- Embedded Google Maps map
- Floating WhatsApp widget

**Accessibility and SEO**
- Semantic tags (`<header>`, `<main>`, `<section>`)
- `.sr-only` classes for screen readers
- Meta description and author defined

---

## 📸 Screenshots

### Home
![Inicio](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/1_S_Inicio.png)

### Photo gallery
![Galería de fotos](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/2_S_Galeria_de_fotos.png)

### Services
![Servicios](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/3_S_Servicios.png)

### Reviews
![Reseñas](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/4_S_Resenas.png)

### Extras
![Extras](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/5_S_Extras.png)

### Instagram
![Instagram](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/6_S_Instagram.png)

### Location
![Ubicación](RugidosWebSite/Screenshots%20--%20RugidosWebSite-2023-legacy/7_S_Ubicacion.png)

---

## 🎥 Demo

[Watch the video on YouTube](https://youtu.be/5V_OWWT0yM4?si=LO-jUatl6iTJekt0)

---

## 🚀 Deploy

The deploy was performed automatically from the repository to cPanel via the `.cpanel.yml` file, copying the content directly to `/public_html/`.

---

## 📝 Development Notes

A project developed **without LLM assistance**, in 2023. All the code — HTML structure, CSS styles and JavaScript logic — was written manually.

---

## 👤 Author

**Iván Gómez Dell'Osa**

- Email: [ivangomezdellosa@gmail.com](mailto:ivangomezdellosa@gmail.com)
- LinkedIn: [linkedin.com/in/ivangomezdellosa](https://www.linkedin.com/in/ivangomezdellosa/)
- GitHub: [IvanGomezDellOsa](https://github.com/IvanGomezDellOsa)
