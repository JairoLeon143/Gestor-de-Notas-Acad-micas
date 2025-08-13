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

	PROCEDIMIENTO menu_registro_notas()
    opcion ← 0

    MIENTRAS opcion ≠ 6 HACER
        IMPRIMIR ""
        IMPRIMIR "MENÚ PRINCIPAL - REGISTRO DE NOTAS"
        IMPRIMIR "1. Ingresar nota de estudiante"
        IMPRIMIR "2. Modificar nota existente"
        IMPRIMIR "3. Eliminar nota"
        IMPRIMIR "4. Mostrar todas las notas"
        IMPRIMIR "5. Calcular promedio general"
        IMPRIMIR "6. Salir"

        LEER opcion

        SI opcion = 1 ENTONCES
            IMPRIMIR "Ingresando nota..."
            // Acción para ingresar nota

        SINO SI opcion = 2 ENTONCES
            IMPRIMIR "Modificando nota..."
            // Acción para modificar nota

        SINO SI opcion = 3 ENTONCES
            IMPRIMIR "Eliminando nota..."
            // Acción para eliminar nota

        SINO SI opcion = 4 ENTONCES
            IMPRIMIR "Mostrando todas las notas..."
            // Acción para mostrar notas

        SINO SI opcion = 5 ENTONCES
            IMPRIMIR "Calculando promedio general..."
            // Acción para calcular promedio

        SINO SI opcion = 6 ENTONCES
            IMPRIMIR "Saliendo del sistema..."

        SINO
            IMPRIMIR "Opción no válida. Intente de nuevo."
        FIN_SI
    FIN_MIENTRAS
	FIN_PROCEDIMIENTO


## Continuará proyecto...
