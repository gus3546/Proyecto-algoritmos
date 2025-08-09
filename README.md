# GESTOR DE NOTAS
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

     Inicio

     Definir opcion Como Entero
 
     Mientras opcion != 6 HACER
        Imprimir "Gestor de Notas Académicas"
        Imprimir "1. Registrar nuevo curso"
        Imprimir "2. Mostrar todos los cursos y notas"
        Imprimir"3. Calcular promedio general"
        Imprimir "4. Buscar curso por nombre"
        Imprimir"5. Eliminar un curso"
        Imprimir "6. Salir"
        Imprimir "Seleccione una opción:"
        Leer opcion

        Si opcion = 1 ENTONCES
            <registrar_nuevo_curso>
        Sino Si opcion = 2 Entonces
            <mostrar_cursos_y_notas>
        Sino Si opcion = 3 Entonces
            <calcular_promedio_general>
        Sino Si opcion = 4 Entonces
            <buscar_curso_por_nombre>
        Sino Si opcion = 5 Entonces
            <eliminar_curso>
        Sino SI opcion = 6 Entonces
            Imprimir "Gracias por usar el Gestor de Notas Académicas"
        Sino
            Imprimir "Opción inválida. Intente de nuevo."
        Finsi
    Finmientras
    Fin

