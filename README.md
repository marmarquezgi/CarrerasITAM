
# CarrerasITAM — Comandos de Git

Guia explicando los pasos que segui para subir mi codigo html

Link de la pagina: https://marmarquezgi.github.io/CarrerasITAM/

Link de la pagina original: https://carreras.itam.mx/carreras/

Link del primer pull request: https://github.com/marmarquezgi/CarrerasITAM/pull/1

Link del segundo pull request: https://github.com/marmarquezgi/CarrerasITAM/pull/2

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
