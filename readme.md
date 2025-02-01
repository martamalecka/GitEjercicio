*¿Qué comando utilizaste en el paso 11? ¿Por qué?*
comando:
git reset --hard HEAD~1
El comando rest —hard deshace totalmente el último commit hecho y lo que está en el working copy.

*¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?*
comando:
git reflog
git reset --hard 565540e
Primero miro con reflog el historial de los commits, cojo el id del commit al cual quiero volver y reseteo el head ahí.

*El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?*
No ha ocurrido ningún conflicto, porque el archivo solo se ha modificado en una branch.

*El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?*
El merge ha generado un conflicto porque el archivo git-nuestro.md tiene contenido diferente entre las ramas y tenemos que decidir con cuál versión nos quedamos.

*El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?*
No ha ocurrido ningún conflicto, porque ya tenemos la misma versión del archivo git-nuestro.md en todas las ramas, tanto main como la styled. El head está en main y styled a la vez ahora.

*¿Qué comando o comandos utilizaste en el paso 25?*
comando:
git log --graph --decorate --pretty=oneline

*El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?*
No puede ser fast-forward porque al hacer el merge los paths se bifurcan y ya no es una línea de commits.

*¿Qué comando o comandos utilizaste en el paso 27?*
comando:
git reset --mixed HEAD^

*¿Qué comando o comandos utilizaste en el paso 28?*
comando:
git reset --hard

*¿Qué comando o comandos utilizaste en el paso 29?*
comando:
git branch -d title

*¿Qué comando o comandos utilizaste en el paso 30?*
comandos:
git checkout main
git merge title

*¿Qué comando o comandos usaste en el paso 32?*
comandos:
git log --oneline
git checkout 08a43f7

*¿Qué comando o comandos usaste en el punto 33?*
comando:
git checkout main
 



