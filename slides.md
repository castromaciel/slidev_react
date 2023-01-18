---
theme: seriph
background: https://images.hdqwalls.com/wallpapers/react-js-logo-no.jpg
class: 'text-center'
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
css: unocss
---

# React Js

La libreria Top de JavaScript para crear interfaces de usuario.

---

# Que es React?

<p>

  React es una librería Open Source (Código abierto) creada con la finalidad de facilitar la creación de interfaces de usuarios utilizando **_componentes_**.

  Toda aplicación web React se construye a partir de **_componentes reutilizables_** que conforman partes de la interfaz de usuario — podemos tener un componente distinto para nuestra barra de navegación, otro para el pie de página, otro para el contenido principal, etc.

  En la mayoría de los casos, la **sintaxis** utilizada para construir aplicaciones React se llama JSX (JavaScript XML), que es una extensión de la sintaxis de JavaScript.

  Con JSX, eliminamos la necesidad de interactuar con el DOM.

</p>

 ```javascript
  const navbar = document.getElementById('nav');
  const footer = document.querySelector('footer')
  ```
  👉🏽 [Documentación oficial](https://es.reactjs.org/)

  👉🏽 [Documentación Beta](https://beta.es.reactjs.org/)


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# Caracteristicas de React

```mermaid {theme: 'dark', scale: 0.8}
flowchart TB
  B(( React Js - Library ))
  
  B((React Js - Library))-->C(JSX: Nos permite combinar la lógica y<br> el marcado de JavaScript en un componente.)

  B((React Js - Library))-->D(Dom Virtual: Se trata de una copia del<br> objeto DOM que primero actualiza y vuelve a renderizar<br> nuestras páginas cuando se realizan cambios.)

  B((React Js - Library))--->E(Componentes: Las aplicaciones React están<br> formadas por diferentes componentes reutilizables que tienen<br> su propia lógica e interfaz de usuario. )
```