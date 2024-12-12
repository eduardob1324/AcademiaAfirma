# AcademiaAfirma


```plantuml
@startuml
class Empleado {
  - nombre: String
  - calculadorSalario: CalculadorSalario
  + obtenerSalario(): double
}

interface CalculadorSalario {
  + calcularSalario(): double
}

class CalculadorSalarioPermanente {
  - salarioFijo: double
  + calcularSalario(): double
}
