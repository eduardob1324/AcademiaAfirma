# AcademiaAfirma


### diagrama de clases 
<img src="diagrama.png" width="400" />

## Explica cómo el principio de Responsabilidad Única (SRP) aplica al caso anterior
> En el caso anterior, el principio de Responsabilidad Única se aplica de la siguiente manera:

La clase Empleado tiene una sola responsabilidad: representar a un empleado en general. No tiene responsabilidad de calcular el salario, ya que eso depende del tipo de empleado.
La clase EmpleadoPermanente tiene una sola responsabilidad: calcular el salario de un empleado permanente. No tiene responsabilidad de representar a un empleado en general, ya que eso es responsabilidad de la clase Empleado.
La clase EmpleadoTemporal tiene una sola responsabilidad: calcular el salario de un empleado temporal. Al igual que la clase EmpleadoPermanente, no tiene responsabilidad de representar a un empleado en general.
