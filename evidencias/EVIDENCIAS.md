\########################

\#2- Protección rama main
########################



jgome@JaviPortatil MINGW64 /c/Datos/IA/MasterIA/01\_Versionado\_de\_codigo\_y\_colaboración/codigo/Tema1Pontia (main)
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
! \[remote rejected] main -> main (protected branch hook declined)
error: failed to push some refs to 'https://github.com/jgomezdelafuente/Tema1Pontia.git'

jgome@JaviPortatil MINGW64 /c/Datos/IA/MasterIA/01\_Versionado\_de\_codigo\_y\_colaboración/codigo/Tema1Pontia (main)



Opciones de protección:
###############################
Se ha seleccionado la opción de para poder subir a la rama main se tenga que hacer mediante Pull Request.
Razones para proteger la rama main en un proyecto real:
- En la rama main debe haber un código estable.
- Este código debe ser revisado, validado y probado antes de subir a Producción
- Se tiene controlado que cambios son los que van a subir
- Se evita la posibilidad de subir cambios indebidos
- Es necesario para garantizar una buena trazabilidad de todos los cambios que han subido a Producción

