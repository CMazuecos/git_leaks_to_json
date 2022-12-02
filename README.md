# Git_leaks_to_json
Creamos un buscador de leaks en commits de github con un formato ETL (código comentado en el programa), extraemos los datos, los modificamos y acabamos cargándolos en un archivo json.
### Archivos necesitados
- 'git_leaks_json.zip': archivo zip con todos lo necesario para la ejecución del programa.
- Contenido 'git_leaks_json.zip': 'requirements.txt', 'git_leaks_json.py' y la carpeta skale-manager.
### Output
- Archivo json con los commits.
### Forma de ejecución del programa
- Descomprimir todo el zip en una misma carpeta y ejecutar desde esa carpeta.
- Posteriormente, instalamos todas las librerías necesarias escribiendo en la terminal 'pip install -r requirements.txt'.
- A continuación ejecutaremos el programa git_leaks.py.
- En extract se obtienen los commits del repositorio.
- En la función transform se transforman los commits y se añaden a una lista de commits, buscando en cada commit las palabras clave.
- Finalmente, se muestra por pantalla el resultado y se escribe en un json la lista de commits.
- También tenemos una función que controla el exit del programa cuando se hace Ctrl + C.
