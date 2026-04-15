1. Inicialización y primer commit:
   git init
   git branch -M main
   git add .
   git commit -m "Estructura inicial del proyecto"

2. Historial:
   git log --oneline

3. Trabajo con ramas (desarrollo):
   git checkout -b desarrollo
   git add index.html
   git commit -m "Agrega contenido en index"
   git checkout main
   git merge desarrollo

4. Diferencias y gestión de commits:
   git diff styles.css
   git commit -m "Cambio temporal"
   git reset --hard HEAD~1
   git reflog
   git reset --hard [ID_DEL_COMMIT]

5. Ignorar archivos:
   git add .gitignore
   git commit -m "Agrega gitignore"

6. GitHub y Rama Login:
   git remote add origin [https://github.com/fabiolamss/laboratorio-git.git](https://github.com/fabiolamss/laboratorio-git.git)
   git push -u origin main
   git checkout -b login
   git add login.html
   git commit -m "Agrega login"
   git push origin login
