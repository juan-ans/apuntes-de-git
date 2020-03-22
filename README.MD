## curso git desde cero

Sistema de comtrol de verciones para el mantenimiento eficioente y confiable de archivos.

##Zonas de git
1. Directorio de trabajo
2. area de preparscion
3. directorio Git

### Flujo de trabajo basico en Git
1.Modificar una serie de archivos en un directorio de trabajo.
2.Preparas los archivos, añadiendo a tu area de preparacion.
3.Confirma los cambios, lo que toma los archivos tal y como estan en el area de preparacion y almacena esa copia instantanea de manera permanente en tu directorio Git.

### Configurando Git por primera vez
git config --global user.name "Juan Carlos"
git config --global user.email ans.juancarlos.1987@gmail.com
git config --global core.editor nano
git config --list

### git log
git log oneline   muestra los hast de los puntos en la historia
git log --graph
git log --oneline --graph 
git log-2
git log --help
git log --pretty=format:"%h - %an, %ar : %s"
git log --after="2016-04-07"
git log --before="2016-04-08"
git log --after="2016-04-07 11:00:00" --before="2016-04-08 11:30:00"
git log --decorate
git log --decorate --oneline --graph --all




git init  para inicializar el git de donde voy a trabajar 
git log   muestra el historial de confirmaciones
git rm    para eliminar un archivo completamente
git checkout -- archivo    para recuperar un archivo que borre 
git mv  renombrar el archivo


git commit --amend   reace la confirmacion
git reset HEAD <archivo>


clonar el repositorio
git clone https://github.com/escueladigital/EDgrid.git mi-propio-ed-grid

etiqueta ligera y etiqueta anotada
git tag version1.1-dev

git tag -a version1.0 -m "mi version de prueba 1"
git tag -l "v1.*"   uso de patrones para filtrar las etiquetas

git show

git branch --help    este comando es para ver la ayuda de branch

git branch -d rama    para eliminar una rama ya fucionada

git merge nombre_rama  para fucionar con la rama donde estamos ubicados

git branch --no-merged las ramas que no han sido fucionadas a la rama actual

