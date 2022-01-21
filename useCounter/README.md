# useCounter Hook

Este Hook nos ayudara a manejar contadores dentro de nuestra app, puede ser uno o varios y 
con el factor que indiquemos.

## Sintaxis:
```
    const { counter: state, increment, decrement, reset } = useCounter(10); // useCounter recibe un valor inicial.

    console.log( counter ) // Imprime el valor actual del contador 
    
    increment( 2 ); // Aumenta el valor del countador en el factor que le pasamos ( 10 + 2 )
    decrement( 3 ); // Decrementa el valor del contador en el factor que le pasamos ( 12 - 3 )
    reset(); // Devuelve el contador a su valor inicial
```