# Conceptos

 - 1) la diferencia entre git y github es que git es un sistema de control de versiones y github es para tener nuestro codigo en la nube    

 - 2) el .gitignore sirve para ignorar archivos ya sean importantes como contraseñas como un .env o entornos de ejecucion de manera local que esten configurados para nuestra maquina como un CMakeUserPresets.json, tambien puede ser para ignorar archivos de dependenicas que son pesados y se pueden descargar como un .venv

 - 3) el .venv no se debe de subir porque es un archivo muy pesado en cambio se hace un .reqirements.txt que contiene las dependencias del proyecto

 - 4) para indicar las dependecias de que se usarn en el proyecto y sea facil de descargar con un ```pip install -r requirements.txt```
- 5) El are de stage sirve para saber que se subira al repositorio local y diferenciar los archivos que queremos subir del area de trabajo, el commit sube al repositorio local lo que esta en el area de stagin y el push sube lo que esta en repositorio local al remoto

- 6) por que se estan registrando en el repositorio local los cuales se suben al remoto despues