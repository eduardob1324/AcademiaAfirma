# AcademiaAfirma
```plantuml
@startuml
abstract class Empleado {
  - nombre: String
  - apellidos: String
  - horaTrabajadas: double
  - direccion: string
  - telefono: string
  + obtenerSalario(): double
}

class EmpleadoTemporal CalculadorSalario {
  -double 
  + calcularSalario(): double
}

class CalculadorSalarioPermanente {
  - salarioFijo: double
  + calcularSalario(): double
}

```plantuml


@startuml
class ArrayList implements List
class ArrayList extends AbstractList
@enduml
