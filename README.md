Proyecto:
SS Williams
                    	Cliente: 
Neuropsicólogo Carlos Alberto Serrano


Introducción:
 
El Neuropsicólogo Carlos Alberto Serrano Juárez, quién está realizando sus estudios para obtener el grado de Doctor, expresó que es de su interés demostrar que a través del uso de las tecnologías de la información se puede mejorar el proceso de atención de pacientes con Síndrome de Williams, describiendo los siguientes problemas:
 
Las actividades de atención para pacientes con Síndrome de Williams son demasiado caras, por lo que su seguimiento suele ser costoso.
Las actividades de estimulación así también, son de origen español y americano.
No existe un seguimiento de atención donde se observe el trabajo del paciente en sus respectivos espacios. (hogar)


Justificación:
 
Con el uso de las tecnologías de la información y de la aplicación web, el  Psicólogo, padre y/o tutor, podrá contar con información oportuna y confiable del seguimiento del paciente con Síndrome de Williams, así como realizar las citas. El psicólogo tendrá la oportunidad de tener el expediente de su paciente actualizado.
 
El paciente tendrá acceso a las actividades de atención  visoespacial en sincronía o asincrónica  con el psicólogo y facilitará la comunicación y ayudará a mejorar al paciente. 





Descripción de Requerimientos:
 
Desarrollar una aplicación web para pacientes con Síndrome de Williams que mejore sus procesos de atención y habilidades visoespaciales, obteniendo información más exacta y confiable. Se deben manejar 4 tipos de usuarios, siendo estos el Administrador, quien se encargará de la gestión global del sistema, refiriéndose así al registro, la consulta y la eliminación de la sesión de los psicólogos para su correcto funcionamiento; los Psicólogos, que se encargaran de hacer sus actividades de trabajo correspondientes, registrar a sus pacientes, sus citas e información de estas, solo teniendo acceso a su sesión correspondiente, siendo registrados por el administrador; niños con el síndrome de Williams, que se puedan registrar e interactuar con la pagina; y por último los padres o tutores de éstos, quienes podrán ver los progresos de los niños. El ambiente del sistema deberá contar con colores propios de la Universidad Nacional Autónoma de México (dorado y azul), logotipos de dicha escuela y de la especialidad de ciencias humanas. El sistema debe ser interactivo para el uso de los niños, que contenga una serie de juegos específicos que les ayude en su desarrollo.
 
 



















Requerimientos Funcionales:
 

1.- Registro e inicio de sesión de usuarios:

Inicio de sesión del administrador responsable del sistema para acceso y control   de la información con los siguientes datos:
Nombre de usuario.
Contraseña.

Registro de psicólogos, hecho por el administrador del sistema, con los siguientes datos:
Nombre.
Cedula Profesional.
Contraseña única.
Horario
Días de la semana (lunes a sábado)
Horario


Después del registro, el psicólogo podrá iniciar su sesión con su cedula profesional y su contraseña correspondiente.

