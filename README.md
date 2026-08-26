## Nombre
**Estudiante:** Miguel Mateo Ramos Rodas  
**Carrera:** Ingeniería de Sistemas  
**Universidad:** Universidad Católica Boliviana  

---

## Descripción
Este proyecto consiste en un sitio web que presenta mi hoja de vida, con todas la caracteristicas y etiquetas de html nativo, incluyendo la implementacion de form, multimedia y un portafolio interactivo.

---

## Etiquetas HTML5 Utilizadas
El sitio implementa una amplia variedad de etiquetas nativas para estructurar semánticamente el contenido:

* **Estructura semántica:** `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.
* **Texto y formato:** `<h1>` a `<h6>`, `<p>`, `<strong>`, `<em>`, `<mark>`, `<small>`, `<time>`, `<address>`, `<details>`, `<summary>`.
* **Listas:** `<ul>`, `<ol>`, `<li>`.
* **Tablas:** `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`.
* **Multimedia:** `<figure>`, `<figcaption>`, `<picture>`, `<img>`, `<audio>`, `<video>`, `<source>`.
* **Formularios e interactividad:** `<form>`, `<fieldset>`, `<legend>`, `<label>`, `<input>`, `<textarea>`, `<select>`, `<option>`, `<button>`, `<meter>`.

---

## Elementos de Accesibilidad Implementados
Se siguieron las pautas de accesibilidad web (WCAG) para garantizar una correcta navegación en lectores de pantalla y mediante teclado:

1. **Enlace de salto accesible (Skip Link):** Permite a los usuarios de lectores de pantalla u omitir la navegación e ir directamente al contenido principal (`<a href="#main" class="skip-link">`).
2. **Atributos ARIA:**
   * `aria-label`: Utilizado en la etiqueta `<nav>` para describir el propósito de la navegación.
   * `aria-labelledby`: Implementado en todas las secciones `<section>` para asociarlas directamente con su encabezado visible (`<h2>`).
   * `aria-describedby`: Asociado al campo de correo electrónico para vincular las instrucciones de ayuda (`<small id="email-ayuda">`).
   * `role="banner"`: Aplicado en el encabezado principal del sitio.
3. **Texto alternativo (`alt`):** Descripción detallada en las imágenes para usuarios con discapacidad visual.
4. **Asociación de formularios:** Todos los campos `<input>`, `<select>` y `<textarea>` están vinculados explícitamente a un `<label>` mediante el atributo `for`.

---

## Instrucciones para Visualizar el Proyecto

## Localmente
1. Clona el repositorio o descarga el archivo `.zip`:
   ```bash
   git clone [https://github.com/mramosr-cyber/hoja-vida-Ramos-Miguel.git](https://github.com/mramosr-cyber/hoja-vida-Ramos-Miguel.git)