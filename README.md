Tareas: Las tareas consisten en probar tus compresion de react js asi como el conocimiento en git.
# Conociendo tus habilidades en git
1. Clona este repositorio (https://github.com/reactjsmx/reactjschallengev1/)
2. Crea un feature branch llamado `react2022-{tuNombre_apellido}` en git
# Conociendo tus habilidades en React js
1. Crea un proyecto  de react usando  reate-react-app (https://create-react-app.dev/docs/getting-started)

# Tarea 1: Renderizando child component en el parent 

# Paso 1 
Crea un componente llamado `Parent` agrega el siguiente codigo.
`function Parent() {
  return (
    <div>
      <h3>Parent Component</h3>
    </div>
  );
}`
# Paso 2
Crea otro componente llamado `Child` y agrega el siguiente codigo
`
/*no modificar*/
function Child() {
  return <div>This is children content</div>;
}
`
# Paso 3
Crea un componente llamado App  y agrega 
`
/*no modificar*/
function App() {
  return (
    <Parent>
      <Child />
    </Parent>
  );
}`
# Objetivo
Tu tarea es renderizar todo lo que contenga el componente `Child` modificando solamente function `Parent` una vez completada la tarea 1 deberás hacer el commit con el nombre de la tarea.

# Tarea2: Agregando unit testing
Agrega https://testing-library.com/docs/react-testing-library/intro/ al projecto y escribe una prueba unitaria para probar que el child se este renderizando correctamente.
Haz un commit con el nombre de la tarea 

# Tarea3: Agregando botones al child 
En la funcion child agrega 2 botones : uno que contenga el label `incrementar` y otro `decrementar`, los botones deben de ser capaces de incrementar/decrementar el contador localizado en la funcion `App` , la funcion App debe ser similar al siguiente ejemplo, haz los cambios pertinentes para tener un contador funcional.
# App.js
`function App() {
  return (
    <Parent>
       <p>valor de contador aqui </p>
      <Child />
    </Parent>
  );
}`
# Child.js
 `function Child() {
  return <div>
     <button>Incrementar</button>
     <button>Decrementar</button>
  </div>;
}`
# Tarea 5 : Agregando unit test en App.js
Agrega una prueba unitaria(unit test) para asegurarte que el contador se este renderizando correctamente
Haz el commit con el nombre de la tarea

# Tarea 6: Crea un pull request en el repositorio 

# Felicidades has completado el primer react challenge !!!!


