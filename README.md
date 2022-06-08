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

