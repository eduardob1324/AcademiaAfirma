# AcademiaAfirma
```plantuml
@startuml
abstract class Empleado {
  - nombre: String
  - apellidos: String
  - horaTrabajadas: double
  - direccion: string
  - telefono: string
  + calcularSalario(): double
}

class EmpleadoTemporal extends Empleado{
  - salario: double 
  + calcularSalario(): double
}

class EmpleadoPermanente extends Empleado{
 - salario: double 
  + calcularSalario(): double
}

