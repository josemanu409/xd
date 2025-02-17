# Configuración Inicial
git config --global user.name "Tu Nombre"
git config --global user.email "tu.email@example.com"
[git_example_project.zip](https://github.com/user-attachments/files/18833610/git_example_project.zip)
git add hola.py

# Hacer un Commit
git commit -m "Añadir script de hola mundo"

# Vincular Repositorio con GitHub
git remote add origin https://github.com/usuario/mi_proyecto.git
git push -u origin main

# Agregar, Commit y Subir Cambios
git add .
git commit -m "Descripción de los cambios"
git push origin main

# Actualizar desde GitHub
git pull origin main
