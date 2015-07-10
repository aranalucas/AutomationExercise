# AutomationExercise
Automation Tests



Evaluación
Modulo básico de automatización
Versión
2

Para realizar los ejercicios de esta evaluación se recomienda haber visto todos los videos  y haber leído información relacionada a:
Maven
Pages 
Locators
La evaluación deberá ser subida a cualquier sitio de acceso público, o privado pero con permisos de acceso para qe-trainings-automation@globant.com
Una vez subida la evaluación, subir el enlace a la misma al curso, como respuesta a la evaluación del módulo 1, y notificar posteriormente a los correos mencionados.


EJERCICIO 1:
El proyecto deberá constar de 6 casos de prueba en una sola clase y con sus correspondientes assertions (No crear una clase por ejercicio o test). 
El proyecto deberá ser creado con maven y debe tener las siguientes características: 
Estructura de paquetes: nombre_apellido.training.globant.com 
Artifact name: nombre_apellido_mod0_ej1.jar 
Por cualquier duda consultar la documentación de Maven. 
 Los ejercicios deben ser creados usando la siguiente URL:  http://10.28.148.127/wordpress
Caso  1: 
Navegar al sitio. 
Validar que la página sea la esperada en base a su título 
Caso  2:
Realizar una búsqueda 
Validar si hay resultados 
Caso  3:
Validar que la fecha que se muestra para un post en la pagina principal coincida con la fecha al ingresar al post
Caso  4:
Ingresar a 'Contact us' 
Completar cada uno de los campos con valores correctos 
Enviar el formulario 
Validar que se haya enviado correctamente 
Caso  5:
Ingresar a 'Contact us'
Omitir completar uno o varios campos 
Validar que el formulario no fue aceptado 
Corregir y completar cada campo 
Enviar el formulario 
Validar el envío 

Caso  6:
Ir a la página principal 
Utilizando el calendario: 
Verificar cuantos días del mes actual tienen posts 
Ingresar en el primer día que tenga posts 
Contar la cantidad de posts que hay para ese día e imprimir los títulos por consola



EJERCICIO 2:
El proyecto deberá constar de 9 casos de prueba en una sola clase y con sus correspondientes assertions (No crear una clase por ejercicio o test). 
El proyecto deberá ser creado con maven y debe tener las siguientes características: 
Estructura de paquetes: nombre_apellido.training.globant.com 
Artifact name: nombre_apellido_mod0_ej2.jar 
Por cualquier duda consultar la documentación de Maven. 
Los ejercicios deben ser creados usando la siguiente URL: http://www.cheaptickets.com/
Crear otro proyecto para el sitio Cheaptickets.com y realizar los siguientes casos de prueba:
Precondición (Realizar manualmente):
Navegar el sitio: http://www.cheaptickets.com/
Crear una cuenta en el sitio. El nombre del usuario debe incluir la palabra "test". Por ejemplo: blahblah_test@gmail.com
Cada test automatizado deberá tener su Test Case (Documentación). Significa que hay que documentar precisamente cada test automatizado que se desarrolle siguiendo las buenas prácticas para esto mismo.				
Caso 1:				
Logearse en el sistema y verificar que el usuario se encuentra logueado.
Caso 2:				
Logearse con un usuario incorrecto y verificar error.
Caso 3:				
Logearse con un password incorrecta y verificar error.				
Caso 4:
Hacer logout y verificar que el usuario no se encuentra logueado
Caso 5:					
Precondicion: El usuario no esta logueado al sistema				
Buscar un vuelo desde LAS-LAX,1 adulto y fecha a elección. Las fechas deben ser dinámicas. No hardcodear las mismas ya que sino el test no funcionaria a futuro.
Verificar pagina de resultados obtenidos, agregando al menos 5 validaciones.
Ordenar por mayor precio
Elegir el primer resultado de la lista						
Verificar Trips Details , agregando al menos 5 validaciones. Continue
Verificar que la información del vuelo sigue siendo correcta. Continue
Verificar que la información del vuelo sigue siendo correcta. Continue
En Traveler Information agregar información del pasajero. Continue
Caso 6:
Definir y automatizar un test negativo dentro del flujo de búsqueda y reservación de vuelos.				
Caso 7:
Definir y automatizar un test positivo dentro del flujo de búsqueda y reservación de vuelos.
Caso 8:				
Precondición: Búsqueda de vuelos (El usuario esta logueado en el sistema)
Repetir el caso 5 del Ejercicio 2, pero esta vez el usuario se encuentra logueado o debe loguearse en la sección de Traveler Information. Cualquiera de estas dos opciones son válidas.
Caso 9:
Vuelo + Hotel (APH – Air Plus Hotel)				
Buscar un vuelo desde LAS-LAX 1 adulto y fecha a elección. Las fechas deben ser dinámicas. No hardcodear las mismas.
Verificar pagina de resultados obtenidos, agregando al menos 5 validaciones.
Ordenar por reviewer score y por estrellas 5 y 4
Verificar que los resultados obtenidos luego del filtrado coinciden con el filtro seleccionado
Elegir el primer resultado de la lista
Verificar Trips Details, agregando al menos 5 validaciones.
