# git-challenges

Este repositorio es un repositorio de desafios a resolver. Cada rama contiene un caso diferente al que te deberas enfrentar.

# 🧩 Problema 1: Editar un commit antiguo
Escenario: Te das cuenta de que cometiste un error en un archivo hace tres commits(subiste una api key), y necesitas modificar ese commit específico.

Solución esperada:

Usar rebase interactivo para editar el commit.

Modificar los archivos.

Amendar el commit y continuar el rebase.


# 🧩 Problema 2: Mover commits a otra rama
Escenario: Hiciste varios commits en la rama main, pero deberían haber estado en una nueva rama llamada feature-x.

Solución esperada:

Crear una nueva rama desde un punto anterior.

Mover los commits con cherry-pick.

# 🧩 Problema 3: Eliminar commits anteriores al último
Escenario: Hiciste 3 commits, pero solo el último es válido. Quieres borrar los dos anteriores.

Solución esperada:

Usar rebase para eliminar commits específicos.

O resetear la rama antes de esos commits y hacer un nuevo commit si es necesario.

# 🧩 Problema 4: Deshacer el último commit (sin perder los cambios)
Escenario: El último commit fue un error, pero quieres mantener los archivos modificados.

Solución esperada:

Usar reset

# 🧩 Problema 5: Recuperar un commit perdido
Escenario: Hiciste reset --hard y perdiste cambios que estaban en un commit. Quieres recuperarlo.

Solución esperada:

Usar git reflog para encontrar el commit perdido y recuperarlo con checkout o reset.