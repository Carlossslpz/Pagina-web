# Pagina-web

Nombre - Carlos 
Apellidos - Lopez Martinez
Curso - 1º Ingenieria informatica
Grupo - B



DESCRIPCION Y PROBLEMAS

Lo primero que hize, fue imaginarme como seria la pagina al final,  despues decidi hacer primero todo el html pero orientandolo ya al css es decir que esten bien definidos los titulos parrafos imagenes tablas... para que el css solo sea enlazarlo y ya:
HTML
Al principio iba a crear la pagina index, pero no tenia claro como queria que fuera su diseño final, por tanto, empeze primero por las subpaginas 


-Contacto

Para este pagina, lo primero que hice, fue copiar el formulario de contacto que hay en los apuntes para ver como quedaba y vi que quedaba chulo pero no me terminaba de convencer pusto que era muy simple y queria poner mas tipos de seleciones checkeo, multiocpion, desarrollo, asi que utilze un codigo de HTML que ya tenia hecho de una pagina que hice para el colegio hece un par de años, por lo que  de ahi saque el codigo de las preguntas que van a partir del correo electronico.
Por ultimo aunque esas respuestas, no se iban a almacenar en ningun sitio, decidi poner un boton que simulara como que esas respuestas habian sido enviadas, para ello, cree una pagina llamada gracias y le puse un texto que decia gracias por el feedback y programe el boton para que cuando se le diera, abriera esa pagina un una nueva pestaña para esto vi en los apuntes como se hacia 


-Fundamentos

Luego segui con la pagina de fundamentos, que es donde se enumeraban los distintos temas, para ello me inspire en la pagina de mi profesor de biologia del colegio, la cual era una pagina en la que habia una matriz de n filas y m columnas en la cual cada elemento , tenia un titulo con el tema y el numero de tema, y una imagen que al pincharla se abria en una nueva pagina con un documento que tenia el tema.

Todo esto se me ocurrio poruqe yo tenia un documento de word con mis apuntes de la asignauta que hice para el examen y ademas vi en los requisitos que habia que hablar sobre un tema de la asignatura asi que aproveche y he puesto todos

Investigue un poco y la matriz se hacia con CSS asi que con HTML solo hice las distintas secciones con titulo una pequeña descripcion del tema y la imagen con hipernvicnulo, aqui tuve un problema, ya que cuando se pinchaban las imagenes, se abria una nueva pagina, se descargaba el documento y se cerraba, pero queria que el documento se pudiera visualizar asi que lo sulucione, subiendo los archivos a One Drive, quitando los permisos de edicion y poniendo el link, y no indicando la ruta de la carpeta local en la se ubicaban como tenia puesto antes y funciono.


-Sobre mi

Al principio no tenia claro que poner aqui, hasta que el profesor dijo que esto iba a estar publico, por tanto pense en algo que fuera sencillo diera informacion, pero no mucha puesto que no quiero que la gente sepa tanto sobre mi, asi que mientas miraba los rrequisitos de la tarea, vi que habia que habia que implementar un curriculum por lo que pense que era una buena opcion, asi que investigue como hacer en HTML una estrucutra de curriculum, para no hacerlo cutre con un h1 y un par de parrafos.

Para la informacion, hay alguna que es real, como la formacion y el nombre pero otros que son inventados por temas de privacidad, luego vi que habia que poner redes sociales y para que se viera mas bonito puese imagenes con links cada imagen era el logo de la red social.

Aqui mas que un problema,me surgio una duda, ya que la tarea, exigia un archivo .cv pero yo habia implementado el CV directamente en la pagina, asi que le pregunte al profesor si esto era correcto y me dijo que si que le valia 

-Tema

Desde el principio el tema lo tenia claro queria que fuera Star Wars porque era mi saga favorita, pero no sabia que estilo darle, puesto que queria que para este trabajo cada pagina tuviera un estilo distinto, asi que un dia buscando ropa para navidades, vi que muchas paginas tenian un carusel para sus productos, lo cual me venia perfecto puesto que yo iba a hablar sobre mis personajes favoritos de la saga y pense que cada personaje iba a ser un elemento de este.

Primero copie el HTML y CSS de una de las paginas pero al intentar editarlo no me enteraba de nada, asi que busque un tutorial de youtube y asi lo saque de manera que entendi lo que hacia y como.El uncio problema aqui, fue al intentar poner las imagenes con links , lo que pasaba es que el contenedor estaba por encima de ellas y no dejaba pincharlas, por tanto me puese a investigar y vi que en CSS definias como la altura de las imagenes, asi que lo cambie y ya funcionaba


-Red 

Para esta pagina sabia que habia que hacer, pero no sabia que estilo darle por lo que solo puse los links de las paginas con sus imagenes y ya pensaria que iba a hacer con CSS.


-Index

Para esta pagina me pasaba lo mismo que con red sabia que queria pero no como.Tenia claro que queria algo sencillo e intuitivo asi que solo puse los enlaces a la pagina como con la red y ya pensaria que iba a hacer


-Menu

La parte mas facil aunque me dio problemas porque al principio puse de etiquetas <ul> y el programa se liaba hasta que me di cuenta que tenia que poner etiquetas <nav>.Otro problema que me dio fue que anque yo ponia target="-blank" las paginas no se abrian en una nueva pestaña por lo que tuve que investigar y encontre que tenia que poner un comando raro.



CSS


