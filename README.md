relog
===
## Uso
- `!relog {name}` volver a iniciar sesión en `{name}`

- `!relog {number}` volver a iniciar sesión en el n-th personaje de su lista de selección.

- `!relog nx` vuelva a iniciar sesión en el siguiente personaje de su lista.

## Problemas conocidos
- Si tu personaje recibe un golpe dentro de los 10 segundos de uso `!relog`, el estado del cliente y del servidor se desincronizará y tendrás que reiniciar el cliente.