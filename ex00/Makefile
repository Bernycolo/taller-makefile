# Crear una variable
SALUDO = "hello world"

# Crear una regla para que ejecute un hello world
run:
	echo $(SALUDO)

# Crear un directorio y un archivo
create:
	mkdir folder
	touch folder/file

# Establecer el contenido de un archivo (sobreescribir)
set:
	echo "hello world!" > folder/file

# Añadir contenido a un archivo (sin sobreescribir)
append:
	echo "hello world!" >> folder/file

# Mostrar el contenido de un archivo
show:
	cat folder/file

# Limpiar los archivos y directorios creados
rm:
	rm -rf folder/file

# Ejecutar clean y luego create
re: rm create

# Declarar PHONY
.PHONY: run create set append show rm re

