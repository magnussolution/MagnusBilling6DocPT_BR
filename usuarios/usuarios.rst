Agregar nuevas cuentas de usuarios a MBilling

Nos dirigimos al Menú Usuarios >> Usuarios >> Nuevo. Encontramos los campos:

- Usuario: Ingresamos el nombre de usuario (Podemos seleccionar para que MBilling genere este dato de manera automática, desde el Menú Configuraciones >> Configuraciones >> Username auto generate, como así también podemos elegir que se coloque un prefijo y la cantidad de caracteres que lo compongan). Es recomendable colocar un nombre de usuario formado por números y no por letras.

- Contraseña: La clave siempre se genera de manera automática, pero puede ser modificada posteriormente por el Administrador, o inclusive por el usuario, si este tiene los permisos correspondientes.

- Grupo: Este campo indica a que grupo va a pertenecer el usuario. Por defecto MBilling tiene 3 grupos: Administrador, Agente y Cliente; pero se pueden crear y generar nuevos. Cada uno con los permisos deseados. Es recomendable no modificar los grupos que trae MBilling por defecto. Es mejor crear nuevos grupos y dejar estos como respaldo en caso de tener problemas con los creados.

- Grupo para clientes del Agente: En caso de que se seleccione el Grupo Agente, en este campo se podrá elegir a que grupo van a pertenecer los usuario creados por dicho agente.

- Idioma: Se debe seleccionar el idioma del usuario.

- Plan: Este campo indica a que Plan va a pertenecer este usuario, por lo tanto cuales serán los valores que va a pagar por las llamadas, ya que cada plan, tiene una tarifa asignada.

- DDD: En este campo podremos generar un plan de marcado específico para cada usuario. El formato es el siguiente:

Ejemplo de plan de marcado: 15/54911/10,0342/54342/11

Las reglas deben estar separadas por coma (,) y están compuestas por tres términos separados por "/". El primer termino indica el número a reconocer y reemplazar, el segundo por cual debe ser reemplazado, el tercero cual es la longitud del número. 

Ejemplo 1: 15/54911/10. Número que comienza con 15 y tenga una longitud de 10 dígitos, se debe cambiar el 15 por el 54911. Número 1561333612 >> comienza con 15 y tiene 10 dígitos = 5491161333612

Ejemplo 2: 0342/54342/11. Número que comienza con 0342 y tenga una longitud de 11 dígitos, reemplazar el 0342 por el 54342. Número 03424742900 >> Comienza con 0342 y tiene 11 dígitos = 543424742900


- Activo: Activamos o desactivamos este usuario, si se encuentra desactivado, no va poder ingresar al sistema.

- Paquetes gratis: Este campo indica si el usuario tiene activado algún paquete promocional.



Pestaña datos personales: Se podrá agregar información detallada del usuario.



Pestaña Adicional

- Tipo de pago: Prepago o postpago.

- Límite de crédito: En caso de seleccionar postpago, se podrá seleccionar el límite de crédito con el cual el usuario podrá realizar llamadas.

- Activar vencimiento: Para activar el vencimiento del crédito.

- Vence: Indicar la fecha de caducidad. 

- Aviso de saldo bajo: Envía alertas por correo al usuario.

- Callshop: Activar el módulo callshop para este usuario.

- Grabar llamadas: Grabar las llamadas de este usuario.

- PIN Callingcard: PIN para que el usuario pueda acceder al callingcard (se genera de manera aleatoria, pero se puede modificar).

- Restricción: Que tipo de restricción de llamada tendrá el usuario. (Leer documentación: Usuarios >> Números restringidos).
