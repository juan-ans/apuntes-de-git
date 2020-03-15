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


git init  para inicializar el git de donde voy a trabajar 
git log   para ver los commit que he realizado
git rm    para eliminar un archivo completamente
git checkout --archivo    para recuperar un archivo que borre 
git mv  renombrar el archivo