# PORTAFOLIO
<h1>Fase 1</h1>
<a href="https://github.com/rclopezjativa/PORTAFOLIO---BD-APIREST">PORTAFOLIO---BD-APIREST</a>

# PORTAFOLIO
<h1>Fase 2</h1>
<h4>Método POST</h4>
<p align="left">
   <img src="https://img.shields.io/static/v1?label=Estado&message=Publicado en portafolio&color=success">
</p>
Contiene un formulario creado en REACTJS que consume la API REST creada en el repositorio <a href="https://github.com/rclopezjativa/PORTAFOLIO---BD-APIREST">PORTAFOLIO---BD-APIREST</a>, el mismo que servirá para administrar los datos de la base de datos; el objetivo es realizar un proceso CRUD (Consult, Read, Update, Delete) en este caso específicamente para la tabla Usuario.
<br><br><b>Autor: Ing. Roberto López</b>
<br><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/rlopezj?color=blue&style=flat-square">
<br><b>Interfases (HTML y URLs) - Ingresar registros a las tablas de MySQL</b>
<br><hr>
Se crea un formulario con tecnología REACTJS, en el mismo que se programa los diferentes métodos para interactuar con la base de datos MySQL (proceso C-R-U-D).
<br><br>El proyecto del formulario se encuentra cargado en este repositorio, encontrará el archivo "Fuentes.rar" con el proyecto creado con tecnología REACTJS y una subcarpeta "CRUD-REACT" con el "build" del formulario REACT.
<br><b><h4>NOTA:</h4></b>En el archivo "Fuentes.rar" no se encuentran los archivos de la carpeta "node_modules" ya que por la cantidad exagerada de archivos de los componentes no se pudo hacer, sin embargo se encuentran los archivos package.jason y package-lock.json para que se puedan regenerar con la herramienta "npm install".
<br><br>En esta fase, se programa:<br>
<UL><li>La carga de los registros de la tabla Usuarios; utilizando el método GET de la API REST, con la finalidad de que se muestren en una tabla del frormulario.</li>
    <li>Se programa el botón insertar que permite agregar un nuevo registro en la tabla Usuarios, se utiliza una ventana Modal construida con REACTJS.</li>
</UL>
<b><h4>NOTA:</h4></b> Por seguridad el hosting utilzado para publicar el API REST no permite accesos en background desde otros dominios ya que son utilizados estrictamente para crear sitios web.
<br><br>Para realizar pruebas de esta solución se deberá descargar el código del API REST e implemetarlo localmente, para ello pueden hacer uso de la herramienta <a href="https://www.apachefriends.org/download.html" target="_blank">XAMPP</a>
<br><br>Cabe mencionar que debe realizar los ajustes necesarios como son: la creración de la base de fdatos, la declaración de las credenciales de acceso a la base de datos, la configuración del dominio local "apirest.com", entre otros ajustes necesarios.
