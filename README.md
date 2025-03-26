

Adjunto los ejercicios de la prueba Técnica:
1. Base de Datos Oracle y PL/SQL
Objetivo: Crear una tabla Personas y desarrollar procedimientos almacenados
asociados.
Requerimientos:

○ Crear la tabla Personas con los campos:
○ ID (clave primaria, autoincremental).
○ Nombres (VARCHAR2(50), no nulo).
○ Apellidos (VARCHAR2(50), no nulo).
○ NumeroIdentificacion (VARCHAR2(20), único, no nulo).

○ TipoIdentificacion (VARCHAR2(5), no nulo, valores: 'CC', 'TI',
'NIT', 'PAS').
○ Email (VARCHAR2(100), único, no nulo, formato válido).
○ Salario (NUMBER(10,2), no nulo, >= 0).
○ Estado (VARCHAR2(10), no nulo, valores: 'ACTIVO', 'INACTIVO').
○ Columnas calculadas:
■ IdentificacionCompleta (concatenación de
TipoIdentificacion y NumeroIdentificacion).
■ NombreCompleto (concatenación de Nombres y Apellidos).

● Implementar:
○ Validaciones y restricciones necesarias.
○ Trigger para convertir Nombres y Apellidos a mayúsculas en
inserciones/actualizaciones.

Procedimientos almacenados:
○ sp_InsertarPersona para insertar registros en Personas,
manejando excepciones y devolviendo mensajes informativos.
○ sp_ActualizarPersona en base al identificador ingresado debe
actualizar el registro en Personas,

● Datos de prueba:
○ Inserta al menos 5 registros utilizando sp_InsertarPersona.
○ Actualizar al menos 3 registros utilizando sp_ActualizarPersona.

2. Procedimiento para Actualizar Salarios
Objetivo: Crear un procedimiento que ajuste el salario de un empleado según
ciertas condiciones.
Requerimientos:
● Stored Procedure sp_AjustarSalario:
○ Recibe el ID de un empleado.
○ Consulta el Salario actual.
○ Si el Salario es < 2000, aumenta un 10%.
○ Si el Salario es ≥ 2000, no realiza cambios.
○ Actualiza el Salario si aplica y devuelve el nuevo valor.
○ Maneja excepciones si el ID no existe.
Exposición de Procedimientos como Servicios REST con ORDS
Objetivo: Exponer los procedimientos sp_ConsultarPersonas y
sp_ActualizarPersona como servicios REST utilizando Oracle REST Data
Services (ORDS).
Requerimientos:
● Configura ORDS para crear un endpoint RESTful en /api/personas.
● El servicio debe contener los siguientes verbos HTTP:
GET: Utilizando consultas SQL directas, para obtener solo el registro activo.
POST: Utilizar sp_InsertarPersona para insertar una nueva persona.
PUT: Utilizar sp_ActualizarPersona para actualizar el registro.
DELETE: Utilizando Código PLSQL para eliminar de forma lógica el registro.
● Documentación:
○ El candidato debe proporcionar documentación de la API
utilizando el formato OpenAPI.
○ Proporciona ejemplos de solicitudes y respuestas (Payloads).
○ Incluye instrucciones para configurar y probar el servicio.
● Seguridad:
○ Implementa medidas básicas como autenticación.

Quedo atent@ de cualquier duda o inquietud que pueda surgir.

¡¡¡Mucha suerte y gracias por el tiempo que nos dedicas :) !!!
