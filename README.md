# Gestor de notas 
Un estudiante necesita llevar un mejor control sobre sus notas académicas, y el objetivo principal de este proyecto será mejorar la organización y obtener mayor eficiencia en la gestión de las calificaciones.

El sistema permite al usuario registrar, visualizar, modificar, eliminar, analizar y organizar las notas de los cursos en los que está inscrito, todo desde una interfaz sencilla que se ejecuta en la consola.

Al cubrir necesidades como la organización de cursos, el seguimiento del progreso académico y la posibilidad de analizar el desempeño en diferentes materias, el Gestor de Notas Académicas ayudará a los estudiantes a conocer y gestionar mejor su rendimiento y sus calificaciones.

## Requisitos
## Funcionales
Registrar nuevo curso

Mostrar todos los cursos y notas

Calcular promedio general

Contar cursos aprobados y reprobados

Buscar curso por nombre (Lineal

Actualizar nota de un curso

Eliminar un curso

Ordenar curso por nota

Ordenar curso por nombre 

Buscar curso por nombre (Binaria)

## No funcionales
Debe usar bucles y condicionales en el código

El sistema se ejecuta en consola con Python

No utiliza librerías externas

La lógica inicial debe estar escrita en pseudocódigo antes de su implementación

## Pseudocodigo

INICIO
    Definir opcion Como Entero
    
    MIENTRAS opcion != 6 HACER
        IMPRIMIR "Gestor de Notas Académicas"
        IMPRIMIR "1. Registrar nuevo curso"
        IMPRIMIR "2. Mostrar todos los cursos y notas"
        IMPRIMIR "3. Calcular promedio general"
        IMPRIMIR "4. Buscar curso por nombre"
        IMPRIMIR "5. Eliminar un curso"
        IMPRIMIR "6. Salir"
        IMPRIMIR "Seleccione una opción:"
        LEER opcion

        SI opcion = 1 ENTONCES
            <registrar_nuevo_curso>
        SINO SI opcion = 2 ENTONCES
            <mostrar_cursos_y_notas>
        SINO SI opcion = 3 ENTONCES
            <calcular_promedio_general>
        SINO SI opcion = 4 ENTONCES
            <buscar_curso_por_nombre>
        SINO SI opcion = 5 ENTONCES
            <eliminar_curso>
        SINO SI opcion = 6 ENTONCES
            IMPRIMIR "Gracias por usar el Gestor de Notas Académicas"
        SINO
            IMPRIMIR "Opción inválida. Intente de nuevo."
        FIN_SI
    FIN_MIENTRAS
    FIN

