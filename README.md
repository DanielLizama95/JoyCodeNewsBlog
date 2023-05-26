Saludos, 
Me siento orgulloso de presentar JoyCode News, un blog sobre desarrollo de videojuegos, y también mi primer proyecto de escala considerable para poner en un portafolio de frontend.
A continuación, repasaré cada sección del blog para comentar los detalles que podrían ser más interesantes.

<h2>1. Navbar </h2> 

![navbar](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/0933fa38-bfa3-4123-884e-b64799ce5723)

<p>La navbar decidí mantenerla simple. Un color sólido de fondo, un logo, y una lista desordenada con 4 elementos.
   Pero tiene una funcionalidad curiosa, y es que cada li tiene un span con íconos de Fontawesome que se animan con Javascript</p>

![ezgif-3-9786d9e53b](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/ef9afad3-61df-4818-a050-c5fc89b97074)

<h2>2. El main</h2>

   ![main](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/d9d6e51a-382a-4a5d-9532-2ee12b778ad1)
   
   <p>El main contiene las 8 noticias más recientes como se puede ver en mi código. Y la hice con grid</p>
   
   ![codigomain](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/d683821b-2c76-4a16-a690-0b109987277c)
   
   En este caso, coincide que las más recientes son las que menor ID tienen en mi array de datos para las noticias:
   
   ![thumbnaildata](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/18ec24d8-25f6-47ca-af17-8fa49a89a064)
   
   Pero esto puede fácilmente cambiarse retocando el bucle for.
   
<h2>3. Sección de todas las noticias</h2>

![newszone](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/06ccb468-7ae7-4997-bde4-5a1a3e260969)
   
   <p>En esta zona decidí usar Flexbox porque quería variar el diseño respecto al de la página principal, pero me costó bastante.
   Y de hecho la vista móvil no me gusta nada, pero trabajaré en corregirla en un futuro.
   En esta sección se muestran las 16 noticias más recientes, si fueran más, se mostrarían en una siguiente página.
   En la parte superior derecha como podrán notar, hay un botón que filtra las noticias por categoría.</p>
   
   ![ezgif-3-6c2818e734](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/c02298d2-44f8-43c4-a452-452387b4ff7e)
   
   Esta es una de mis features favoritas porque por esta funcionalidad pasé de no entender bien los métodos de ES6 y las funciones flecha,
   a dominarlas decentemente.
   
<h2>4. Footer</h2>
 
   ![ezgif-3-a380329616](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/7ef5df6d-34a4-4606-a28c-4e78173eb1a8)
    <p>Nada especial con el footer tampoco, pero tiene una curiosidad. Y es que si pasas el mouse por el corazón, se anima, y deja de 
    hacerlo cuando haces mouseleave.</p>

<h2>5. Artículos</h2>

   ![articlemobile](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/eb08ed90-ffed-4d29-b06a-9d8bb09f3cae)

   Los artículos son la sección más compleja del sitio, aunque no lo parezca. (Personalmente me gusta más la vista móvil).
   Constan de un título, una imagen, el nombre del editor, la categoría de la noticia, la fecha, y el tiempo de lectura obtenido
   a partir del número de palabras que tiene el artículo.
   
  ![code](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/fd37b75d-c0c7-4536-8a4d-c34145d7a200)

   ¿Cómo? Simplemente tomando la cantidad de palabras que tiene el artículo y dividiéndolas entre 200, que son las palabras que 
   cualquier persona promedio puede leer por minuto. Todo esto encapsulado en un Math.Ceil() para que el número resultante se
   redondee hacia arriba.
   
   Y finalmente tenemos la sección de contenido relacionado, y comentarios.
   
   ![comments](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/d812678a-9be7-4451-8687-ee093e69f0b1)

   No, les miento, quería hacer más en esta sección. Mi idea original era hacer que puedas agregar un comentario, pero estaba
   fuera de mis límites por cuestión de tiempo. Al igual que agregar comentarios que no sean Lorem Ipsum. 
   Al menos los nombres, la noticia relacionada y las fotos sí son aleatorias. En el caso de las fotos y nombres, las obtuve 
   mediante la API de Randomuser, aunque por si acaso, guardé todo en una variable para no depender de la API (tiene usos limitados).


<h2>6. Trivia</h2>

![Trivia](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/8f863e48-5889-425d-8199-5eb81fde4e6b)

El juego de trivia fue mucho más sencillo de lo que pensé, me tomó dos días hacerlo nada más. Probablemente porque ya antes había
visto tutoriales de sliders, y juegos de memorama. Más tardé en decidir el tema y las preguntas de la trivia, que programando la 
trivia en sí. También pasé mucho rato probando estilos diferentes.

![ezgif-1-8ebc59802a](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/dc61fbc7-4835-4ba3-a06f-4b9497f22f6e)

Hasta que finalmente me decidí por este.

![trivia2](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/249f0c24-5d0a-40fc-a8b8-332dcb1b8bbe)

Simple y más que funcional.

![ezgif-1-e07ab62c4e](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/f4d8c061-ac67-440d-a542-443fe46094b7)

Un amigo se ofreció a hacer tanto el logo como un par de animaciones. Esta es cuando ganas.

![ezgif-1-1d44cb2f38](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/39bd5f7d-0797-4101-a45e-34d8bec83a6c)

Y esta cuando pierdes.

Por supuesto, el código es reutilizable si le hacemos modificaciones para tomar uno u otro array de preguntas. pero dada mi experiencia
haciendo muchos artículos distintos, no quise arriesgarme a hacer varias trivias, porque intuía que el tiempo no me iba a alcanzar.

<h2>7. Sección de contacto</h2>

  ![contact](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/082e6277-86f6-4956-a01f-cc7d72ec16c0)

<p>La sección de contacto como podrán notar tiene un main mucho más estrecho que otras páginas de la web. Eso es porque no había comparación,
en móvil se veía mil veces mejor. No es tanto texto y por eso en escritorio se veía raro.</p>

![contactform](https://github.com/DanielLizama95/JoyCodeNewsBlog/assets/133599190/c81da05a-0d02-41c4-8bb9-2c81ad487ee5)

En lo que respecta al formulario, usé Formspree y la validación required que aprendí en la clase 8 del Bootcamp. Y la navbar tiene un
enlace a mi Github.

<h2>Conclusión</h2>

Me siento muy contento y satisfecho por todo lo que aprendí practicando todo lo visto en el Bootcamp y en tutoriales de Youtube.
Por supuesto que cometí errores, fui aprendiendo cosas sobre la marcha. Mi código no es el mismo al principio que al final, por ejemplo.
Pero al menos sé que a la próxima ya estaré más preparado. Estoy emocionado por empezar otro proyecto. Atentos a mi Github ;)
