# ER-01: Empleados y Departamentos

## Enunciado
Gestionar información de empleados (DNI, nombre, fecha nacimiento, 
salario, departamento) y departamentos (nombre, nº despacho, jefe).

## Diagrama
<image src="er.png">

## Cardinalidades
- Empleado - Trabaja - Departamento: (1,N) : (1,1)
- Un departamento tiene 1 jefe; un empleado pertenece a 1 departamento

## Decisiones de diseño
- DNI como identificador principal del empleado
- Nº despacho como identificador del departamento

## Autor
Kaori — DAW
