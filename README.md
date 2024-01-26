Aquí va la documentación de la página
La pagina cuenta con una estructura HTML repartida de la siguiente forma
Dentro de la etiqueta HEAD se encuentra el link de bootstrap v5.3, link al archivo style.css
En el header encontramos al navbar y al carousel.
En la seccion MAIN encontramos a la seccion "¿Quiénes Somos?" y seccion "Destacados".
Posteriormente la sección "Contacto" que contiene el formulario con un boton enviar que muestra una ventana modal.
Y al final el footer donde se encuentra un texto con el nombre de la web "Viajes Chile" y los iconos de las redes sociales con tooltips invidiales.

Para este proyecto se utilizaron varios componentes de bootstrap v5.3
Navbar (Header)
Carousel (Header)
Card (Sección destacados)
Formulario (Seccin contacto)
Ventana Modal (Boton Enviar)
Tooltips (Iconos RRSS)

En vista SM el navbar se comprime y las opciones pasan a verse en un boton desplegable. Se aplico la propiedad fixed al navbar para dejarlo fijo en el TOP. También se le añadio saltos de pagina al apretar en las opciones por medio de bootstrap.
El carousel cuenta con boton "anterior" y "siguiente" muestra 3 imagenes.
Para la sección "¿Quiénes somos?" se aplico la clase bootstrap "d-none" para hacer que la sección desaparezca por debajo de los 992px.
A los card de la "sección destacados" se les aplico un height definido a sus imagenes para alinearlas y se hizo uso de clase bootstrap "row" y "col" para adaptarlo a la vista.
El formulario fue sacado como componente de bootstrap, se duplico el primer label y se cambio el nombre y se añadio una ventana modal al boton enviar.
El botón enviar cuenta con una ventana emergente que aparece en el centro de la pantalla al pulsar "Enviar".
Por último en el footer se implemento un salto de sección al inicio de la página al apretar en el texto "Viajes Chile" y al pasar el cursor encima de los iconos de Redes Sociales aparece un tooltip con su respectivo nombre, ademas los link se abren en pestañas adicionales.
