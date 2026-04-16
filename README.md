# 📘 Trabajo Práctico — ONG “Impulso Joven”

## 🧾 Descripción del proyecto

## Este proyecto consiste en el desarrollo de un **sitio web institucional de una ONG ficticia**, como parte de la materia _Taller de lenguajes de marcado t tecnologias web_.

# 🏢 Identidad de la ONG

## Nombre

**Impulso Joven**

## 🎯 Misión

Promover el desarrollo educativo y laboral de jóvenes en situación vulnerable mediante programas de formación, acompañamiento y acceso a oportunidades.

## 🌍 Visión

Ser una organización referente en inclusión social juvenil en Latinoamérica.

## 💡 Valores

- Inclusión
- Educación accesible
- Compromiso social
- Transparencia
- Trabajo en equipo

---

# 📄 Contenido de cada página

## 🏠 index.html — Inicio

---

## 🧑‍🤝‍🧑 nosotros.html — Institucional

---

## 📚 programas.html — Programas

---

## 📞 contacto.html — Contacto

### Debe incluir:

- Dirección:

> Av. Siempre Viva 123, Buenos Aires

- Teléfono:

```html
<a href="tel:+549999999999">+54 99 9999-9999</a>
```

- Email:

```html
<a href="mailto: "nombre@mail.org">nombre@mail.org</a>
```

- Red social:

```html
<a href="nombre de ig" target="_blank" rel="noopener noreferrer"> Instagram </a>
```

---

# 🔗 Navegación (OBLIGATORIA en todas las páginas)

```html
<nav>
  <ul>
    <li><a href="index.html">Inicio</a></li>
    <li><a href="nosotros.html">Nosotros</a></li>
    <li><a href="programas.html">Programas</a></li>
    <li><a href="contacto.html">Contacto</a></li>
  </ul>
</nav>
```

---

# 🧱 Estructura base obligatoria

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Título único</title>
  </head>
  <body>
    <header></header>
    <nav></nav>
    <main></main>
    <footer></footer>
  </body>
</html>
```

---

# ⚙️ Requisitos técnicos (OBLIGATORIOS)

- Usar etiquetas semánticas (`header`, `nav`, `main`, `footer`)
- 1 solo `<h1>` por página
- Usar `<section>` o `<article>`
- Incluir:
  - 1 `<ul>`
  - 1 `<ol>`
  - 1 `<dl>`

- Mínimo 2 imágenes con `alt`
- Enlaces internos (`#`)
- Enlace externo con `target="_blank"`
- `mailto:` y `tel:` en contacto
- Navegación funcional entre páginas

---

# 🧪 Validación

Todas las páginas deben pasar:
👉 [https://validator.w3.org/](https://validator.w3.org/)

---

# 💻 Uso de Git (MUY IMPORTANTE)

- Cada integrante debe hacer commits propios
- Usar mensajes claros:

Ejemplos:

- `feat: estructura base index`
- `feat: agrego sección programas`
- `fix: corrijo enlaces del nav`
