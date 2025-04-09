# Limpieza de commits

1. Añadí tres commits con mensajes poco claros: "Arreglos", "Cambios", "Actualización de cosas".
2. Usé `git rebase -i HEAD~3` para editar el historial.
3. Cambié el primer commit con `reword` para mejorar el mensaje y usé `squash` en los dos siguientes para fusionarlos.
4. Escribí un mensaje de commit más descriptivo en el editor.
5. Hice `git push --force` para actualizar el historial en GitHub.
