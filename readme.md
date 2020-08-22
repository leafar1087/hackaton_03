--Respuesta pregunta número 1--

--¿Para qué sirve la validación de formularios?
La validación nos sirve para evitar registrar data en nuestra base de datos que sea mal digitada por los usuarios en los campos de nuestro  formulario, ya sea por su equivocación, ambiguedad, mala edición de nuestro formulario, así como asegurar un nivel de seguridad a nuestra base de datos, ya que se evitaría ataques informáticos como inyecciones SQL.

--¿Cuáles son los problemas al no validar un formulario?
Se pueden presentar diversos problemas, tanto a nivel de seguridad, ya que nuestro formulario estaría expuesto a inyecciones SQL, mediante la cual podrían acceder, alterar o borrar nuestra data, significando pérdidas a nivel ecónomico, de información; así como de parte de nuestros clientes o usuarios, que podrían llegar a desligarse de los servicios prestados por nuestra empresa o negocio, por no garantizar la confidencialidad y seguridad de sus datos.
Por el lado de ingreso de data, afectaria la calidad de datos de nuestra base de datos, teniendo data no esperada. Ejemplo, de manejar un campo denominado número de documento de identidad que solo debe recibir números y máximo OCHO caracteres, sin embargo, al no validar puedo ingresar letras, caracteres especiales de indeterminada longitud o fechas de hechos que puedan ser mayores al día actual.

--¿Cuáles son los beneficios?
Se evitarían inyecciones SQL a nuestra base de datos, así como podemos asegurar que nuestros datos en la base de datos serían de mayor calidad, además que el usuario, se adecuaría a los parámetros requeridos en nuestro formulario, evitando un mal ingreso de información que altere nuestra base de datos