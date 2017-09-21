# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1`
Para perder los cambios realizados en el working copy utilice este comando en vez de comandi "git reset HEAD~1". --hard revierte el index y el working tree de modo que los cambios se pierden totalmente. 

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` 
`git reset--hard` 

Para rehacer el último commit que acabamos de deshacer con el comando git reflog vi el codigo de paso anterior y con el comando git reset --hard, pegando el codigo del paso anterior (del commit que hice) volví un paso atras. 

--

**3. El merge del paso 13,¿Causó algún conflicto? ¿Por qué?**

El merge del paso 13 no me causó ningún conflicto. Antes de hacer el merge. Antes de hacer el merge hay que asegurase que estamos en la rama adecuada. 

--
**4. ¿El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? **


Causó conflicto porque antes de hacer el merge no añadí los cambios de archivo y no hice commit.

--

**5. ¿El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

EL merge del paso 21 no me causó ningún conflicto. 

--

**6. ¿Qué comando o comandos utilizaste en el paso 25? **

`git graph`
 

--

**7. ¿El merge del paso 26, ¿Podria ser fast foreward? ¿Por qué?**


Un fast-forward merge es cuando al momento de hacer merge con la rama master no se ha añadido ningún commit luego de crear la rama title. Si la rama master ha divergido después de haber creado la rama title ya no es posible un fast-forward merge. He hecho cambios (commit) depsues de crear la rama title entonces el merge del paso 26 no podría ser fast foreward. 

--

**8. ¿Qué comando o comandos utilizaste en el paso 27? **

`git reset HEAD~1`


--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git reset --hard HEAD~1`


--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -d title`


--

**11. ¿Qué comando o comandos utilizaste en el paso 30**

`git reflog`
`git reset -- xxx`

xxx- el código copiado de git reflog 


--

**12. ¿Qué comando o comandos utilizaste en el paso 32**

`git reflog`
`git reset -- xxx`

xxx- el código copiado de git reflog
 

--

**13. ¿Qué comando o comandos utilizaste en el paso33**

`git reflog`
`git reset -- xxx`

xxx- el código copiado de git reflog

--


