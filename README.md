Práctica final voluntaria

1.	En el proyecto del curso que desarrollamos en visual studio code, genere una nueva entidad llamada Cliente con las siguientes propiedades:
a.	Id
b.	Nombre
c.	Apellidos
d.	Direccion
2.	Agregue a esta clase como entidad de entity framework

3.	Ingrese a neon tech oncloud, y genere una nueva base de datos.
4.	Configure en el proyecto api la nueva cadena de conexión, reemplace la anterior
5.	Elimine la carpeta migrations del proyecto api, la idea es volver a crear nuevos archivos de migración incluyendo la nueva entidad Cliente
6.	Una vez eliminados estos componentes, realice el proceso de migración para generar la tabla cliente en la nueva base de datos postgres en neon tech oncloud

7.	Genere una nueva interface llamada IClienteService, luego creará una clase que llamara ClienteService 
8.	Dentro de este service creara dos métodos	
a.	CrearClientes()
i.	Este metodo recibirá como parámetro un objeto cliente para insertarlo en la base de datos.
b.	EditarClientes()
i.	Este método recibirá como parámetro un objeto cliente existente y lo actualizará en la base de datos
c.	Consultar todos los clientes de la tabla clientes de la base de datos.

d.	ConsultarClientesPorNombre()
i.	Creará una consulta para retornar un cliente pasándole como parámetro el nombre

9.	Crear dentro de Blazor una página llamada clientes, que desplegará la lista de clientes.
10.	Crear dentro de Blazor una página EditarCliente para crear o editar un cliente.
