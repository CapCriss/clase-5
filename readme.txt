INSTALAR  GIT

abrir gitbash en la carpeta que quiero o abir la app gitbash
    git --version
mkdir prueba crea carpeta
touch crea archivo agregar extension
rm elimina un archivo SIN CONFIRMACIÓN
clear limpia la consola


configuracion inicial
git config --global user.name "nombreQue usará de todos los archivos hechos desde el pc"
git config user.name Se pueden cambias las veces que sea desde el bash ya que se sobreescriben
git config user.email


cree repo en github repositorio-clase-5
git init en el bash dentro de la carpeta "clase 5 en mi caso"
git add. para añadir el archivo

git commit es como crear respaldos
git commit -m "COMMIT"
git remote add origin https://github.com/CapCriss/clase-5.git es el link del repositorio en github.
Solo se hace una vez.

git push -u origin master este crea en el origen la primera rama y que suba todo.
Aqui pide logear solo una vez a menos que cambie de email
Solo la primera vez que suba un proyecto nuevo.
luego solo es git push para subir los archivos nuevos

git status para saber que tengo oque cambios he hecho o puedo guardar
git add .
git commit



clonar para trabajar en un mismo proyecto
git clone https://github.com/CapCriss/clase-5.git
