relog
===
## Uso
- `!relog {name}` volver a iniciar sesión en `{name}`. ej: `{relog Paul.5347}` esto cambiara al personaje con el nickname **Paul.5347**

- `!relog {number}` volver a iniciar sesión en el número del personaje de su lista de selección. ej: `{relog 3}` esto cambiara inmediatamente al 3° personaje de su lista de selección.

- `!relog nx` vuelva a iniciar sesión en el siguiente personaje de su lista.

## Problemas conocidos
- Si tu personaje recibe un golpe dentro de los 10 segundos de uso `!relog`, el estado del cliente y del servidor se desincronizará y tendrás que reiniciar el cliente.