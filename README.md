# Nav Menu — Barra de navegación interactiva

**Proyecto pequeño:** una barra de navegación horizontal con iconos (Ionicons) y efecto "activo".

---

## Descripción

Pequeña demo en HTML/CSS que muestra una **navegación interactiva**: al hacer click en un ítem se activa (clase `.active`) y el botón circular (`.check`) se desliza para marcar la opción.

### Características

* HTML y CSS puros (sin frameworks).
* Iconos con Ionicons (CDN).
* Efecto de traducción vertical para el icono y aparición del texto cuando está activo.
* Fácil de personalizar (colores, tamaño, íconos).

---

## Cómo ejecutar localmente

1. Clona el repositorio:

```bash
git clone https://github.com/TU_USUARIO/TU_REPO.git
cd TU_REPO
```

2. Abrir `index.html` en el navegador. O sirve con un servidor simple:

```bash
# Python 3
python -m http.server 8000
# Luego abrir http://localhost:8000
```

---

## Estructura recomendada

```
/ (raíz)
├─ index.html
├─ estilo.css
├─ README.md

```

---

## Personalización rápida

* Cambia la variable `--clr` en `estilo.css` para modificar colores base.
* Reemplaza los `ion-icon name="..."` por otros nombres de Ionicons.

---
## [Vista previa](https://orioncode-nod.github.io/nav-menu/)
