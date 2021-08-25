# relog
Cambia de personaje rápidamente

## Comandos
Toolbox(/8) | Descripción del comando
--- | ---
**relog {name}** | Vuelva a iniciar sesión en `{name}`.  ej: `relog Paul.5347` esto cambiara al personaje con el nickname **Paul.5347**
**relog {number}** | Vuelva a iniciar sesión en el `{number}` del personaje de su lista de selección.  ej: `relog 3` esto cambiara inmediatamente al **3 personaje** de su lista de selección.
**relog nx** | Vuelva a iniciar sesión en el siguiente personaje de su lista.

## Problemas conocidos
- Si tu personaje recibe un golpe dentro de los 10 segundos de uso del comando `relog`, el estado del cliente y del servidor se desincronizará y tendrás que reiniciar el cliente.