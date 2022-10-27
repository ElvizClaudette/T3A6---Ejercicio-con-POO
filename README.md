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
    - int añosDeAntigüeda
    - String horastrabajas
    - float salarioBase
    - String nombre
    - String apellido Paterno
    - String RFC
    - String CURP
    - String email
    - String telefono
    
  - Proceso:
    - Calcular la nomina de todos los empleados 
  
  - Salida:
