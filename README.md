Practica GIT

		-  ¿Qué comando utilizaste en el paso 11? ¿Por qué?  git reset —hard HEAD~1
		Para perder los cambios, sin el hard no se pierde el trabajo al deshacer el commit, el Stalin area queda vacío.
		
		-  ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 
		git REFLOG
		Para ver las etiquetas de los commits que se han hecho
		git reset y la etiqueta del commit que quieres rehacer.
		git restore del git-nuestr.md 
		o git reflog y git reset —hard
		-  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
		No hay conflictos, tenemos el resultado already to update. Eso significa que los cambios se han fusionado en la actual.  No hay conflicto por que el archivo no se ha modificado en lineas distintas, es decir es lineal y tiene acceso a master  
		-  El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
		 Antes de esto hubo que hacer un git add . Que no se especificaba la practica para que tuviera en cuenta el commit.
		Hay un conflicto en git-nuestro.md nos dice que solucione los conflictos antes de hacer el mergo.
		Esto es debido a que se han tocado el mismo fichero en dos ramas distintas (diferentes contenidos)	 Merge Fast-Foward 
		-  El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 
		No me marco conflicto.
		Updating 9a344f2..d8c9f65
		Fast-forward
		 git-nuestro.md | 15 ++++++---------
		 1 file changed, 6 insertions(+), 9 deletions(-) 
		-  ¿Qué comando o comandos utilizaste en el paso 25?  
		git log --graph —pretty=oneline
		
		-  El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
		Si, puesto que estábamos en la rama master que absorbe a title, no estaríamos perdiendo el cambio de title, es decir title mantendría su cambio y master y head se desplazarían juntos al merge

		-  ¿Qué comando o comandos utilizaste en el paso 27?  			
		git reset HEAD~1
		-  ¿Qué comando o comandos utilizaste en el paso 28?  
		git checkout — git-nuestro.md
		
		-  ¿Qué comando o comandos utilizaste en el paso 29? 
		
		git branch -D title  
		-  ¿Qué comando o comandos utilizaste en el paso 30?  
		git reflog 
		git checkout (967f9d3) El hash que tenia a ese punto
		-  ¿Qué comando o comandos usaste en el paso 32?  git reflog
		git checkout (9a344f2)
		
		-  ¿Qué comando o comandos usaste en el punto 33?  
		git reflog
		git checout ( d8c9f65)
		
