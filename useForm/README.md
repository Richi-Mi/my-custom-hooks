# useForm - customHook

Hook que nos permitira manejar el estado de nuestros formularios.

## USO:
`const [ values, handleInputChange, reset ] = useForm( initialState );`

**useForm() .- Recibe un valor inicial que debe ser un objeto**

values .- Valores que tiene actualmente el formulario
handleInputChange( event ) .- Recibe el evento del Input y cambia el estado del formulario
reset() .- Regresa el formulario a su valor inicial