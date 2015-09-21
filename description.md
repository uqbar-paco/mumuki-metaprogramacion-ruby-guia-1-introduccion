Lejos de lo que muchas veces se piensa (e incluso a veces nosotros mismos pensamos), _programar_ no trata de escribir código, sino de construir **conocimiento ejecutable**: desarrollamos modelos computables que permiten resolvernos problemas. Así, cuando programamos estamos razonando y diseñando sobre un modelo de dominio: sus elementos, sus relaciones, sus responsabilidades. Sí, a este conocimiento ejecutable compuesto por estos elementos es lo que llamamos programa. 

¿Y cuando estamos _metaprogramando_? Simple: pasamos a razonar y diseñar sobre modelos ... ¡acerca de los modelos! Por ejemplo, si programamos con objetos, nuestros elementos del modelo serán, por ejemplo, sueldos, empleados, canchas de fútbol, dioses griegos, colores, noticias. Pero cuando metrapogramamos nuestros elementos del modelo serás los objetos, las clases, los mensajes, la herencia, la instanciación, los parámetros. Nada en realidad cambió sobre nuestro concepto de programación, sólo que ahora traremos con ideas más abstractas. Y por lo tanto **nuestros programas resolverán problemas más generales**.  

¿Y para que nos puede servir esto? ¡Para hacernos más fácil la vida! :smile: En nuestro dia a día construyendo modelos de dominio, decenas de veces nos encontramos con ideas repetidas: hacer un observer o un builder siempre es parecido, implementar el `equals` y `hashcode` es tedioso, serializar un objeto en formato JSON es una tarea mecánica y propensa a errores. Entonces, ¿no podría hacerlo otro? ¿Quizás nosotros mismos, con otro sombrero, pero una única vez? 

Sí, podríamos. No importa cuan pequeño o grande sea el problema, si hay lógica repetida, tenemos que evitarla, aunque nuestro lenguaje y paradigma no nos de ninguna respuesta rápida al problema. Incluso así es como surgen los _frameworks_ y bibliotecas genéricas: un test-runner como SUnit, un ORM como Hibernate, una herramienta para desarrollar aplicaciones Web como Rails: en todas estas tecnologías, la metaprogramación es clave.

Moralejas: 

 1. la metaprogramaión no es algo que ocupará todo nuestro tiempo, pero nos dará mucho poder. 
 2. para poder metaprogramar, ¡tenemos que saber programar!
 3. Si vamos a trabajar sobre el modelo de todos los modelos (el meta-modelo), tenemos que tenerlo claro. 

Por eso, en esta primera guia, empezaremos por hacer un breve repaso del lenguaje Ruby, el paradigma de objetos. Y daremos nuestros primeros pasos sobre mepatraprogramación. Para más información, [ver acá](http://uqbar-wiki.org/index.php?title=Metaprogramaci%C3%B3n). ¡Acompañanos!

