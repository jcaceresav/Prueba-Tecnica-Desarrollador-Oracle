# Prueba-Tecnica-Desarrollador-Oracle
This repository stores a variety of database objects -  Oracle Database.

Repo/Folder name	Description
C	C examples
apex	APEX examples
db-sample-schemas	Git submodule of the Oracle Database Sample Schemas
dotnet	.NET based examples
exadata	Exadata examples
java	Java examples
javascript	JavaScript examples
machine-learning	Oracle Machine Learning examples
optimizer	Oracle Optmizer and Optimizer Stats examples
plsql	PL/SQL examples
python	Python examples
ruby	Ruby examples
sagas	Saga examples
security	Security features examples
spatial	Spatial features examples
sql	SQL examples
sqldeveloper	SQL Developer examples
txeventq	TxEventQ examples
Documentation
You can find the online documentation of the Oracle Database under docs.oracle.com/en/database/

LiveSQL
Some of the examples that you see within this repository can be executed in the free web-based tool: LiveSQL.oracle.com.

LiveSQL is also an excellent resource for getting started with Oracle Database.

Dev Gym
If you would like to challenge yourself, you can take quizzes, workouts and classes at DevGym.oracle.com.

Contributing
This project welcomes contributions from the community. Before submitting a pull request, please review our contribution guide

Security
Please consult the security guide for our responsible security vulnerability disclosure process

License
You may not use the identified files except in compliance with the Apache License, Version 2.0 (the "License.")

You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0. A copy of the license is also reproduced in LICENSE.md

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and limitations under the License.


















¡Hola, Crack! 🙌

Sabemos que las pruebas técnicas son desgastantes y algo pesadas, pero creemos que un buen proceso de selección es el que nos permite ver el potencial de una persona y también le permite al candidato(a) si este va a ser un trabajo retador, divertido, apasionante y acorde a tus expectativas. Date la oportunidad de hacer esto a conciencia no para pasar una prueba, sino para entender si este es el lugar adecuado para tu crecimiento profesional.🚀🔥

En el siguiente Link podrás encontrar la prueba técnica. El tiempo de entrega es máx. en 2 días; sin embargo, si la envías antes tendrás puntos extra :)

¡¡Quedo atenta a cualquier duda que pueda surgir!!  ✍️📲

Te dejo mi correo: welcome@doublevpartners.com / deysi.perez@doublevpartners.com y mi cel:324 4839193.

¡Muchos éxitos! 🤞🚀

Un Abrazo

Equipo People - DVP 

===========================================================================================================================
                   https://url9191.buk.co/ls/click?upn=u001.vULe7lq9W5O0hD80dms4zOywytZLgvogaWO8whfSLQPTkdDQVdK3sM03CuNdpwQ7rX50333Z-2BtOR7o7Tn7kqJmhhagesPnnYTcjuvdVMsfljD3t2l7ocfuFjvBiGy1dGahwJ_qrZ-2BMAxz33wnBiZlghkMLkx1rhGMNjXlFuA9ym8lep5U8-2Bulr3hIiTXRG3QpRQux7IlyTrqGplrK-2BHABiF3Qz5VfqEFpfCHXVVd-2BtLMN-2F5xSthW3DSl3mNW0U2GQa3s2aMqVEPgukRQz489FPuxxN2iPVdRVTDgmYKMWXfl18ar1YaGSmYvu3JxlO94dRjWlYmjimolbYWWkhWJ5HZ13SF-2BcgSAqosnj1GBG1-2BJvUItukqMwDMosUf-2FiPb1Re6JlPtArDwgpE-2B-2FW5OQIUMzI-2F9FXxlDta-2Fyxm-2F2Q1TWsvK18vtQu3Tm-2Brwa89-2B-2FSNO8ZNf1jPi4bv5eeXmd-2FZrwbBONLLJ6L0z80pwSivmGLMoHEOU91b5kM2EI2zaAfhwfEXm8AsTgSUhuMNq82x211YoQHMsLPqG8Zv29EmLDToqlQz8kkJpGJnIE6iwKAzsgB
                   
===========================================================================================================================

Prueba Técnica Desarrollador Oracle
Estimado(a) candidato(a).
Nos enorgullece saber que Double V Partners tiene el potencial de ser parte
de tu proyecto de vida. Sabemos que las prueba técnicas son desgastantes y
algo pesados, pero creemos que un buen proceso de selección es el que nos
permite ver el potencial de una persona y también le permite al candidato(a)
si este va a ser un trabajo retador, divertido, apasionante y acorde a tus
expectativas. Date la oportunidad de hacer esto a conciencia no para pasar
una prueba, sino para entender si este es el lugar adecuado para tu
crecimiento profesional.
Instrucciones
Duración: Tienes un plazo de 2 días a partir de la recepción de esta prueba
para completarla.
Entrega: Debes subir tu solución a un repositorio GitHub y enviar el enlace
al correo welcome@doublevpartners.com con el asunto “Prueba Técnica + [Tu
Nombre]”.
Formato de Entrega:
● Incluye un archivo README.md con instrucciones detalladas para
ejecutar y probar tu solución.
● Asegúrate de que el repositorio esté organizado y que el código esté
correctamente documentado.

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
● Procedimientos almacenados:
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

2

3. Exposición de Procedimientos como Servicios REST con ORDS
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
                   




