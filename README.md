# T3A6---Ejercicio-con-POO

## Etapa 1. Descripción del problema
Una fábrica textil desea llevar el control de la nómina de sus empleados
en la matriz ubicada enTeziutlán y dos sucursales más (sucursal cdmx,
sucursal malecónVeracruz). Para calcular la nómina debe indicarse la 
cantidad de empleados, número de contrato, tipo de empleado, años de 
antigüedad, las horas laborales de contrato y el salario base, además
de su información básica (nombre, apellidos, RFC, CURP, email y teléfono).

Además del sueldo base se debe agregar un bono por antigüedad bajo las 
siguientes condiciones:

- De 0 a 2 años de antigüedad no se asigna bono.
- de 3 a 5 años de antigüedad se asigna un bono del 3% y si el trabajador es administrativo entonces
  el bono será del 4%.
- De 6 a 10 años de antigüedad recibe un bono adicional del 8% y si el trabajador es administrativo,
  entonces el bono será del 12%.
  
  ## Etapa 2. Diseño de a solución
  - Entrada:
    - int cantidadDeEmpleados
    - int numeroContrato
    - String tipoDeEmpleado
    - int añosDeAntigüedad
    - String horastrabajadas
    - float salarioBase
    - String nombre
    - String apellidoPaterno
    - String RFC
    - String CURP
    - String email
    - String telefono
    
  - Proceso:
    - Calcular la nomina de todos los empleados 
  
  - Salida:
  ~~~
  +-----------------------------------------------------------------+
  |                             NOMINA                              |
  +-----------------------------------------------------------------+
  | NOMBRE: ELVIZ CLAUDETTE     APELLIDO PATERNO: GARRIDO           |
  | RFC:                        CURP:                               |
  | N° DE CONTRATO: 128         HORAS TRABAJADAS: 80 HRS            |
  | SUCURSAL: TEZIUTLAN         SUELDO:                             |
  | BONO POR ANTIGUEDAD:                                            |
  +-----------------------------------------------------------------+
  
  ~~~
  
  ## Etapa 3. Diseño de la solución
  Diagrama de la clase
  ![](https://github.com/ElvizClaudette/T3A6---Ejercicio-con-POO/blob/main/T3A6.png)
  
  ## Etapa 4. Desarrollo de la solución
  https://github.com/ElvizClaudette/T3A6---Ejercicio-con-POO/blob/main/T3A6.zip
