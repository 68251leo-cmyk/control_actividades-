# Interpretación de comandos
## Anliza 
git status - revista el estado del repositorio local como cambios en los archivos, y si aun estan el la zona de trabajo o en el repositorio local

git add README.md - agrega el area de staging el README.md

git commit -m "Actualiza documentación" - se agrega al repositorio local los cambios

git push - se agregan los cambios al repositorio remoto

## que falta
Modificar archivo
- caso A 
↓

git add .

↓

git commit -m "mensaje" para registrar lso cambios en el repositorio local y puedan ser enviados al remoto

↓

git push

- caso B 

Repositorio GitHub

↓

fork para clonarlo en mi cuenta de github enl a nube

↓

Repositorio local

- caso C

Repositorio remoto actualizado

↓

git pull para hacer un merge con el remoto y el local

↓

Repositorio local actualizado