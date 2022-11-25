# Ej 1.



<img width=100% height="100" src="https://wallpapercave.com/wp/h3u2qag.jpg" title="questions-cat"/>



❇️ ` ¿Qué comando utilizaste en el paso 11? ¿Por qué?`:

        Git reser --hard HEAD~1 
    Porque quiero deshacer el último commit y además, quiero que se pierdan los cambios realizados en el working copy. En el caso de no queres perder lo que tengo en mi working copy, usaria git reset HEAD~1 sin el --hard
    Con git log verifico que en vez de dos, ahora solo tengo mi primer commit

❇️ ` ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?`:

        git reser --hard id_commit 
    Para ver el identificador del commit al que quiero rehacer o volver y

        git log 
    Para verificar que estoy donde quiero


❇️ ` El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?`:

        git merge master
    
    Lo hacemos asi porque "htmlify" absorve a "master" y para ello debemos estar en el branch htmlify.
    No hay conflictos porque antes del merge no hubo modificaciones, está actualizado.


❇️ ` El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?`:
    
    Encontramos conflicto porque hay modificaciones en las mismas líneas. 
    Debemos arreglar los conflictos y luego realizar un commit con el resultado.


❇️ ` El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?`:

    No hay conflicto porque lo hemos resuelto anteriormente para poder cambiar a rama master. Y la que había en rama master no tenía diferencias con la version que absorvemos de la rama style.

❇️ ` ¿Qué comando o comandos utilizaste en el paso 25?`:
        
        git log --graph  


❇️ ` El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?`:

    Sí, porque el archivo de git-nuestro.md de la rama title era el mismo archivo de master modificado. Si antes de mergear title y master hubiéramos modificado, el archivo de master solo podría ser no fast forward. Es decir, no avanzaría el puntero title, sino que aparecería un nuevo commit con dos padres, el que apunta a master y el que apunta a title. Así, mantendría el trabajo que hay en master y absorbería el trabajo que hay en title.


❇️ ` ¿Qué comando o comandos utilizaste en el paso 27?`:

        git reset HEAD~1

❇️ ` ¿Qué comando o comandos utilizaste en el paso 28?`:

        git restore git-nuestro.md

❇️ ` ¿Qué comando o comandos utilizaste en el paso 29?`:

        git branch -D title

❇️ ` ¿Qué comando o comandos utilizaste en el paso 30?`:

        git branch title 
        git merge title

❇️ ` ¿Qué comando o comandos usaste en el paso 32?`:

        git checkout  id_commit_inicial

    Hash commit inicial: 1c4c87cbff4e71edb1cceb42d5c0cdf9c40f804c

❇️ ` ¿Qué comando o comandos usaste en el punto 33?`:

        git reflog
        git checkout id_commit_final
        git log

    - git reflog para ver el hash del commit donde añadimos el título.
    - hash commit final: d6fe1ddf6918f7179ab65be0d6475f9a84eea7f0 
    - git log para verificar que  head está apuntando al commit final.

# Ej.2 

<img width=100% height="100" src="https://wallpapercave.com/wp/h3u2qag.jpg" title="questions-cat"/>

✅ GitHub, Fork and Pull Request (name author: DMR)

