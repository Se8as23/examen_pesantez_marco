# Examen interciclo sistemas distribuidos 

He creado una carpeta Docker en donde esta todo lo nesesario para correr la aplicacion ingresamos con el cmd y ponemos el comando:

    docker build -t examen_pesantez_marco .

Esto hara que se construya la imagen despues de eso para ponerla en funcionamiento ingresamos el comando:


    docker run --name examen_pesantez_marco -p 3000:80 examen_pesantez_marco

Probamos que corra todo accediendo a la direccion `localhost:3000`, esto debe mostrarnos nuestra pagina de bienvenida con el mensaje 'Bienvenido a mi servidor Docker con Angular!'
