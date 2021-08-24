# Sistemas-Distribuidos-TP-2-Punto-2
Repositorio correspondiente al punto 2 del trabajo practico numero 2 de Sistemas Distribuidos

En este punto se creo una REST API usando Spring, y para probarla podemos usar Postman y conectarnos a una instancia de MongoDB que corra en el puerto 27017. 

Las llamadas son al localhost:8080 y tenemos los metodos GET/ Para traer todos los estudiantes, GET/byStudentNumber/{studentNumber} ,para traer estudiantes por los nombres

GET /byEmail/ {email} para traer algun estudiante segun su email, POST /save para agregar estudiantes con formato

JSON y/delete/{studentNumber} para borrar segun el id de estudiante.
