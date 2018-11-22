# FinanzUP!
Calculadora financiera para plazos fijos y préstamos.
Permite guardar usuarios y relacionarlos con los préstamos o plazos fijos solicitados.

## :floppy_disk: Instalación

```bash
# clonar el repositorio
$ git clone https://github.com/marcorichetta/FinanzUP.git

$ cd FinanzUP

# Crear un virtualenv (Opcional)
$ python3 -m venv mivirtualenv -> Nombre del virtualenv

# Activamos el virtualenv
$ source mivirtualenv/bin/activate (Linux)

# Instalar las dependencias
$ pip install -r requirements.txt
```
## :database: Base de Datos
El sistema fue hecho con una base de datos sqlite3.
```
# Para generar la base de datos
$ sqlite3 prueba.db < creacionDB.sql
```
## :hammer: Uso
```
$ flask run
```
Por defecto sirve el contenido en la dirección http://127.0.0.1:5000/ en el navegador.
