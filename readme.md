# Respuestas a Práctica de GIT

###- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

`$ git reset --hard HEAD~1`

Utilizamos reset para deshacer, `--hard` porque se quiere perder los cambios del working copy; finalmente, `HEAD~1` porque es el último commit. 
 

###- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Primero: `$ git reflog`
Con esto he obtenido el hash del commit del paso 10 (1e6f148).

Finalmente: `$ git reset --hard 1e6f148`
Con esto muevo el HEAD al commit del paso 10.

###- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No porque el contenido de master ya lo tenía styled

###- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Si, porque las mismas línea en las distintas ramas tiene contenido distinto.

###- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, ya que es un merge fast-forward. Lo que tiene master ya está incluido en styled.

###- ¿Qué comando o comandos utilizaste en el paso 25? 
`$ git log --graph` 

Si el paso 25 hubiese pedido mostrar los punteros (ramas, head, etc)

`$ git log --graph --decorate`

###- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Si, porque "title" al contener los commit de "master", forma una lista

###- ¿Qué comando o comandos utilizaste en el paso 27? 
`$ git reset HEAD~1`

A diferencia del paso 11, aquí se mantienen los cambios

###- ¿Qué comando o comandos utilizaste en el paso 28?
`$ git checkout -- git-nuestro.md` 

###- ¿Qué comando o comandos utilizaste en el paso 29? 
`$ git branch -D title`

###- ¿Qué comando o comandos utilizaste en el paso 30?
Primero, para obetener el hash del merge: `$ git reflow`

Luego: `$ git reset --hard 8c136a6`

###- ¿Qué comando o comandos usaste en el paso 32?
`$ git reflog`

`$ git reset --hard 78f25e8`

Donde 78f25e8 es el hash del primer commit

###- ¿Qué comando o comandos usaste en el punto 33?
`$ git reflog`
`$ git reset --hard d68a767`

