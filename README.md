# Gitflow-en-github
Gitflow en github
# crecion de una rama
git checkout -b develop
# verificar si la rama se ha creado 
git branch
# subir la rama al repositorio de github
git push -u origin develop
# creacion de una rama feature 
git checkout -b feature/login-con-facebook
# verificar si la rama se ha creado
git branch
# inspeccionar los cambios para subir al git
git add login-con-facebook.txt README.md
# añadir mensaje y commit a los cambios efectuados 
git commit -m "Se implemento el inicio de sesion de Facebook"
# subir al repositorio con la rama seleccionada
 git push -u origin feature/login-con-facebook