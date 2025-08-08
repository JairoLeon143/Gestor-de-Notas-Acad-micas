# Gestor de Notas Académicas

El objetivo del sistema es poder llevar un registro, consultas y manejo sobre las calificaciones de los estudiantes de los cursos. Está creado para utilizarse en centros educativos como colegios, institutos, universidades, etc., facilitando a los docentes el control en registro de notas de los estudiantes, de una manera rápida y sencilla. 

El enfoque es principalmente a docentes o estudiantes que necesiten llevar un control sobre notas o exámenes, ya que el sistema cubre esta necesidad de registrar nuevas notas, que se pueda corregir en caso que se requiera o eliminarlas si no son necesarias, también poder mostrar el promedio general. Es util para cualquier docente, ya que su utilidad es muy sencilla.

## Requisitos del sistema:
### -Funcionales: 

  **1. Registrar Nota De Estudiante:** Permite ingresar la nota que obtuvo el estudiante. 

  
  **2. Modificar nota existente:** Permite cambiar la nota que fue inresada del estudiante.

  
  **3. Eliminar nota:** Permite eliminar la nota ingresada.

  
  **4. Monstrar todas las notas:** Permite motstrar las calificaciones de los estudiantes registrados.

  
  **5. Calcular promedio general:** Permite calcular el promedio de toas las notas ingresadas.

  
### -No Funcionales: 
Desarrollado para ejercutarlo en consola en lenguaje **Python**


No es posible utilizar librerias externas, solo funciones básicas del lenguaje. 


Está desarrollado utilizando estructuras basicas  de control tales como: 


		**Bucle**: Mientras ... Hacer ... Fin_mientras (En Python: While)
		**Instrucciones** Como Imprimir, Leer Para Mostrar Y Recibir Datos Del Usuario.
		**Condicionales:** Si ... Entonces ... Sino ... Fin_si (En Python: If, Elif, Else)

# Pseudocódigo

	codigo = """def menu_registro_notas():
   	opcion = 0

    while opcion != 6:
        print("\\nMENÚ PRINCIPAL - REGISTRO DE NOTAS")
        print("1. Ingresar nota de estudiante")
        print("2. Modificar nota existente")
        print("3. Eliminar nota")
        print("4. Mostrar todas las notas")
        print("5. Calcular promedio general")
        print("6. Salir")

        try:
            opcion = int(input("Ingrese una opción: "))
        except ValueError:
            print("Entrada no válida. Debe ser un número.")
            continue

        if opcion == 1:
            print("Ingresando nota...")
            # <acción para ingresar nota>

        elif opcion == 2:
            print("Modificando nota...")
            # <acción para modificar nota>

        elif opcion == 3:
            print("Eliminando nota...")
            # <acción para eliminar nota>

        elif opcion == 4:
            print("Mostrando todas las notas...")
            # <acción para mostrar notas>

        elif opcion == 5:
            print("Calculando promedio general...")
            # <acción para calcular promedio>

        elif opcion == 6:
            print("Saliendo del sistema...")

        else:
            print("Opcion no valida. Intente de nuevo.")

## Continuará proyecto...
