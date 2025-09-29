# CarrerasITAM — Comandos de Git

Guia explicando los pasos que segui para subir mi codigo html

## Pasos que seguí

```bash
git clone https://github.com/marmarquezgi/CarrerasITAM.git  # para clonar el repositorio

cd .\CarrerasITAM\  # para entrar al repositorio

git checkout -b user/marmarquezgi/tarea  # crear una nueva rama en el repositorio

# Agrego archivos que estaban en otra carpeta

git status  # para verificar que estoy en la rama correcta

git add /todos los archivos

git commit -m "Primer commit"  # para tener una foto de mi trabajo en el tiempo

git push --set-upstream origin user/marmarquezgi/tarea  # para subir los cambios a github
