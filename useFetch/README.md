# useFetch() - custom Hook 

Hook que nos permitira manejar el estado de una petición GET http usando Fetch

## Uso: 

```

const { data, loading, error } = useFetch( https://api.com/users );

data .- Resultado de la petición ( Si no hay errores )
loading .- Indicara si esta cargando o si ya se cargo la data
error .- indica si hubo un error en la petición

```