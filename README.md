Ejercicio 1
Tomando como base el diagrama de diseño y la implementación en JAVA publicados en
aulas junto con la letra del obligatorio, desarrolle los siguientes casos de uso implementando
la interfaz de usuario en consola. Se debe poder acceder a cada caso de uso desde un
menú.
Tanto el diagrama de diseño como el código base en JAVA, implementan una solución
parcial del problema, por lo que deberá incluir lo que entienda necesario (a nivel de diseño y
de implementación) para implementar los casos de uso solicitados.
Importante: Si detecta que el diagrama entregado tiene alguna diferencia en relación al
código base entregado o viceversa, deberá actualizar ambas cosas.
Caso de uso CU1 – Anulación de factura
Precondición:
La factura deberá tener un código autonumerado en el alta de factura.
El stock de los productos de la factura se actualiza al confirmar la factura.
Estas funcionalidades no están implementadas en el código base, por lo que deberá
implementarlas.
Curso normal:
1) Se ingresa el código de Factura.
2) Se muestran los datos de la factura en el siguiente formato:
Factura Código: XXX
Detalle:
Cod Producto – Nombre Producto – Precio Unitario - Unidades - SubTotal
Monto total de la Factura: $ XXXX
3) Se solicita confirmación de la anulación de la factura. La factura no se debe eliminar
del sistema sino que debe quedar marcada como anulada.
Facultad de Ingeniería
Bernard Wand-Polak
Cuareim 1451
11.100 Montevideo, Uruguay
Tel. 2902 15 05 Fax 2908 13 70
www.ort.edu.uy
Página 3 de 5
Computación - Electrónica - Telecomunicaciones - Sistemas de Información
Cursos alternativos:
1) Si no existe una factura con ese código, fin de caso de uso
3) Si el usuario no confirma la anulación, fin de caso de uso.

Postcondición: El stock de cada producto debe quedar actualizado. Se deberá registrar la
fecha en la que se realizó la anulación.
Caso de uso CU2 – Elegir un proveedor de la lista de proveedores definidos en el
sistema y obtener un listado de las facturas anuladas que contengan productos del
proveedor indicado.
Curso normal:
1) Se elige un proveedor de una lista.
2) Se muestran un listado de las facturas anuladas del proveedor seleccionado. Se deben
listar en el siguiente formato.
CodigoFact: XX – Cantidad de Productos – Fecha anulación - Monto Total: $ XXXX
Cursos alternativos:
No hay
