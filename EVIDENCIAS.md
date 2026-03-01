########################
#Protección rama main
########################
En el apartado 2 del documento practica1 vienen las imágenes de las evidencias:
- Img 2.1 viene las configuraciones realizadas para proteger la rama main


- Img 2.2 Se ve el resultado en modo foto del error al hacer un push a la rama main. En la imagen 2.3 se ve como el fichero EVIDENCIAS.md no ha subido al repositorio.
jgome@JaviPortatil MINGW64 /c/Datos/IA/MasterIA/01_Versionado_de_codigo_y_colaboración/codigo/Tema1Pontia (main)
$ git push
git: 'credential-manager-core' is not a git command. See 'git --help'.
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: error: GH006: Protected branch update failed for refs/heads/main.
remote:
remote: - Changes must be made through a pull request.
To https://github.com/jgomezdelafuente/Tema1Pontia.git
! [remote rejected] main -> main (protected branch hook declined)
error: failed to push some refs to 'https://github.com/jgomezdelafuente/Tema1Pontia.git'
jgome@JaviPortatil MINGW64 /c/Datos/IA/MasterIA/01_Versionado_de_codigo_y_colaboración/codigo/Tema1Pontia (main)


Opciones de protección:
###############################
Para poder configurarlo se ha seleccionado:
- Que a la rama main siempre se tenga que subir por Pull Request (Img 2.1)
- Por defecto, el owner o administrador del repositorio puede subir a la rama main. En la imagen 2.1 se ve que se le quita esos permisos, para que siempre tenga la necesidad de subir por Pull Request

Beneficios:
- Conseguir que en la rama main debe haber un código estable.
- Este código debe ser revisado, validado y probado antes de subir a Producción
- Mayor control sobre que cambios van a subir
- Evita la posibilidad de subir cambios indebidos
- Garantiza una buena trazabilidad de todos los cambios que han subido a Producción


#######################
#Gitignore
#######################




