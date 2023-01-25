
# Componentes

Hay dos tipos principales de componentes en React: componentes de clase y componentes funcionales. Para nuestro caso, vamos a utilizar los **componentes funcionales**.

<div grid="~ cols-2 gap-4">
<div>

```js {all|1,8|2|3-7|all|10|all}
const App = () => {
  const greetings = "Hello World";
  return (
    <div className="App">
      <h1> {greetings} </h1>
    </div>
  );
}

export default App
```

```js
const Footer = () => {
  return (
    <footer className="footer">
      <h1> Im footer </h1>
    </footer>
  );
}

export default Footer
```

</div>
<div class="~ mt-20">

```js
const Navbar = () => {
  const text = "I'm Navbar!";
  return (
    <navbar className="navbar">
      <h1> {text} </h1>
    </navbar>
  );
}

export default App
```

</div>
</div>