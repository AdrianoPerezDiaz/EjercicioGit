En el primer paso creo la carpeta "Ejercicio1" desde windows. Arranco visual code studio y creo los archivos "index.html" y "readdme.txt", arranco el repositorio
Creo en github un repositorio y renombro la rama principal del visual code como main para evitar errores. Enlazo los repositorios con "git remote add origin https://github.com/AdrianoPerezDiaz/EjercicioGit.git" y compruebo con un "git remote -v". Realizo un primer "git add ." y "git commit".
Mediante un "git push origin main" subo los archivos del local al remoto.
Tras crear la rama development con  "git branch development" y me sitúo en ella con "git checkout development" para realizo algún cambio en los archivos "index.html" y "readme.txt" para guardar los cambios con "git add ." y "git commit". subo la rama development con los cambios realizados a remoto con "git push --set-upstream origin development"


Tras volver a la rama "main" realizo un merge