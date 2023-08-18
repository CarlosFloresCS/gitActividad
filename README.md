# Aclaracion
Mi compañero fernando no tenia su laptop por eso hicimos el trabajo en mi local, es por ello que la terminal de ambos es la misma.
# INTEGRANTES
- Carlos Alonso Flores Panduro
- Fernando Adriano Choqque Mejía

# Terminal carlos
   gitActividad git init
ayuda: Usando 'master' como el nombre de la rama inicial. Este nombre de rama predeterminado
ayuda: está sujeto a cambios. Para configurar el nombre de la rama inicial para usar en todos
ayuda: de sus nuevos repositorios, reprimiendo esta advertencia, llama a:
ayuda: 
ayuda:  git config --global init.defaultBranch <nombre>
ayuda: 
ayuda: Los nombres comúnmente elegidos en lugar de 'master' son 'main', 'trunk' y
ayuda: 'development'. Se puede cambiar el nombre de la rama recién creada mediante este comando:
ayuda: 
ayuda:  git branch -m <nombre>
Inicializado repositorio Git vacío en /home/flowers/Escritorio/uni/Software/gitActividad/.git/
   gitActividad   git:(master) ✗ git add app.py && git commit -m "primer commit" && git remote add origin https://github.com/CarlosFloresCS/gitActividad.git && git push --set-upstream origin master 
[master (commit-raíz) 1343f00] primer commit
 1 file changed, 9 insertions(+)
 create mode 100644 app.py
Enumerando objetos: 3, listo.
Contando objetos: 100% (3/3), listo.
Compresión delta usando hasta 6 hilos
Comprimiendo objetos: 100% (2/2), listo.
Escribiendo objetos: 100% (3/3), 326 bytes | 326.00 KiB/s, listo.
Total 3 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/CarlosFloresCS/gitActividad.git
 * [new branch]      master -> master
rama 'master' configurada para rastrear 'origin/master'.
   gitActividad   git:(master) git branch feature1        
   gitActividad   git:(master) git checkout feature1
Cambiado a rama 'feature1'
   gitActividad   git:(feature1) git add app.py && git commit -m "commit feature1 de carlos" && git push --set-upstream o
rigin feature1
[feature1 7ae61d2] commit feature1 de carlos
 1 file changed, 1 insertion(+), 1 deletion(-)
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 6 hilos
Comprimiendo objetos: 100% (2/2), listo.
Escribiendo objetos: 100% (3/3), 311 bytes | 311.00 KiB/s, listo.
Total 3 (delta 1), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'feature1' on GitHub by visiting:
remote:      https://github.com/CarlosFloresCS/gitActividad/pull/new/feature1
remote: 
To https://github.com/CarlosFloresCS/gitActividad.git
 * [new branch]      feature1 -> feature1
rama 'feature1' configurada para rastrear 'origin/feature1'.

# Terminal fernando
   gitActividad   git:(master) git branch feature2
   gitActividad   git:(master) git checkout feature2
Cambiado a rama 'feature2'
   gitActividad   git:(feature2) git add app.py && git commit -m "commit feature2 de fernando" && git push --set-upstream o
rigin feature2
[feature2 69ed593] commit feature2 de fernando
 1 file changed, 1 insertion(+), 1 deletion(-)
fatal: 'o' does not appear to be a git repository
fatal: No se pudo leer del repositorio remoto.

Por favor asegúrate de que tengas los permisos de acceso correctos
y que el repositorio exista.
zsh: command not found: rigin
   gitActividad   git:(feature2) git push --set-upstream origin feature2 
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 6 hilos
Comprimiendo objetos: 100% (2/2), listo.
Escribiendo objetos: 100% (3/3), 315 bytes | 315.00 KiB/s, listo.
Total 3 (delta 1), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'feature2' on GitHub by visiting:
remote:      https://github.com/CarlosFloresCS/gitActividad/pull/new/feature2
remote: 
To https://github.com/CarlosFloresCS/gitActividad.git
 * [new branch]      feature2 -> feature2
rama 'feature2' configurada para rastrear 'origin/feature2'.