Registro de pacientes a atender realizado por el psicólogo, que deberá contener la siguiente información:
Nombre. (apellido paterno.-materno-nombres)
Sexo.
Femenino
Masculino
Edad.
Fecha de nacimiento. (dia-mes-año
Lugar de nacimiento.
Lateralidad.
Diestro


Escolaridad.
Jardín de niños
Preescolar
Primaria
Secundaria
Clave de paciente.
RFC 
Contraseña única.

Después del registro, el paciente podrá iniciar su sesión con su clave de paciente y su contraseña correspondiente.


Registro de padres de familia o tutores de los pacientes, que será realizado por el psiquiatra en turno y llenar los campos del siguiente formulario:
Nombre
Domicilio (Calle, No. Interior, No. Exterior, Colonia, C.P., Delegación. Ciudad).
Ocupación.
Escolaridad.
Teléfono (Casa, Oficina). 


2.- Citas:

 Registro de citas de pacientes realizado por el psicólogo con los siguientes datos:
Fecha del registro ( generada por el sistema)
Nombre del psicólogo
Dia, fecha y hora de la cita.
Nombre del paciente.

 Historial de citas, que cada psicólogo podrá consultar desde su sesión en el sistema.


3.- Pacientes:

      Expediente del paciente, que se conformará de la siguiente información: 
Datos personales del paciente.
Datos de comunicación con padre de familia o tutor.
Diagnóstico del paciente.
Medicamentos.
Estudios realizados. 
Citas solicitadas.
Citas realizadas.
Citas canceladas.
Será editado únicamente por el psicólogo que atiende a determinado paciente.

Actividades visoespaciales realizadas por el paciente.
(Las Actividades son para 6to semestre)
Resultados obtenidos por periodos que podrá visualizar el psicólogo encargado de dicho paciente. 


4.- Actividades de estimulación:

Actividades de atención por tema realizadas por el paciente desde el  sistema.
¿Cuales son los temas?
Actividades visoespaciales por tema para mejorar la calidad de tratamiento.
¿Cuales son las actividades?


5.- Información:

El sistema tendrá que tener la siguiente información distribuida por la página:
      ¿Qué es el Síndrome de Williams?.
      Síntomas.
      Diferencias con otras enfermedades.
      Información para Padres, tutores y/o profesores.


6.- Contacto:

El sistema mostrará la siguiente información de contacto:
Teléfonos.
Correo electrónico.
Requerimientos No-Funcionales:
 

1.- Seguridad: 

Se creará una base de datos en MySQL para poder guardar toda la información y tener mayor seguridad con la encriptación de datos de los usuarios y psicólogos. 

2.- Interfaces: 

Todas las ventanas de cualquier tipo de usuario tendrán una interfaz definida con los colores representativos de la UNAM, y deberá ser  fácil de manejar por todos los usuarios.

3.- Validación: 

Todos los campos deben estar validados minuciosamente para que el sistema funcione de la manera adecuada y no presente errores en la base de datos.

4.- Tiempo de Acción: 

El sistema debe ser veloz cuando se pide cierta información, por ello, debe estar lo más comprimido posible y así no utilizar demasiada memoria que pueda retrasar su tiempo de acción.

5.- Almacenamiento:

La capacidad del almacenamiento del sistema será dependiendo de cuánto espacio en memoria se tenga en la máquina donde se instalará.

 


 
Requerimientos de Hardware y Software:
        
En el área de Hardware se necesita un equipo funcional capaz de soportar la plataforma con un rendimiento óptimo y para que funcione de esa manera deberá contar con las siguientes características:

Memoria RAM de 2GB.

Procesador de 4 núcleos a 1.50 GHz y tarjeta gráfica de 520 MB.
Teclado, mouse optico y bocinas

En cuanto al software, el sistema deberá contar con los siguientes requerimientos para su funcionamiento óptimo:

El sistema operativo de este equipo tendrá que ser Windows 7 o posterior.    (32 bits y 64 bits)

SQL Server 2008 R2 (32 bits y 64 bits) Standard Edition.

Java SE 1.5 o superior.

Navegador Web. (Chrome, Internet Explorer, Firefox)








 

Evolución del Sistema
 
Mediante actualizaciones programadas, se implementará al sistema una serie de actividades que servirán para el tratamiento de los pacientes con síndrome de Williams y edición de datos sobre nuevos descubrimientos o datos innovadores para el tratamiento de este problema, de igual manera se optimizará y adaptará el sistema para otros sistemas operativos (Linux, OS, Mejora de rendimiento en Windows 10) siendo pues, una aplicación en constante renovación con seguimiento y mantenimiento de aproximadamente un año de duración. 





Delimitación del proyecto

Proyecto: SSWilliams


Cliente:
Neuropsicólogo Carlos Alberto Serrano Juárez 
Facultad de Estudios Superiores Iztacala
Universidad Autónoma de México
Consultorio: Mar Tirreno No. 111-504
México, Distrito Federal
Horario de atención: lunes y viernes de 16:00 a 20:00 horas	  
Teléfono celular: 55 10 15 72 98


Planteamiento del problema: 

El Neuropsicologo Serrano Juárez, quién está realizando sus estudios para obtener el grado de Doctor, expresó que es de su interés demostrar que a través del uso de las tecnologías de la información se puede mejorar el proceso de atención de pacientes con Síndrome de Williams, describiendo los siguientes problemas:


Las actividades de atención para pacientes con Síndrome de Williams son demasiados caros, por lo que su seguimiento suele ser costoso.

 Las actividades de estimulación así también, son de origen español y americano.

No existen un seguimiento de atención donde se observe el trabajo del paciente en sus respectivos espacios (hogar)




Objetivo general: 

Desarrollar una aplicación web para pacientes con Síndrome de Williams que mejore sus procesos de atención y habilidades visoespaciales, obteniendo información más exacta y confiable.


Objetivos específicos:


Generar un espacio en el internet de información que genere conocimiento sobre el Síndrome de Williams.

Integrar un sistema de administración  a pacientes con Síndrome de Williams que lleve el registro, seguimiento y control de citas, atención y resultados alcanzados.

Implementar las actividades de atención y estimulación para pacientes con el Síndrome de Williams a la aplicación web, , fortaleciendo su proceso de aprendizaje


Usuarios:

Administrador del Sistema

Psicólogos

Personas, en especial niños que tengan Síndrome de Williams.

Padres de familia o tutores


Alcance:

Módulo 1. Registro de usuarios
Registro del administrador responsable del sistema para acceso y control de la información
Registro de psicólogos y pacientes que atiende.
Registro de horarios de atención del psicólogo.


Módulo 2. Citas
Registro de citas por psicólogo
Registro de citas por paciente
Historial de citas por psicólogo y paciente

Módulo 3. Pacientes
Expediente del paciente
Datos personales del paciente
Datos de comunicación con del padre de familia o tutor
Diagnóstico del paciente
Citas solicitadas
Citas realizadas
Citas canceladas
Actividades de atención realizadas por el paciente
Actividades visoespaciales realizadas por el paciente
Resultados obtenidos por periodos

Módulo 4.  Actividades de estimulación
Actividades de atención por tema
Actividades visoespaciales por tema

Módulo 5. Información
¿Qué es el Síndrome de Williams?
Síntomas
Diferencias con otras enfermedades
Información para Padres, tutores y/o profesores

Módulo 6. Contacto
Espacio para registro de personas interesadas
Teléfonos
Correo electrónico


Justificación:

Con el uso de las tecnologías de la información y de la aplicación web, el  Psicólogo y padre o tutor, podrá contar con información oportuna y confiable del seguimiento del paciente con Síndrome de Williams, así como realizar las citas.

El psicólogo tendrá la oportunidad de tener el expediente de su paciente actualizado.

El paciente tendrá acceso a las actividades de atención y visoespacial en sincronía o asincrónica  con el psicólogo.




