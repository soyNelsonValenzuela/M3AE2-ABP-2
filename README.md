# Proyecto BEM – M3AE2 ABP2

Este proyecto corresponde a la actividad **"Metodologías de organización y modularización de estilos"** del módulo 3. Su objetivo es implementar buenas prácticas de organización de estilos mediante la metodología BEM (Bloques, Elementos y Modificadores), generando una interfaz clara, modular y escalable.

## 🎯 Aprendizaje Esperado

> Implementar una metodología para la organización y modularización de estilos en una interfaz web acorde a las buenas prácticas.

## 🧩 Descripción del Proyecto

Se desarrolló una página web sencilla con estructura HTML y CSS, utilizando exclusivamente la metodología BEM para la asignación de clases. El foco principal es la correcta separación de responsabilidades entre bloques, elementos y modificadores.

## 📁 Estructura del Proyecto

```
M3AE2-ABP-2/
├── css/
│   └── styles.css
├── html/
│   └── index.html
└── README.md
```

## 🏗️ Componentes de la Interfaz

- **Header**: contiene el logo del sitio y un menú de navegación.
- **Contenido Principal**:
  - Un artículo con título, imagen y texto.
  - Un formulario de contacto o galería de imágenes.
- **Footer**: incluye información de contacto y enlaces a redes sociales.

## 🧱 Metodología BEM Aplicada

Se definieron los siguientes bloques y sus respectivos elementos:

- `header`
  - `header__container`
  - `header__logo`
  - `header__nav`
    - `nav__list`
    - `nav__item`
    - `nav__item--active` (modificador)
    - `nav__item--disabled` (modificador)
- `main`
  - `main__article`
    - `article__title`
     - `article__image`
     - `article__text`
  - `main__gallery`
    - `gallery__title`
    - `gallery__grid`
    - `gallery__image`
  - `main__contact`
    - `contact__title`
    - `contact__form`
    - `contact__field`
    - `contact__label`
    - `form__input`
    - `contact__button`
- `footer`
  - `footer_content`
  - `footer__info`
  - `footer_text`
  - `footer__social`
  - `footer__link`
  - `footer__icon`


## 🎨 Estilos CSS

- Se utilizó un solo archivo `styles.css` para manejar todos los estilos.
- Las clases siguen estrictamente el formato BEM: `bloque__elemento--modificador`.
- El diseño es **responsive**, adaptándose a distintos tamaños de pantalla.

## 🧪 Resultado

El proyecto es visualmente coherente y funcional, con una estructura modular fácil de mantener y escalar.

## 🧑‍💻 Autor

**Nelson Valenzuela Gómez**

---