Sin duda la parte mas dificil porque de HMTL, sabia algo e incluso como he dicho tenia paginas ya hechas por lo que me fue facil hacer el codigo HTML

Como yo empeze a hacer el CSS antes de que lo vieramos en clase, tuve que ver videos y tutoriales

El problema vino cuando el profesor dijo que tenia que ser solo un documento CSS porque hasta entonces yo tenia 3 documentos CSS para tres de las paginas.

Por lo que lo unifique todo en uno, pero yo al hacer el HTML no habia especificado ni "class" ni "id" por lo que al juntarlo todo fue un descontrol, puesto que ademas como he dicho antes queria que cada pagina tuviera su propio estilo, aunque fuera solo cambiar el fondo y el color del texto  asi que tuve que revisar el codigo entero, poniendo "class"  e "id" para que cada seccion tuviera su estilo y no se solapara con los de otras paginas ademas de poner numerosos <div> porque vi que hacian mas facil la programacion de CSS

Aqui he tenido varios problemas que en realidad era el mismo; en HTML o no puse "class" e "id" o puse el mismo para varias paginas y CSS no hacia lo que queria o ponia  "class" o "id" mal donde no tocaba y CSS no hacia nada

Ademas para el CSS he usado arial porque me gusta y el padding y margin los he ajustado para cada pagina en funcion de como me parecia mas bonito.

-Menu

Fue la primera parte que hice con CSS al principio estuve mirando plantillas de menus para inspirarme pero todos eran como muy complejas y queria hacerlo por mi cuenta, si eso con algun que otro tutorial, asi que opte por un menu simple que como detalle le puse que al pasar el raton por encima de cada seccion cambiaba de color, esto ultimo lo aprendi de un tutorial


-Contacto

Para esto queria un estilo simple por lo que opte por poner todo en el centro para que se viera mas estetico y le puse un fondo color pastel que a mi me parecio bonito 


-Gracias

Aqui opte por poner de fondo un gitf de confetis y en el centro el texto en grande


-Fundamentos

Cuando fui a aplicar el CSS vi que el codigo HTML no estaba del todo bien para que CSS hiciera lo que yo queria asi que tuve que remodelar el HTML y de paso aproveche para poner "class" e "id"

Como me di cuenta que se veia poco intuitivo lo de las fotos, investigue e hice que al pasar el raton por encima, estas crecian y encogian ,ademas puse los titulos en rosa por cambiar los colores.


-Tema

Para esta parte vi un tutorial en youtube, pero para el fondo como era star wars, puse un gitf con fondo de estrellas , luego el carusel tenia de principal la ficha tecnica y la sinospsis, despues cada bloque era un personaje con mi opinion de ellos y una imagen, aunque al volver a ver la normativa, vi que habia que incluir enlaces por tanto cree un nuevo elemento del carrusel y le puse imagenes con links a canales de youtube de Star Wars, pero no funcionabam porque los divs en los que estaban albergados estaban como por encima asi que despues de estar casi 30 mins probando cambios en el CSS y el HTML, di con el comando bueno y por fin lo consegui


-Sobre mi 

Para esta pagina vi numerosas plantillas , pero queria algo que pudiera hacer yo, asi que opte por poner unos rectangulos de una tonalidad mas oscura en cada apartado que me parecio que era algo sutil pero que quedaba estetico y servia para diferenciar, y para las imagenes de mi que habia que poner, las puse en circulos por cambiar un poco


-Inicio

Decidi que queria hacer algo como en fundamentos, intutitivo y minimalista asi que copie el formato, pero para las imagenes le pedi a la IA de Bing que me generara fotos relacionadas con cada uno de los temas, puesto que al pinchar cada foto te lleva a la pagina correspondiente para hacerlo mas intuitivo, hice lo de que al pasar por encima de las fotos estan se reescalaban y puse las esquinas redondeadas por cambiar

Ademas puse unos textos de que hacia cada boton porque sino la pagina me parecia muy sosa y omiti el menu puesto que las imagenes hacian esa funcion


-Red

Aqui no tenia nada claro asi que empeze a poner comandos de CSS a ver cual me gustaba mas hasta que vi unos circulos que me gustaron y de ahi empeze a imaginar, puse una imagen con el link en el centro del circulo la cual al pasar por encima el raton se agranda y al pinchar te lleva las paginas de mis compañeros, la imagen es una generada con la IA de Bing basada en el tema de las paginas de mis compañeros y las dispuse un una matriz para que se vea mas bonito ademas como no queria texto, queria algo mas limpio, busque he hize que los circulos al pasar el raton por encima hagan un sombreado alrededor

Ademas tanto los textos como el sombreado de los circulos los puse en azul puesto que eso con el fondo gris me encanta como combinacion


CONCLUSIONES


En general me ha parecido un trabajo facil, puesto que yo ya tenia algun conocimiento previo como ya he dicho y lo que no sabia lo he buscado en los apuntes o en internet

Por otro lado el CSS se me ha "Complicado" un poco mas pero todos los errores se han reducido a no poner Class o Id para diferenciar elementos y poner etiquetas incorrectas que unicamente afectaban a la estetica y algun otro fallito tonto 

Ademas es muy util este tipo de trabajos ya que aprendemos a solucionar los problemas por nuestra cuenta y a ser autosuficientes, ademas el contenido es algo bastante util puesto que saber HTML y CSS es vital puesto que nunca se sabe si algun dia vas a necesitralo y mas en un mundio tan digitalizado en el cual una buena pagina web es crucial.