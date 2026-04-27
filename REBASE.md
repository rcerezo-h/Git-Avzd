# Limpieza de commits con rebase

# Primera fase

En la primera fase, que era crear commits poco claros, escribí los siguientes

- `Cosas`
- `Cosotas`
- `Turbo cosotas`

Con esto lo que hacemos es crear diferentes commits que no tengan una defición clara para cambiarlo a continuación.

# Segunda fase

Ahora vamos a ver cuales son los commits que se han hecho gon git log --oneline para despues ejecutar un rebase -i HEAD~3, con la finalidad de cambiar los commits.

El primer commit se renombra con rewod para darle una definición clara, mientras que los otros dos usamos squash para unirlo con ese commit y en vez de tener 3 inciertos, tenemos 1 bastante claro. 

Para terminar de comprobarlo, hacemos un git log --oneline de nuevo para ver los cambios

# Tercera fase

Por último hacemos un git push --force para actualizar el historial remoto de GitHub