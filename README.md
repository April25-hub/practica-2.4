print(" ")
print("Arzaba Diaz April")

def calificaciones_materias():

    """
    
    Pide las calificaciones de cada materia y las muestra en pantalla.
    
    """
    
    materias = ["Pensamiento matematico", "Español", "Ingles", "Quimica", "Civismo", "Frances"]
    
    calificaciones = []



    for materia in materias:
    
        calificacion = input(f"Ingresa la calificacion de {materia}: ")
        
        calificaciones.append(calificacion)



    for materia, calificacion in zip(materias, calificaciones):
    
        print(f"En {materia} has obtenido {calificacion}.")



# Llamar a la funcion

calificaciones_materias()
![image](https://github.com/user-attachments/assets/d43d4ced-27d7-4b4e-b13b-97d3beb2eaeb)
![image](https://github.com/user-attachments/assets/2daea3f1-e520-4a87-ba59-d42ceef91b07)


