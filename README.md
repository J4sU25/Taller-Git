#Pasos Seguidos

Se intentó crear una rama "feature" inicialmente, pero hubo problemas porque no se estaba en un repositorio Git.
Se navegó al directorio correcto (Taller-Git) y se creó exitosamente la rama "feature".


Creación de contenido inicial:

Se creó un archivo "archivo.txt" con contenido inicial.
Se realizó el primer commit en la rama "feature".


Desarrollo en la rama feature:

Se añadió más contenido a "archivo.txt".
Se realizaron varios commits en la rama "feature".


Creación de la rama master:

Se intentó cambiar a la rama master, pero no existía.
Se creó la rama master con git checkout -b master.


Merge y rebase:

Se intentó fusionar feature en master, pero no hubo cambios.
Se realizó un reset y luego un rebase de feature en master.


Creación de hotfix:

Se creó una rama "hotfix" y se hizo un commit.
Se aplicó el hotfix a master usando cherry-pick.


Desarrollo paralelo:

Se añadió nuevo contenido en la rama feature (archivo "corrupcion.txt").
Se añadió contenido similar en la rama master.


Resolución de conflictos:

Al intentar fusionar feature en master, surgió un conflicto en "corrupcion.txt".
Se resolvió el conflicto manualmente y se realizó un commit de fusión.


Visualización del historial:

Se usó git log para ver el historial de commits y la estructura de ramas.
El historial muestra una estructura de ramas con merges y desarrollo paralelo.



Observaciones:

Hubo algunos errores iniciales al trabajar con Git, como intentar crear ramas fuera de un repositorio.
Se practicaron conceptos importantes como creación de ramas, commits, merges, rebase y resolución de conflictos.
El conflicto en "corrupcion.txt" no se resolvió completamente, lo que indica que se necesita más práctica en la resolución de conflictos.
El uso de comandos como git log --oneline --graph --all muestra una comprensión de cómo visualizar la historia del repositorio.

En general, este ejercicio proporcionó una buena práctica en el uso de Git, cubriendo muchos conceptos fundamentales del control de versiones.
