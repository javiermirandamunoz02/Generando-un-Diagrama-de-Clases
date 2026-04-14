. Puntos Clave

Herencia: Las clases Alumno y Profesor heredan de Persona para no repetir datos (Nombre, RUT).

Encapsulamiento: Datos sensibles (notas, sueldos) son privados; solo se acceden mediante métodos públicos.

Relaciones:

Asociación: El Profesor dicta la Asignatura.

Agregación: La Asignatura contiene Alumnos (el alumno existe sin la materia).

Composición: La Institución crea sus Asignaturas (si el colegio cierra, la malla desaparece).