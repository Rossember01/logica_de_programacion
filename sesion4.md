<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4

# Actividad 4: Ejercicios de control de flujo con expresiones compuestas


// Variables de tipo String

String nombre = "Juan Pérez";

String apellido = "González";

String identificación = "1000000001";

String correo = "juan.perez@ejemplo.com";

String carrera = "Desarrollo de Software";

String universidad = "Cesde";

// Variable de tipo int

int edad = 20;

// Variable de tipo boolean

boolean esActivo = true;

boolean becado = false;

// Variable de tipo char

char género = 'M';

// Variable de tipo double

double promedio = 4.5;

// Variable de tipo int

int semestre = 2;


 - Con la información anterior, implementa los siguientes ejercicios:


 - Determinar si el estudiante es mayor de edad y tiene un estado activo.
 - Determinar si el estudiante tiene una beca o una carrera relacionada con el desarrollo de software.
 - Determinar si el estudiante está en el último semestre de su carrera y tiene un estado activo.
 - Determinar si el estudiante tiene una carrera relacionada con el desarrollo de software y un promedio superior a 4.0.
 - Mostrar toda la información del estudiante si está matriculado en el Cesde.
 - Asignar una beca del 50% si el estudiante está matriculado en el Cesde, tiene un promedio superior a 4.0 y está activo.
 - Determinar la cantidad de beca que recibe el estudiante según su promedio:

0.0 - 3.4: El estudiante no recibe beca.

3.5 - 3.9: El estudiante recibe una beca parcial del 25%.

4.0 - 4.4: El estudiante recibe una beca parcial del 50%.

4.5 - 5.0: El estudiante recibe una beca completa.


# Solución


```java
package SESION4;

public class Sesion4LP {

    public static void main(String[] args) {

        String nombre = "Juan Pérez";
        String apellido = "González";
        String identificación = "1000000001";
        String correo = "juan.perez@ejemplo.com";
        String carrera = "Desarrollo de Software";
        String universidad = "Cesde";
        // Variable de tipo int
        int edad = 20;
        // Variable de tipo boolean
        boolean esActivo = true;
        boolean becado = false;
        // Variable de tipo char
        char género = 'M';
        // Variable de tipo double
        double promedio = 4.5;
        // Variable de tipo int
        int semestre = 2;

        System.out.println("------------------------");
        System.out.println("Ejercicio 1");
        if (edad >= 18 && esActivo) {
            System.out.println("Es mayor de Edad y esta Activo");
        }

        System.out.println("------------------------");
        System.out.println("Ejercicio 2");
        if (promedio >= 3.5) {
            becado = true;
            System.out.println("tiene beca");

            if (carrera == "Desarrollo de Software") {

                System.out.println("Estudia Desarrollo de Software");
            }

            System.out.println("------------------------");
            System.out.println("Ejercicio 3");
            if (semestre != 3)
                ;
            System.out.println("No se encuentra en el ultimo semestre");

        }
        if (esActivo) {
            System.out.println("Esta Activo");
        }

        System.out.println("------------------------");
        System.out.println("Ejercicio 4");

        if (carrera == "Desarrollo de Software")
            ;
        {
            System.out.println("tiene una carrera relacionada con el desarrollo de software");
        }

        if (promedio >= 4.1)
            ;
        {
            System.out.println("tiene un promedio superior a 4");
        }

        System.out.println("------------------------");
        System.out.println("Ejercicio 5");

        if (universidad == "Cesde")
            ;
        {
            System.out.println("nombre");
            System.out.println("apelliso");
            System.out.println("identificacion");
            System.out.println("correo");
            System.out.println("carrera");
            System.out.println("universidad");
            System.out.println("edad");
            System.out.println("es activo");
            System.out.println("becado");
            System.out.println("genero");
            System.out.println("promedio");
            System.out.println("semestre");
        }

        System.out.println("------------------------");
        System.out.println("Ejercicio 6");

        if (universidad == "Cesde" && promedio >= 4.1 && esActivo)
            ;
        {
            System.out.println("El estudiante tiene beca del 50%");
        
        }

        System.out.println("------------------------");
        System.out.println("Ejercicio 7");

        if (promedio >=4.5);{
            System.out.println("El estudiante tiene beca completa");
                }
    }
}



```










