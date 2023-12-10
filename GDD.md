# LULLABY
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Logos/LullabyLogoCircle.png" width = "auto" height = "150">
</p>

## 1. VERSIÓN
Version 1.1. Determinar las primeros capítulos del GDD y empezar a completarlos

Versión 1.2. Cambiar capitulos posterior al dos y completar 

Version 1.3: Completar apartados secundarios 

Version 1.3.1: Añadir apartado de guión y storyboard

Version 1.3.2: Añadir apartado de arte 2D y 3D con concept art y vfx, iluminación y postproceso respectivamente

Version 1.4. Añadir imágenes de los apartado 

Versión 2.1: Cambiar imágenes 

Versión 2.1.1: Cambiar imágenes de controles

Versión 2.1.2: añadir arte final de las interfaces

Versión 2.2: Completar el apartado de elementos de nivel

Versiión 2.3.1: Añadir las imágenes del apartado de 2D

Versiión 2.4: Añadir la seccion de ruta de niveles

Versiión 2.4.1: Añadir la seccion de ruta de niveles y completar el nivel 1 con imágenes

Versiión 2.4.2: Añadir la seccion de ruta de niveles y completar el nivel 2 con imágenes

Versioón 2.4.3. Añadir y completar apartados de arte 3D con animaciones y modelos 

Versioón 2.4.4. Maquetar modelo de negocio

Versioón 2.5: Ficha de niveles

Versioón 2.5.1. Añadir secciones y completarlas

Versioón 2.5.2: Incluir imágenes

## 2. INTRODUCCIÓN
El presente Game Desing Document (GDD) proporciona una visión integral de “Lullaby”. A lo largo del documento se van a ir desarrollando y explorando los detalles conceptuales que atañan al desarrollo, las características que lo definen. 
Se especificará el propósito y el aspecto visual que define la inmersión del videojuego.  

### Concepto general 
*Lullaby* es un videojuego de plataformas 3D que se desarrolla en “Alora”, el mundo de los sueños, donde los jugadores deben conseguir la nana perdida para seguir con sueño y mantenerse en este reino.  

Conforme se va avanzando en el juego, la historia lo hace en paralelo para que la narrativa para enriquecer la experiencia del jugador. 
Asimismo, el avance la historia nos irá acompañando incluso cuando el personaje ha muerto, es decir, tendremos puntos de control alojados a lo largo del juego para mantener activos cada cambio sucedido con anterioridad.  

### Público general
Es un juego orientado a un público joven de entre 12 y 25 años. Está enfocado de esta forma para aquellos que disfruten de los juegos de plataformas, combate y aventura. 
El límite se fija de acuerdo a las normas PEGI en 7 por dos motivos fundamentales:
- *Lullaby* cuenta con monstruos de aspecto animal y no humanoide que pueden asustar a los más pequeños.
- El juego añade un sistema de combate semi-realista, por lo que para tratar de evitar comportamientos violentos en la vida real se busca una edad en la que sepan diferenciar realidad y ficción. 
El usuario no necesita contar con habilidades específicas o haber jugado a otros juegos similares para poder jugar a este. En el propio juego se aprenden las habilidades motoras y mentales necesarias para completarlo.
El jugador tendrá que hacer uso de sus habilidades aprovechando las mecánicas que brinda el juego como salto, doble salto, airdash, lucha con enemigos y mucho más, mientras presencia una emotiva historia que le dejará marcado.  

### Próposito de juego 
El objetivo principal de este juego es entretener al jugador y ofrecerle un juego que reta sus habilidades motoras y psicológicas adquiridas con los videojuegos. 
Como objetivo secundario el juego puede ser utilizado para enseñar algunas partes del pensamiento computacional a todos los jugadores, pero en especial a los niños. Para ello hay una serie de métricas que podrán ser monitorizadas por padres, profesores, psicólogos y otros profesionales relacionados con los infantes mientras los niños juegan. 
#### Métricas de pensamiento computacional 
A continuación, se detallan las métricas que se van a poder monitorizar externamente al juego y en qué parte del juego se encuentran los elementos que enseñan cada sección del pensamiento computacional. 
- Abstracción
- Descomposición
- Generalización
#### Abstracción 
Centrándose sobre todo en el reconocimiento de los elementos clave de un problema y el reconocimiento de patrones.  
Estas destrezas se podrán medir principalmente en el combate contra el jefe final. En este combate el jefe final realizará 3 patrones de comportamiento en las diferentes fases del combate. 

En la fase 1 el jefe se dividirá en 4 copias de sí mismo en un cierto orden, cada copia será de un color diferente por lo que se podrán distinguir entre sí. Estas copias deben ser golpeadas en el orden que se han dividido ya que, de no hacerlo, provocará daño al personaje. El jugador debe reconocer este patrón y llegar a la conclusión de que debe golpearlos en orden.  

En la fase 2 el patrón de comportamiento cambia y el jefe final se aleja a una zona sin suelo.  La imposibilidad de que el jugador lo golpee físicamente hará que se abra una nueva forma de ataque a distancia. El villano lanzará bolas de energía que el jugador debe golpear (posiblemente en un orden) para conseguir hacerle daño. De esta manera el elemento clave será reconocer el orden y devolverlas ante el impedimento de no poder luchar cuerpo a cuerpo. 

Además, los enemigos siguen patrones de movimiento que permiten al jugador identificar rutas, lo que facilita la opción de evitarlos o tomarlos por sorpresa.  
La métrica principal que se utilizará para medir estas destrezas es el tiempo que pasa desde que se le plantea el problema al jugador hasta que detecta los elementos clave y reconoce el patrón para llegar a la solución. 
Una métrica adicional que se podrá emplear es el número de veces que el jugador es derrotado antes de identificar el patrón y los elementos clave del problema. 
#### Generalización 
Para esta métrica nos hemos centrado sobre todo en resolver problemas basándose en soluciones anteriores y en la identificación de conexiones, similitudes e inducción.  

A lo largo del juego se presentan diferentes puzles que requieren el uso de mecánicas iya introducidas previamente en el juego, como presionar botones, saltar, realizar un air dash o utilizar la mecánica de salto en la pared. La primera vez que el jugador deba realizar una de estas mecánicas, se le mostrará una ilustración en ciertos carteles ubicados en el mundo, explicándole cómo debe realizar la acción. 
A medida que se avance en el juego, estas mecánicas seguirán siendo necesarias para la progresión, pero ya no se le indicará al jugador. En su lugar, deberá deducir por sí mismo la necesidad de estas a lo largo del juego reforzando de esta manera el pensamiento computacional. 

La métrica principal para evaluar estas habilidades será el tiempo que el jugador requiere para abordar una situación familiar y resolverla utilizando las mecánicas o recursos ya aprendidos.
Además, con ello también se mide el tiempo que necesita el jugador para identificar dentro de los problemas nuevos similitudes ya aprendidas, aunque la estructura sea distinta. Esto implica adaptar los conocimientos a la nueva situación del juego. 
#### Descomposición 
En esta métrica se focaliza en la descomposición de problemas en otros más pequeños.  
Esta habilidad se puede medir en los distintos puzles que se plantean a lo largo del mundo. En cada uno de ellos, el jugador deberá identificar los recursos que puede emplear para resolver problemas pequeños que, en última instancia, conducen a una solución más grande 

La métrica principal que se utilizará para medir estas destrezas es el tiempo que transcurre desde que se le plantea el problema al jugador hasta que detecta los elementos clave y aborda las tareas por separado hasta alcanzar la solución final.  
Otra alternativa es el tiempo que le toma resolver cada pequeño problema desde que se le ha planteado el problema global. 

### Plataformas
Lullaby estará disponible para WebGL siendo posible jugarlo desde pc con mando o teclado y ratón y desde móvil con controles táctiles.  

### Sinopsis
Lulla es una pequeña oveja que se aventura por los enigmáticos rincones de El Reino de los Sueños, dominado por el poderoso dios del sueño Morfeo. La misión de Lulla: recuperar la nana mágica que le permitirá continuar en ese mundo de sueños.  

Mientras esta inocente protagonista va superando los entresijos del plano onírico, Morfeo no está dispuesto a que su estancia allí perdure mucho. La regla principal es que nadie puede quedarse.  

A pesar de la firmeza de Morfeo, Lulla se encamina en una desafiante búsqueda y en una batalla contra las temibles pesadillas mandadas por el dios de los sueños.  

La lucha por mantéese dormida y permanecer en ese mundo, se convierte en un desafío extraordinario por alcanzar su objetivo donde Lulla refleja la valentía y el autodescubrimiento. 

### Género 
Se trata de un juego de plataforma acción-aventura. Al ser un género hibrido los dos que abarca se combinan entre sí. 
Por ser un videojuego de plataformas, la mecánica principal consiste en mover al personaje a través de los escenarios o niveles llenos de superficies y desniveles, haciendo uso de las habilidades de salto y dash, y las mecánicas derivadas de estas, como doble salto, escalar por paredes, agarrarse de cornisas, etc. 
Asimismo, se complementa con el género de acción-aventura al añadir elementos de combate y enemigos que derrotar para poder avanzar, así como una narrativa que acompaña al jugador a medida que resuelve puzles y rompecabezas, habla con personajes y descubre secretos del mundo de fantasía en el que se desarrolla todo. 

### Estilo visual 
#### Personajes y escenarios 
El estilo visual se ha enfocar en un videojuego en 3D en específico low poly o de baja poligonización. La razón de esto es que el juego tiene que estar disponible para WebGL y debe poder jugarse en multitud de dispositivos, tanto ordenadores como móviles.
Como herramienta se ha utilizado Miro para crear un tablero en el que adjuntar referencias de escenarios y personajes con el fin de encontrar una estética adecuada al tipo de juego, la narrativa, el público objetivo y el propósito del juego. Además, se ha añadido un apartado donde el equipo de diseño puede subir sus bocetos y proponer posibles combinaciones de estos para crear los modelos 3D. 

Los personajes siguen una estética cartoon, siendo entrañables y adorables, pero sin llegar a ser infantiles. 

Los escenarios tienen una geometría simple y una estética sencilla, pero a la vez encantadora.  Aunque se ha preferido no recargar la escena de objetos, cada elemento colocado tiene un significado narrativo dentro del diseño del nivel. 
Los elementos del entorno son objetos cotidianos, pero se usan de una forma fuera de lo común. Así encontramos ejemplos como piruletas que actúan a modo de árboles. La razón detrás de esta decisión de diseño es que el juego está ambientado en un mundo de fantasía como es el Reino de los Sueños, por lo que se cuenta con mucha libertad artística y un rango de estilos visuales muy amplio.  

Además, al tratarse de un mundo de irreal, el equipo de arte y diseño puede experimentar entre las cosas mundanas para distrsionarlas y colocarlas dentro de este mundo onírico. La posibilidad de lo imposible ha hecho que los artistas pudieran recrearse en la inherencia y lo irracional para cohesionar una historia fantástica. 

El hilo conductor de la fantasia tomada como protagonista en el desarrollo de la narrativa ha hecho que se unifiquen la realidad y la creatividad. 
#### Paleta de color 
La paleta de colores está asociada a lo que comúnmente se relaciona con la magia y lo onírico, por lo que, por lo que, para mostrar persistencia, la mayor parte del peso lo conforman los colores morados y violetas. Con ello se pretende crear una atmósfera etérea conjugándolo con una iluminación mágica que trasporte al jugador. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/GeneralColorPalette.png" width = "auto" height = "250">
</p>

- Olivine (AFC485). Un color verde claro, ligeramente desaturado, que se utiliza en los elementos del entorno para aportar frescura en la paleta y romper la monocromía de los morados. Se utiliza sobre todo para mantener vigente el mundo real y que no se sienta tan desligado a lo que los jugadores conocen. 
- Powder Blue (9BB7D7). Un color azul claro pastel, de nuevo desaturado,que se encuentra en armonía con los tonos morados y verde y sirve de puente entre estos. Se utiliza en elementos del entorno para romper de nuevo la monocromía.
- Thistle (CEBACF). Es el color más claro de la paleta. Es usado para elementos que necesitan enfatizar sutilmente sobre el resto, pero sin llamar demasiado la atención del usuario. Es el color predominante en el personaje jugable ya que es el color de la lana, representando la inocencia de Lulla. A su vez con ello conseguimos destacarla por encima del resto de elementos del escenario
- Pomp and Power (8D5A97). Es el color predominante de la paleta, se encontrará en la mayor parte de los elementos del mundo dando ese toque de fantasía y magia
- Dark Purple (1F0318). El color más oscuro de la paleta es una antítesis del color del personaje principal que se utilizará para las zonas oscuras y las sombras
- Bittersweet (EE6352). Un tono rojizo que denota peligro utilizado en enemigos y en elementos que deben llamar la atención del jugador. Se contrapone a los verdes, azules y morados de la paleta, haciendo que resalte.
- Naples Yellow (F5D267). Color complementario de los morados que se usará de nuevo como indicador de peligro y de elementos en los que el usuario debe focalizar su atención.

Esta paleta de colores es la principal del juego. En cada nivel o zona del juego predominarán más unos colores u otros, además de no tener que utilizar los colores exactos de la paleta. Para ello se proporciona una herramienta que permite crear degradados entre los colores de la paleta para crear nuevos tonos que usar. 

A continuación, se muestran algunos ejemplos de paletas degradadas entre dos colores principales de la paleta.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/GradientColorPalette.png" width = "auto" height = "250">
</p>

#### Isotipo y logotipo
El isotipo del juego está inspirado en el imaginario social que existe alrededor de la idea de dormir y de soñar. Es por ello que todos los elementos que se han incorporado a él están relacionados con ello. 
La razón detrás de estos temas elegidos para el isotipo es representar qué está haciendo Lulla en el mundo real mientras explora el Reino de los Sueños
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Logos/LullabyLogoCircle.png" width = "auto" height = "150">
</p>
- Luna. Un icono estrechamente relacionado con la noche siempre ha sido el uso de la luna, en especial la creciente y la menguante. De la misma forma, este símbolo también se asocia a la acción de dormir y de soñar. La forma de la luna a su vez recuerda a una cuna o un nido, que es donde duermen los infantes y las crías de algunos animales.
- Móvil de estrellas. Los móviles que se colocan en las cunas de los bebés y los niños se usan, entre otras cosas, para que se relajen y duerman tranquilamente. Es por ello que se ha aprovechado la forma de las estrellas, muy relacionadas con la noche, como el objeto que cuelga en este móvil. Además, se aprovecha así la forma de la luna para hacer que cuelguen las estrellas de ahí.
- Manta. Para simular a la protagonista del juego dormida se utiliza una manta colgando de la luna, consiguiendo transmitir que Lulla se encuentra soñando.
- Cielo estrellado. De forma general, los sueños y la acción de dormir se relacionan con un cielo nocturno, muchas veces lleno de estrellas.
- Colores. Utilizando la paleta de color del juego y algunas paletas de degradados se han relacionado los colores “oníricos” y “de fantasía” que se usan en el juego con los colores para “dormir” y de “tranquilidad”. Además, se mantiene una relación entre los colores con el parecido a la realidad, la luna de un color más claro y el cielo que simula la noche de un color más oscuro.

El logotipo, por su parte, utiliza como base una tipografía de uso libre y 100% gratuita llamada “Spicy Chips” y está formado por la palabra “Lullaby”, que es el título del juego. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Logos/LullabyTittle.png" width = "auto" height = "125">
</p>

El logotipo cuenta con una modificación en la letra “b” simulando ser una corchea musical. Para que este elemento siga actuado como una letra ”b”, la corchea se ha volteado horizontalmente, a pesar de que no existe una nota musical válida en esa dirección. 
Esta decisión de diseño se ha tomado porque la música tiene un sentido narrativo y relaciona el título del juego, cuya traducción al español es nana o canción de cuna, con la parte musical y con el objetivo que tiene la protagonista dentro del juego.

Se mantiene una relación de colores entre el isotipo y el logotipo para que se pueden usar junto comjo imagotipo o separado indistintamente. 
#### Interfaces y pantallas
Las interfaces y las distintas pantallas también siguen la paleta de colores que se ha presentado. Sin embargo, en las pantallas e interfaces se usa el 2D para los distintos elementos como botones, indicadores, cuadros de diálogo, etc. 
De la misma forma, las interfaces no se centran tanto en simular un mundo fantástico, sino en utilizan elementos relacionados con la trama y el tema general de dormir y soñar, como son la luna, las estrellas o el día y la noche. 

## 3. NARRATIVA
### Mundo
El mundo donde se ambienta el juego es el Mundo de los Sueños, y tiene características que lo definen como tal. Es un mundo abierto, con elementos del mundo real llevados al extremo. Se ambienta en un mundo de plataformas en 3D, que con esa curiosidad innata de disfrutar y explorar se embarca en una aventura por su cuenta. El mundo de los sueños es particular para cada individuo, todos pueden acceder a él al soñar, pero este es el de Lulla, con todos sus sueños y pesadillas.  
El mundo de los sueños está gobernado por Morfeo, cuya labor es tratar de mantener la armonía en él creando sueños y pesadillas y asumiendo diferentes formas según se requiera para preservar el equilibrio del mundo en el que es el guardián.  
Aspectos que lo harán reconocible:  
- Plataformas: Es un mundo que juega con los sueños y pesadillas de Lula. En primera instancia será amigable con elementos que Lula tiene asociados al bien, a su comodidad, como por ejemplo árboles enormes con apariencia de seta y largos prados con montañas, donde solía ir con su madre. Por otro lado, esto también puede trabajar en su contra, ya que juega con las alturas y con las situaciones de riesgo, reflejando inteligentemente el sentimiento de Lulla de estar constantemente al límite, al borde de caer. Además, representa la clásica de soñar con una caída.  
- Hipérbole del mundo real: Se exageran elementos del mundo real, para hacerlo reconocible, tal como los pinchos del mundo, que simulan el aguijón de las abejas. Algunos de los componentes que componen el mundo son las setas gigantes que serán plataformas, o como las amapolas que irán apareciendo en el mundo, las cuales indican que la barra de sueño (vida del personaje in-game) se recargue. Se ha elegido la amapola porque es la planta de donde derivan tanto la morfina como el opio, y es una forma de añadir un toque más adulto para aquellos que sepan este dato.
- Evolución: El mundo es dinámico, y aunque no se modifican los elementos más reconocibles para el jugador, se busca crear una atmósfera distinta en el final del juego para transmitir la ira de Morfeo por la prolongada estancia de Lulla en el reino. El cambio del entorno entre los niveles se quiere hacer paulatina para que no sea abrupto y el jugador pierda inmersión en el juego, sino que la transformación vaya acompañándole a lo largo del juego.
  
### Personajes
#### Lulla
Lulla, la protagonista del juego es una pequeña y tierna oveja de 11 años (Se está tomando la edad humana ya que en realidad la expectativa de vida media de una oveja son 12. Se hace para mantener una referencia a la edad humana que resulte familiar y evitar confundir a la gente que no tiene conocimiento sobre este dato. Además, omitimos la explicación, ya que carece de relevancia en el contexto de la narrativa y la jugabilidad). 

Lulla es el centro de la trama del juego. Se trata de una protagonista caracterizada por su inocencia, su determinación y la tristeza que la mueve a querer soñar permanecer en ese mundo de fantasía. 
Nació en el seno de una familia feliz, y como primera y única hija llenó la vida de sus padres de alegría. Su hogar, una granja en el recóndito pueblo de Lanuza, Huesca, es una humilde construcción familiar que la ha visto crecer. Allí, Lulla se ha criado con todo el amor y el cariño de sus padres, que siempre se han esforzado por darle lo mejor.

Los días pasaron, las estaciones cambiaron y la ovejita que apenas si sabía salir de casa sin su madre pronto comenzó a ir a la guardería. Poco después empezó a hacer sus primeros amigos, a los que invitaba a jugar con ella en la granja. Aprendió a leer, a escribir, incluso a cantar, y pronto se dio cuenta de cuántas cosas maravillosas había en el mundo. A hora de dormir, siempre preguntaba a su madre sobre sitios lejanos, más allá de la granja y el pueblo, verdaderamente emocionada. 

La madre le respondía hasta que Lulla se cansaba de hablar, y después le cantaba la suave nana que había sido la favorita de su hija desde que no era más que un corderito. La pequeña cerraba entonces los ojos, cansada, y se dejaba llevar por la cálida voz de su madre a todas aquellas tierras fantásticas que después volverían a aparecer en sus sueños. 

Así transcurría la vida para Lulla hasta sus 10 años, cuando una tarde de otoño más fría de lo habitual su madre cayó enferma. Pasaba los días encerrada en su habitación, sin poder levantarse de la cama por los intensos dolores y mareos. Muchas veces deliraba por la fiebre, y a veces pasaban días seguidos sin que comiera nada. Aún con todo esto, Lulla se escabullía por las noches a la cama de su madre, donde esta le volvía a cantar, con una voz cada vez más débil y lejana, hasta que la pequeña se quedaba dormida.  

Desde una perspectiva narrativa más técnica, Lulla es el núcleo de la trama del juego. Se trata de una protagonista caracterizada por su inocencia, su determinación, y la tristeza que la mueve a querer recorrer el mundo de los sueños. 
- Inocencia: se trata de una niña inocente, nacida y criada con el amor de una madre cariñosa y una vida apacible. El diseño de Lulla busca transmitir una apariencia inocente, tierna y amable, utilizando formas circulares en su cuerpo, ojos grandes y colores claros, así como unas animaciones de caminar, saltar y atacar risueñas y despreocupadas.
- Determinación. A pesar de ser una niña y tener una apariencia tierna, Lulla lucha contra sus pesadillas, avanzando sin detenerse en su objetivo.
- Tristeza. El aspecto fundamental que mueve la narrativa es realmente el duelo de Lulla por la pérdida de su madre. La tristeza que siente la oveja después de descubrir la dura realidad de la muerte es la que le motiva para querer aislarse del mundo real

En general, su deseo de escapismo debido a la tristeza, que nace también de su inocencia, es el combustible que alimenta su determinación para conseguir sus objetivos en el Reino de los Sueños. 
En resumen, Lulla es ingenua y tierna, pero está dispuesta a luchar superando obstáculos mucho más grandes que ella, incluso enfrentarse a sus peores pesadillas, solo para escapar de su miedo real: la tristeza auténtica que sentirá al despertarse sin su madre. 

#### George y Byron
George y Byron son los dos personajes secundarios que ayudarán y guiarán a Lula en el mundo de los sueños. Son “el timón y pumba” del juego, siendo, a pesar de no ser parientes de Lula, una figura de guía para ella.  Son personajes que habitan en el mundo de los sueños de todos los seres vivos, pero se manifiestan de distintas formas en cada uno, en personalidad muy parecidos, pero en personificaciones diferentes.  
- George: Es un cerdo, de color rosado, grandote, torpe, y caricaturesco. Además, lleva un esmoquin, y al igual que Byron, su fiel acompañante, siempre aparecen en un charco de barro durante todo el juego, que es donde Lula siempre ha visto a los cerdos en las granjas vecinas donde vive. Esto es así porque asocia a los cerdos con la sabiduría y con la diversión, siendo un animal ordenado, que vive como quiere sin ser juzgados.  A causa de esto, ayuda a Lula a conseguir la determinación para llegar hasta el final.
- Byron: Es una rana que está apoyada en la cabeza de George y es de color verde. Es más callado que su amigo, debido a que prefiere escuchar antes que hablar, y selecciona muy bien sus palabras, es un observador del mundo, se dedica a aconsejar y trata de tener una visión objetiva de las cosas. Trata de hablar con Lula acerca del riesgo de quedarse dormido mucho tiempo, aunque, al mismo tiempo, siente compasión y se reserva su opinión sincera para mostrarle a Lulla empatía y el deseo de que quiere lo mejor para ella.   
A pesar de ser un personaje de naturaleza reservada, se ha reflejado la imprevisibilidad 	del mundo de los sueños en su atuendo.Además, Byron aprovecha la oportunidad para 	alentar a Lulla, quitándole importancia al tema y tratando se infundirle diversión y confianza 
#### Mamá
La madre de Lulla es un personaje que, si bien no aparece directamente en el juego, tiene mucho peso narrativo, puesto que es su muerte la que desencadena los sucesos del juego.  

Meryl nació en una granja de crianza industrial ovina, donde miles de ovejas huérfanas reciben su crianza. En sus primeros años de vida, el único paisaje que la rodeó era el laberinto de pasillos y cercos claustrofóbicos de la instalación. Días y días de repetición la volvieron taciturna, e incluso cuando huyó con 16 años de aquel bloque deprimente de acero, no pudo quitarse la sombra gris que ahora proyectaba el edificio sobre su corazón.  

Todo esto cambió, sin embargo, cuando conoció a Tom. Era una mañana común y corriente para ella, esforzándose por llegar a clase a tiempo. En cuanto el carnero vio a Meryl recorrer el campus a toda prisa, sabía que se había enamorado, y semanas después se armó de valor para confesarse.  

El amor de Tom borró de un plumazo el peso que arrastraba su corazón, y cuando llegó el momento indicado, buscaron un pueblo tranquilo donde construir su hogar. Después llegó Lulla, su pequeño angelito, y Meryl se aseguró de que su infancia sería lo opuesto a la de ella: la vida de Lulla estaría llena de color, jugaría con sus amigos por el prado como ella nunca pudo, y siempre se aseguraría de cantarle una nana dormir.  

Cuando Lulla tenía 10 años, Meryl se puso enferma. Casi desde el comienzo, la madre sospechó que su aflicción sería mortal, y los síntomas que cada día se acrecentaban le dieron la razón. Llegó el momento donde ya no podía preparar el desayuno, después comenzó a necesitar ayuda para moverse, y poco a poco sus horas en cama eran demasiadas. El único esfuerzo que no podía dejar de hacer era cantarle a su pequeña, que la visitaba todas las noches como un duendecillo. Meryl sonreía al escuchar sus pequeños pasitos acercarse a la puerta. 

Finalmente, la enfermedad ganó, y Meryl solo deseó que su hija siguiese manteniendo su alegría, lamentándose de no poder cantarle un poquito más. 
### Enemigos
#### Fobos
Son una raza de pesadillas sin formar, que aparecen en el mundo para ahuyentar a los que pasan largas horas en el mundo de los sueños. Son un indicio de que Morfeo no desea que sigas allí. En apariencia son un ente como Bob en Monstruos contra Alienígenas o un slime del BOTW, pero a su vez tienen un aspecto más siniestro y hostil. Luchan cuerpo a cuerpo y en ocasiones extrañas, cuando se ven arrinconados, pueden lanzar proyectiles. 

Se alimentan de la negatividad y de la energía de Morfeo, y nacen a través de los vacíos del mundo, por tanto, aparecen a partir de la segunda mitad del primer nivel. Los vacíos son los espacios entre plataformas que no contienen nada debajo, por lo que pueden aparecer en cualquier lugar.  
#### Dolly
Es la primera oveja mutada, la cual, se manifiesta en el mundo de los sueños porque tiene tareas pendientes. Para Lulla, Dolly representa la crueldad del mundo hacia ella y su especie, es por ello que se manifiesta como pesadilla. Lulla teme que su destino pueda emular ese final que tuvo ella en algún momento de su vida.  

Además, el propósito de Dolly es atormentar a otras ovejas en sueños, actuando como “El Coco”, un elemento de la cultura popular del mundo que infunde miedo. 
#### Fantasma Oveja (Eos)
Es el arma más poderosa de Morfeo, bautizada como Eos, la diosa del amanecer para hacer despertar a aquellos que osan quedarse más tiempo en el mundo de los sueños.  

Su forma varía dependiendo del miedo del huésped, y en este caso es una oveja fantasma, que representa su miedo a la muerte de sus seres queridos. Sus poderes varían, y su objetivo es inequívoco: luchar contra Lula.  
Eos vaga por el mundo de los sueños levitando, esperando órdenes de Morfeo. Unicamente obedece las órdenes de Morfeo, no tiene una voluntad propia, ni un espíritu libre, no es un ente con la capacidad de razonar o comprender, tiene una función que debe cumplir a cualquier coste. 

### Guión 
OSCURIDAD PLENA
El narrador comienza a narrar mientras se ve una página de un libro con 5 viñetas. 
Narrador:
Esta es la historia de Lula
Se enfoca la primera viñeta en un primer plano
Narrador:
Lula, era una niña normal, feliz y enérgica como las demás ovejas de la zona
Se enfoca la segunda viñeta
Narrador:
Correteaba por los parques y establos todos los días sin cesar mientras descubría cómo funcionaba el mundo que le rodeaba.
Se enfoca la tercera viñeta
Narrador:
Hasta que un día, esa energía, se fue por donde vino... De la nada
Se enfoca la cuarta viñeta
Narrador:
No pudo seguir soñando durante un tiempo...
Se enfoca la quinta viñeta
Narrador:
Hasta que lo consiguió
CREDITOS INICIALES 
Lula abre los ojos y despierta en el mundo de los sueños. Mira a su alrededor y se encuentra en una cama en un terreno de hierba morada, flotando encima de la nada, hasta que ve un charco que le resulta familiar pero no sabe de qué exactamente. En el charco se pueden distinguir dos figuras, un cerdo, y encima del cerdo una rana. 
GEORGE (el cerdo) con entusiasmo
Holaaa Lulaaaa, ¡cuánto tiempo sin verte! No te veo desde lo de...
Byron interrumpe 
BYRON
¡Calla tocino!
Lula desconcertada, no responde. 
BYRON (la rana) dirigiéndose a George 
Deja a la chica en paz que está desorientada. 
BYRON (dirigiéndose a Lula)
Me alegro tanto de verte... Pero bueno basta de charlas, ¡ve a pasártelo bien!
GEORGE sonriente
Pero recuerda coger la almohada de donde la dejaste
BYRON
¡Justo después del campo de amapolas! 
COMIENZA EL NIVEL 1.1 EL TUTORIAL. Y al terminar sucede la siguiente secuencia en una explanada.
GEORGE
Vaya vaya, ¡que rápida eres! Ya has llegado hasta aquí.
BYRON 
Uy, pero qué ven mis ojos... Deberías tener cuidado con los FOBOS.
GEORGE con aspecto más preocupado
Esas pesadillas sin forma son peligrosas, igual deberías ir volviendo... 
LULA
Cogeré la nana de mi madre y me iré te lo prometo.
BYRON 
Bueno... Tienes tu almohada para zumbarles, recuerda pasarlo bien y volver pronto.
CONTINUA EL NIVEL 1.2: EL ATAQUE DE LOS FOBOS
BYRON
¡Requetecorcholis! Sí que has llegado lejos sin despertarte
GEORGE
A Morfeo no le gustan estas cosas.
BYRON
Creo que por una vez George tiene razón, esto se está poniendo peligroso
A PARTIR DE ESTE PUNTO EMPIEZA LA NOCHE, LOS ÁRBOLES CAMBIAN Y LA AMBIENTACIÓN SE OSCURECE
BYRON
Tendrás que preocuparte por cosas más tenebrosas que los fobos de aquí en adelante.
GEORGE
Ten cuidado Lulla.
COMIENZA EL NIVEL 2.1 LA NOCHE DE LAS DOLLYS 
GEORGE confuso
Oye Byron, ¿esa no es Lulla? 
BYRON asombrado y enfadado al mismo tiempo 
¡¿Pero qué haces todavía aquí!? 
GEORGE
Oh no esto es malo Byron, Morfeo mandará a Eos a por Lula.
BYRON
Bueno... Ya no hay nada que podamos hacer para convencerte... Lo que buscas está al otro lado del puente.
GEORGE
No debería decir esto, pero... ¡Mucha suerte!
COMIENZA EL NIVEL 2.2: CON AMOR, MAMÁ
MERYL 
Ya puedes dormir tranquila hija mía. 
LULLA triste
Mamá desde que te fuiste nada es igual, te echo de menos, pero ya podré vivir tranquila conservando tu recuerdo en lo más profundo de mi corazón. Te quiero
FIN

### Escenas y cinemáticas
El juego tendrá dos tipos de escenas no jugables: viñetas con dibujos 2D y pequeñas cinemáticas 3D dentro del mismo gameplay.  
Una vez explicado el diseño artístico de las escenas no jugables, se desarrollará su contenido y propósito en el juego. 
- Cinemática inicial: 
La cinemática se encarga de presentar brevemente a Lulla y poner en contexto al jugador, ya que este necesita saber que está en el mundo de los sueños. Además, da algunas pinceladas de información sobre el desarrollo de la trama y prepara el giro argumental más importante, puesto que en una de las viñetas aparece la silueta de la madre de Lulla.  
Seguidamente, se darán unas explicará la información brevemente relativa  sobre viñeta:
- Primera conversación con George y Byron: 
Esta es la primera interacción de Lulla con los NPC aliados, y ocurre nada más superar los primeros obstáculos de la primera zona. En estas primeras instancias de juego, George y Byron se han ubicado de manera planeada para indicar al jugador el camino a seguir.  
Narrativamente, los dos aliados de Lulla cumplen una función similar a su contraparte de ritmo de juego: recibir a Lulla y guiarla en sus primeros pasos por el mundo de los sueños, ya que todo lo soñado se termina olvidando al despertar.  


## 4. GAMEPLAY
### Jugabilidad
La jugabilidad es frenética, con mecánicas de juegos de plataformas centradas en el movimiento y físicas tales como plataformas que se desplazan o giran y saltos con obstáculos a evitar. Esto se combina muy bien con un sistema de combate basado en golpeos simples y reducción de vida para dar al jugador más sensación de poder y presentar diferentes peligros. Por último, también se cuenta con puzles combinando las mecánicas del juego que exigen al jugador que utilice su ingenio para poder resolverlos y avanzar en el nivel. 

### Sistemas HUD
#### Salud
La salud se mide con una barra que se rellena con contenedores de sueño los cuales se pueden obtener al derrotar enemigos o destruir objetos. 
Al perder toda la salud (sueño) el personaje despertará y por tanto se acabará la partida, teniendo que empezar desde el último punto de control. El sistema de puntos de control funciona de tal manera que cuando el jugador llega a uno, se guarda esa ubicación para que se regrese a la última más cercana cuando pierda o se caiga al vacío. 
#### Econocmia de salud
Para establecer la economía de salud se ha establecido el número máximo de golpes que el personaje puede aguantar del enemigo más débil sin recargar la salud. Se logra así establecer la dificultad de combate más sencilla comenzando por los enemigos más pequeños, y pudiendo hacerla incremental con aquellos más dificiles. De esta manera se aumenta la cantidad de golpes necesarios o puntos de vida para derrotarlos, y se lográ, a su vez, un equilibrio adecuado.  
Por ejemplo, si queremos que un personaje aguante 20 golpes de los Fobos antes de ser derrotado, y cada Fobo hace 5 de daño, la vida total de Lulla debe ser 20 x 5 = 100 puntos de vida 
#### Modificadores de estado 
De momento no se introducirán modificadores de estado, pero se han estado barajando opciones posibles para este apartado. 

### Flujo de juego 
### Personajes(s) del jugador
Como protagonista, Lulla es el móvil que pone en marcha los sucesos del juego. El mundo es su sueño, los enemigos, sus peores pesadillas manifestadas por Morfeo y por lo tanto su viaje es el del jugador.
En cuanto a Lulla como personaje, las características que destacan son su inocencia, su determinación y la tristeza.
#### Métricas del jugador 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/PlayerMetricsTable.png" width = "auto" height = "450">
</p>

#### Habilidades del juagdor 
El jugador contará con las siguientes habilidades: 
- Salto
- Doble salto
- Airdash
- Ataques físicos a corta distancia
- Salto de pared a pared
- Deslizamiento por railes
#### Combate 
El combate se basa en un sistema melee a corta distancia como los The Legend of Zelda. También se presentan peleas con jefes que tienen ataques a distancia y cuentan con patrones de ataque para desafiar al jugador. 
La protagonista golpea con una almohada que usa de arma dentro del mundo del juego

### Personajes enemigos
Habrá tres enemigos, dos “genéricos” y un boss, como se ha mencionado anteriormente (la oveja fantasma). Cada uno tendrá unas características de daño y vida variables, una mecánica de ataque distinta. 
- Fobos: Son unas criaturas parecidas a un charco viscoso. Son pesadillas sin formar y aparecerán a partir de la mitad del primer nivel. Son un enemigo estilo ‘Goomba’ de Mario Bros. Su función es complicar las zonas de plataformas y enseñar al jugador sus mecánicas de combate sin que haya demasiada dificultad.
- Ovejas Dolly: Clones de la oveja Dolly, cuya vida y comportamiento es más complejo que la de sus compañeros Fobos. El objetivo de estos enemigos es hacer los combates más interesantes y delimitar áreas donde pueda haber coleccionables o zonas explorables. Podrían aparecer también en zonas de plataformas, pero de forma más inusual.  
Todos los valores son orientativos y aproximados, después de realizar cálculos y establecer el máximo de enemigos de cada tipo a la vez y el daño del jugador por ataque se establecerán los valores finales.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/EnemiesTable.png" width = "auto" height = "150">
</p>

#### Jefes
La oveja fantasma será el jefe final del juego y se trata de una oveja híbrida, tiene la parte inferior fantasmal. Posee 3 patrones de movimiento para acabar con el jugador: 
- En el primer patrón, el jefe se divide en múltiples copias de sí mismo, cada una de un color diferente, las cuales se dirigen hacia el jugador. Para infligir daño al jefe, el jugador debe atacar estas copias en el mismo orden en el que se han dividido. Cada vez que se ataca con éxito una copia en el orden correcto, esta se desvanece en un remolino de humo. Sin embargo, si el jugador comete un error, su personaje sufrirá daño y el proceso de multiplicación se repetirá. El objetivo es golpear a las 4 copias en el orden correcto para avanzar al patrón 2. 
- En el segundo patrón el jefe se desplaza a una zona sin plataformas, fuera del alcance del jugador. El jefe empezará a arrojar fuegos fatuos o bolas de energía en dirección al jugador, quien debe golpearlas en el momento adecuado para causarle daño. El jugador debe realizar este proceso aproximadamente cinco veces para que el jefe avance al tercer patrón. En caso de alguna esfera impacte al jugador, le quitará un porcentaje de vida (aún está por determinar, pero oscilará entre el 10%-20%)
- En el tercer patrón el jefe se alejará a una zona sin suelo y se dividirá en 4 otra vez. En este caso cada copia lanzará en línea recta una esfera de energía de su color y el personaje debe devolverlas en el orden en que se han lanzado o en el que se han multiplicado (aún por decidir, aunque lo suyo sería hacer que fuera lo mismo, es decir, que se lancen las esferas en el orden en el que se han dividido). Al hacer esto de manera correcta una vez se habrá vencido por fin al jefe final. 
#### NPCs
Hay múltiples NPCs a lo largo del videojuego, desde los enemigos, a personajes aliados que servirán para poder desarrollar y ayudar al jugador en la trama de una forma dinámica.  
##### Aliados
Los principales NPCs del juego son George y Byron, un cerdo y una rana respectivamente. Estos se encuentran dentro del mundo de los sueños y serán un elemento clave para el desarrollo de la trama.  

Aparecen desde la primera escena, y guiarán a Lulla por este mundo de ficción. Hay un elemento que les identifica, que es un charco de barro. Se colocarán a lo largo del mundo con el propósito de que el jugador pueda identificar cuándo habrá un diálogo u cinemática que enriquecerá la trama.  
Características:  
- George: Es un cerdo de granja, de color rosado, sonriente y torpe a la hora de hablar. 
- Byron: Elocuente, más sensato que George, y trata de ser una figura que haga feliz a Lulla en todo momento
  
### Movimientos y fisicas
#### Controles
El juego cuenta con 3 tipos de controles diferentes, entre ellos se encuentran teclado y ratón, móvil y gamepad (PlayStation, Nintendo, Xbox o cualquiera genérico). Además, los indicadores contextuales del juego se adaptan en función del tipo de control que se está usando. 
##### PlayStation
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Screens%20and%20Interfaces/Controlls/PS_controls.png" width = "auto" height = "250">
</p>

##### XBOX
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Screens%20and%20Interfaces/Controlls/XBox_controls.png" width = "auto" height = "250">
</p>

##### Dispositivos móviles
En dispositivos móviles los controles estarán superpuestos en la interfaz, con un joystick para el movimiento, 4 botones para las acciones principales, un botón para la pausa en la esquina superior derecha y para mover la cámara basta con deslizar el dedo en la mitad derecha de la pantalla. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Screens%20and%20Interfaces/Controlls/movile_controls.png" width = "auto" height = "250">
</p>

##### Switch
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Screens%20and%20Interfaces/Controlls/Switch_controls.png" width = "auto" height = "250">
</p>

##### PC
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Screens%20and%20Interfaces/Controlls/PC_controls.png" width = "auto" height = "250">
</p>

#### Cámaras
La cámara utilizada en el juego durante la jugabilidad es una cámara en 3ª persona con movimiento libre. 
Esta cámara cuenta con una función que hace que se acerque al jugador cuando encuentra un obstáculo sólido que no debe traspasar, por ejemplo, una pared o el suelo. 
Cuando el jugador entra en un diálogo, la cámara se coloca dinámicamente en un punto intermedio entre el jugador y el personaje con el que está conversando. Cuando se acaba el diálogo, la cámara se vuelve a colocar automáticamente detrás del jugador. 
Para las cinemáticas se cuenta con diferentes cámaras colocadas estratégicamente para cada secuencia, y las cuales cuentan con movimientos de cámara como Dollys y Tracks, con planos bien medidos aprovechando el control sobre las cámaras que el equipo tiene en cinemáticas. 


## 5. INTERFACES
La interfaz de juego debe ser sencilla y despejada para facilitar el mayor rango de visión posible para el jugador.  

### Interfaz de juego
Esta sencillez se caracteriza por una barra de sueño situada en la esquina superior izquierda. 
La interfaz de juego debe ser sencilla y despejada para facilitar el mayor rango de visión posible para el jugador.  
Por ello, el jugador solo dispondrá de la barra de sueño (o vida) en la esquina superior izquierda. Esta barra tiene una animación simulando el líquido de una lámpara de lava, con los colores morados y azules de la paleta, y cuenta con un reborde de un color que lo resalte del escenario 3D. También tendrá un icono que será el mismo de los elementos 3D que se sitúan por el escenario y que al recogerlos recargan esta barra. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/HUD/HUDSketch2.jpg" width = "auto" height = "250">
</p>
La información contextual que aparece para interactuar con los elementos de la escena puede situarse en el inferior de la pantalla centrada, o puede integrarse dentro del mundo 3D en forma de “bocadillos” cerca o encima del objeto interactivo. 
La opción más atractiva visualmente y que mejor encaja con la estética que se quiere conseguir es la segunda, además de aumentar la cohesión entre el 2D y el 3D del juego. Es por ello que cuando el jugador se acerca a un elemento interactivo aparece un pequeño “bark”  o burbuja encima del elemento con un icono del botón a pulsar para interactuar con él. 
Como se detectan los controles que se están usando, cuando se juega con teclado y ratón o con mando se omite el botón de pausa debido a que el movimiento del ratón y del joystick izquierdo irá asociado al movimiento de la cámara, por lo que no será posible clicar ningún botón con ratón ni con los joysticks. 
Para pausar cuando se usen estas entradas se hará a través de la tecla ESC y los botones del mando adecuados.  
Sin embargo, en la interfaz para móvil sí se encuentra el botón, ya que no hay otra alternativa para poder pausar el juego. 

#### Interfaz de juego en dispositivos móviles 
Si el usuario está jugando al juego desde un dispositivo móvil se superpone a la interfaz del juego base los siguientes elementos: 
- Joystick de movimiento. Se sitúa en la parte inferior izquierda de la pantalla y controla el movimiento del personaje.
- Cruz de botones A/B/X/Y. Se sitúan en la parte inferior derecha de la pantalla y tienen las mismas acciones asociadas que los botones de un mando físico.
- Botón de pausa. Se sitúa en la parte superior derecha y permite al usuario pausar el juego.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/HUD/HUDSketch3.jpg" width = "auto" height = "250">
</p>

### Diálogos
Los diálogos siguen el estilo de los del juego Animal Crossing, situando a Lulla en un lado de la pantalla y al NPC en el otro lado. Para ello cuando se interactúe con un personaje y se abra la interfaz de diálogo, previamente habrá un movimiento de cámara para situar a los personajes en esta posición. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/Dialogs/DialogInterfaceSketch1.jpg" width = "auto" height = "250">
</p>

La interfaz de diálogo consiste en una nube donde aparece la conversación que está teniendo lugar. Sobre esta nube se sitúa una pequeña etiqueta con el nombre del personaje que está hablando en la parte superior izquierda. A su vez, en la parte inferior derecha se encuentra el botón o la tecla asignada a continuar con el diálogo. 

### Tutoriales
Los tutoriales son in-game y aparecen al acercarse a la parte delantera de un objeto designado única y exclusivamente para los tutoriales llamado cartel. 
Cuando el jugador entra en la zona designada, aparece sobre el cartel una pequeña ventana integrada en el mundo 3D que muestra el tutorial a aprender. 
La ventana tiene forma de nube y los tutoriales están dibujados como si fueran bocetos y en ellos se muestra el botón a pulsar para realizar esa acción a aprender. En la parte superior de la ventana se sitúa el título del tutorial.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/Tutorials/TutorialInterfaceSketch2.jpg" width = "auto" height = "250">
</p>

Para salir del tutorial el jugador debe alejarse y salir del rango del cartel, y esta burbuja se cierra. De esta forma no se interrumpe el movimiento del jugador ni se vuelve intrusivo para él. 

###  Diagramas de flujo de interfaces
En el siguiente diagrama podemos observar cómo interaccionan las diferentes interfaces entre sí y cómo se pasa de una a otra. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/FlowOfScreen.png" width = "auto" height = "250">
</p>

### Pantalla de inicio 
La pantalla de inicio es la pantalla principal del juego desde la que el usuario va a poder acceder a otras pantallas y va a poder iniciar una partida. 
Es por ello que debe ser una pantalla que capture la esencia del juego, pero sin desvelar la trama y los secretos del mismo. 
Es por ello que se han barajado varias posibles opciones de pantalla de inicio, todas con su propuesta de disposición, de botones y de gráficos de fondo. En ambos casos, el logo y el título permanecen inalterados, ya que es una parte importante de la pantalla de inicio y debe ocupar gran parte de la pantalla y estar centrado en ella. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/Main%20Screen/MainScreenSketch2.jpg" width = "auto" height = "250">
</p>

El diseño final de la pantalla de inicio tiene a Lulla dormida plácidamente, con un cielo estrellado sobre ella. La luna es el logo del juego y al seleccionar un botón de la lista de opciones, este se decora con una estrella a cada lado y se subraya. 
La pantalla de inicio cuenta con los siguientes botones: 
- Jugar. Al pulsarlo comienza una partida del juego.
- Opciones. Permite acceder a la configuración, donde podrán editarse ajustes de imagen y sonido.
- Controles. A través de él se accede a la pantalla donde se muestran los controles para todas las entradas que acepta el juego.
- Contacto. Abre una página en el navegador con el Beacons del equipo de desarrollo.
- Salir. Cierra el juego en la versión local.
Después de contar con un boceto inicial, durante la creación de la pantalla definitiva de barajaron varias opciones y se reorganizaron los elementos. Se situaron las opciones de la interfaz en el centro para lograr una disposición más coherente y visualmente más equilibrada. 
Resultado de pantalla: 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Screens%20and%20Interfaces/Main%20Screen/Main_menu.png" width = "auto" height = "250">
</p>

### Pantalla de carga
Esta pantalla aparece cuando se acede a una nueva partida, informando al jugador de que se están cargando los recursos del juego. 
Para proporcionar información constante al jugador de que el juego sigue cargando y no se ha quedado colgado hay una animación que se repite en bucle. De esta forma también conseguimos que la pantalla no sea estática y no aburra al jugador.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/Loading/LoadingScreenSketch3.jpg" width = "auto" height = "250">
</p>

El estilo final de la pantalla será un fondo de un cielo nocturno con una gran luna llena y unas nubes que la acompañan. En la parte inferior de la pantalla aparecerá el texto “Cargando...” y la animación de las estrellas girando. 
Resultado de pantalla: 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Screens%20and%20Interfaces/Loading/00_Example.png" width = "auto" height = "250">
</p>

### Pantalla de pausa
Esta pantalla es accesible al pausar el juego, ya sea a través de la tecla asignada al teclado y al mando o a través del botón de pausa en dispositivos táctiles. 
La pausa es una pantalla que se superpone al juego, por lo que se verá en todo momento el estado en el que se ha quedado el jugador al pausar. Está titulada con un texto “Pausa” que indica que estás parado. 
Se superpone la barra de sueño descrita en la interfaz de juego para que el usuario sepa en todo momento la “vida” de la que dispone. 
De la misma forma, encontramos una lista de botones con los que el usuario puede interactuar. El estilo visual de estos sigue el descrito para los botones de la pantalla de inicio. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/Pause/PauseScreenSketch2.jpg" width = "auto" height = "250">
</p>

- Continuar. Des-pausa el juego.
- Opciones. Accede a la pantalla de configuración.
- Controles. Accede a la pantalla de controles.
- Salir. Permite al usuario volver a la pantalla de inicio. Se le informará antes de salir de que con esta acción perderá todo lo que ha jugado hasta el momento y se pedirá la confirmación. 
La estética que esta pantalla trata de simular es la de que el juego pausado es un reflejo en la superficie de la luna que está en el cielo nocturno y que está ligeramente tapada por una nube. 
Resultado de pantalla:
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Screens%20and%20Interfaces/Pause/00_Example.png" width = "auto" height = "250">
</p>

### Patalla de opciones
Esta pantalla sirve para que el usuario configure su experiencia de juego. 
Las características que el jugador puede personalizar son las siguientes.
- Volumen general. Slider para controlar el volumen general del juego.
- Volumen de SFX. Slider para controlar el volumen de los efectos de sonido de forma independiente al resto de sonidos.
- Volumen de música. Slider para controlar el volumen de la música de forma independiente al resto de sonidos.
- Calidad de gráficos. Desplegable para ajustar la calidad de los gráficos del juego.
- Idioma (solo si se accede desde el menú principal). Botones para seleccionar el idioma del juego.
- Activar/Desactivar controles de móvil. Una casilla de verificación para activar y desactivar la interfaz de los controles para dispositivos móviles.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/Options/OptionsScreenSketch3.jpg" width = "auto" height = "250">
</p>

La pantalla sigue la estética descrita anteriormente, con un fondo haciendo referencia al cielo y las opciones sobre una nube con forma rectangular.

### Pantalla de controles
Esta pantalla muestra los diferentes mapeos de controles dependiendo del dispositivo de entrada que el usuario quiera usar.  
Para cada control se muestra un diagrama del mismo junto con las acciones asignadas a cada accionador. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/Controlls/ControlsScreenSketch1.jpg" width = "auto" height = "250">
</p>

Dentro de la pantalla de controles el usuario puede navegar por las diferentes pestañas creadas para cada posible dispositivo de entrada. En total hay cinco pestañas: 
- PC. En ella se muestran las teclas y los botones del ratón asociados a cada acción posible del juego.
- XBox. En ella se muestra el mapeo de controles para un mando de Xbox o compatible.
- PlayStation. En ella se muestra el mapeo de controles para un mando de PlayStation o compatible.
- Switch. En ella se muestra el mapeo de controles para un mando de Switch o compatible.
- Móvil. En ella se muestra la interfaz para controlar el juego en dispositivos móviles y las acciones asociadas del juego. 
La estética de esta pantalla sigue la línea de un cielo como fondo y nubes como los botones para cambiar entre pestañas. Además, para marcar la pestaña seleccionada, la nube de ese control está aumentada, desplazada hacia abajo y decorada con estrellas y una luna.
Resultado de pantalla:
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Screens%20and%20Interfaces/Controlls/Interface_controls.png" width = "auto" height = "250">
</p>

### Pantalla de usuario 
Esta pantalla aparece nada más el usuario presiona la opción de jugar en la pantalla principal y permite asociar un nombre de usuario o nickname al jugador. 
Esta pantalla consigue que, a la hora de recoger datos para las métricas de pensamiento computacional, estos aparezcan asociados a un nombre de usuario. 
Además, le recuerda al usuario que si está usando un móvil puede activar los controles táctiles. 
Una vez el jugador ha introducido un nombre y ha personalizado los controles, comienza el juego pulsando la tecla que aparece al lado de “continuar” en la esquina inferior derecha. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/Nikname/NiknameScreenSketch3.jpg" width = "auto" height = "250">
</p>

### Pantalla de selección de idioma
Esta pantalla aparece antes que cualquier otra cuando se inicia el juego. En ella aparecen botones con forma de banderas representando los diferentes idiomas en los que está el juego. 
Para avanzar, el usuario debe escoger el idioma de su preferencia y el juego se traducirá automáticamente a este. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Screens%20and%20Interfaces/Language/LanguageScreenSketch1.jpg" width = "auto" height = "250">
</p>

### Diagrama de flujo entre pantallas
En el siguiente diagrama podemos observar cómo interaccionan las diferentes Pantallas entre sí y cómo se pasa de una a otra. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/FlowOfScreen.png" width = "auto" height = "250">
</p>

## 6. NIVELES
### Diseño de niveles
Con el fin de proporcionar un análisis y una descripción detallada del diseño de niveles se analizarán en primer lugar los elementos generales del mundo. Se especificarán desde los tipos de plataformas y elementos dañinos para el jugador, hasta las combinaciones entre amabas para generar puzles y así aumentar la dificultad a lo largo del juego. Además, se determinará cómo superar dichas adversidades.  
Antes de comenzar con ello, se describirán los niveles y la separación del juego.  

Habrá dos niveles tal y como los conocemos, de aproximadamente 20 minutos de duración cada uno. El primer nivel se divide en dos partes, siendo la primera “el tutorial” a nivel de mecánicas de movimiento básicas, y la segunda para afianzarlas e introducir la mecánica de lucha.  Este enfoque se implementa con el propósito de brindar al jugador la sensación de progreso y evitar la monotonía al ofrecer elementos que ya conoce. Al mismo tiempo, se busca que los entusiastas de las plataformas no se aburran o se sientas restringidos.  
Se ha decidido dividir en mitades los niveles para que el jugador pueda ver los cambios de una manera clara, pero a su vez para que la jugabilidad no se interrumpa de forma abrupta. Cada vez que termine una mitad se introducirá un elemento nuevo, marcando así la diferencia y el nuevo nivel de dificultad entre una parte y otra. El segundo nivel también se dividirá en dos partes: la primera incluirá la introducción de un nuevo enemigo más complejo, y la segunda constará de la pelea final contra el jefe. 

Elementos de los niveles: 
- Bloques de salto básico: Es un bloque de altura determinada para que el jugador salte una única vez. Habrá zonas amplias diseñadas para permitir al jugador la posibilidad de explorar el mundo a pesar de tener un camino principal establecido. De esta manera, se proporcionan rutas alternativas para que el jugador no se sienta limitado y pueda investigar o experimentar cierta sensación de libertad en el mundo En esta imagen se intenta representar lo dicho anteriormente; el jugador puede ente plataformas con distinto nivel de altura o puede optar por el camino de altura inferior para llegar a la siguiente plataforma.
  <p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/basic_jumping_platform.jpg" width = "auto" height = "250">
</p>

- Bloques y columnas de doble salto: Los bloques y las columnas de doble salto son elementos del mundo que se presentarán para introducir el concepto del doble salto, que adquirirá una mayor complejidad en etapas posteriores del juego. Al igual que en el apartado anterior, se ofrecerán múltiples opciones de camino dentro del recorrido que el jugador debe seguir. En la imagen proporcionada, se ilustra lo mencionado, permitiendo al jugador saltar entre las columnas o explorar la parte trasera de la imagen para intentar abordar las columnas desde una perspectiva diferente.
  <p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Double_jump_blocks_and_columns.jpg" width = "auto" height = "250">
</p>

- Plataformas móviles: Son plataformas situadas en el aire que ejecutarán diferentes movimientos, incluyendo desplazamientos verticales en el eje y en ambas direcciones, así como movimientos horizontales en los ejes x, y, z. Estos darán lugar a la creación de diversos patrones, los cuales serán definidos en detalle a continuación.
    - Movimiento lateral:  En secuencias de múltiples plataformas, las plataformas se moverán únicamente sobre el eje x o el eje z, son para secuencias sencillas pero que aportan dinamismo a la experiencia del jugador y construcción del mundo.
    - Movimiento vertical: En secuencia o por solitario, plataformas con la misma apariencia que las anteriores describen un movimiento sobre el eje y. Servirán para desplazamientos más sencillos y son zonas sin patrones, ya que, añade una complejidad mayor al juego, lo que puede generar en los jugadores menos experimentados frustración.
    - Movimiento complejo: Hay plataformas que no describirán un movimiento en un único eje, para poder desplazarse a otras zonas y aportar variedad al juego, se describen distintos movimientos, como por ejemplo en L. Con este sistema de waypoints nos permite explorar patrones de movimiento que contribuyen a la jugabilidad y al movimiento. 
  <p align="center">
    <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/platform_lateral_movement.jpg" width = "auto" height = "200">
    <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/platform_vertical_movement.jpg" width = "auto" height = "200">
    <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/complex_movement.jpg" width = "auto" height = "200">
</p>

- Plataformas caíbles: Plataformas que se caen si el jugador está encima durante un tiempo determinado. El tiempo variará dependiendo del nivel en el que se esté.
 <p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Dropable_platforms.jpg" width = "auto" height = "250">
</p>

- Botones: Se incorporarán botones en ciertas áreas del juego para activar plataformas móviles que facilitarán la progresión a través de secciones que de otra manera serían intransitables. La imagen que se muestra ejemplifica una situación como la descrita anteriormente. La zona resaltada en rojo representa un área de peligro para el jugador. Como se puede apreciar en la imagen, al presionar el botón, la plataforma se desplazará hacia la ubicación del jugador, permitiéndole cruzar esa zona. Una vez que la plataforma móvil llegue al extremo opuesto, realizará un recorrido de regreso. Aunque, más adelante en la progresión del juego pueden tener solo un sentido de movimiento.
 <p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/buttons.jpg" width = "auto" height = "250">
</p>

- Pinchos:  Los pinchos serán un elemento peligroso en el entorno del juego y reducirán la vida del jugador al entrar en contacto con ellos. Se han diseñado con el propósito de evitar que, si el jugador comete un error y cae en un obstáculo, no sufra una derrota instantánea, especialmente en secciones donde caer al vacío puede ser una amenaza constante. Esto se hace para prevenir la frustración del jugador al minimizar las pausas en el juego y mantener un ritmo fluido en la jugabilidad. Además, los pinchos servirán para marcar el camino a seguir, lo cual es esencial para la orientación del jugador. Estos elementos se combinarán con paredes, plataformas y otros elementos en etapas posteriores del juego. A continuación, se mostrará un prototipo de los pinchos.
 <p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/spikes.jpg" width = "auto" height = "250">
</p>

- Doble pared: Las "dobles paredes" consisten en dos paredes cercanas y una plataforma en la parte superior. Para acceder a la plataforma superior, se requiere el uso de esta mecánica. Por lo general, en la parte inferior de las dobles paredes, habrá elementos peligrosos como pinchos u otros obstáculos dañinos.
 <p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/double_wall.jpg" width = "auto" height = "250">
</p>

- Tambores: Son unos cilindros con tambor y unas baquetas, que lo que hacen es hacer un efecto trampolín al dejarte caer, pero al estar en el punto más alto se tiene la oportunidad de tener salto doble y mantener esa altura
 <p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/spring_platforms.jpg" width = "auto" height = "250">
</p>

- Chekpoints: Cada ciertos obstáculos o enfrentamientos, se pondrán chekpoints para agilizar la experiencia del jugador. Aquí un ejemplo:
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/checkpoints_elements.jpg" width = "auto" height = "250">
</p>

- Raíles: Son el método de desplazamiento más rápido dentro del mundo, con el cual, el jugador se desliza. Se intercalarán con obstáculos que tenga que saltar y esquivar. Además, existen desvíos en el mundo para obtener vida adicional, o en un futuro posibles coleccionables. Xon el fin de que el jugador no tenga que repetir zonas, se proporcionará un raíl que le lleve de vuelta al camino principal.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/rails_elements.jpg" width = "auto" height = "250">
</p>

- Elementos decorativos: Habrá dados, y bastones de caramelo a modo de decoración en el mundo. Además, se utilizará como guía para que el jugador sepa por dónde dirigirse en caso de que se vea algo perdido.  Puede haber agrupaciones de estos o encontrártelos de forma individual como se mostrará a continuación. Los elementos del mundo son fantásticos y ayudan a decorar las escenas, otorgando la personalidad que se busca al juego. Algun ejemplo de ello es la imagen que se muestra a continuación.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/decorative_elements.jpg" width = "auto" height = "250">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Decorative_element.png" width = "auto" height = "250">
</p>

#### Concepto de nivel 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/decorative_elements.jpg" width = "auto" height = "250">
</p>

### Esquema de progresión del juego 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/decorative_elements.jpg" width = "auto" height = "250">
</p>

### Ficha de niveles
#### Nivel 1
Isla 1: Al ser el comienzo del juego, las pruebas de esta isla son las más sencillas. Primero unos escalones enseñan al jugador a utilizar el salto normal. A continuación, se debe saltar de columna haciendo uso del salto doble, que también se enseña en esta zona. Finalmente, se llega a un punto de guardado y a las plataformas móviles que te llevarán a la siguiente parte del tutorial y a la siguiente zona del mundo.

Isla 2: El primer reto de esta isla son las 3 plataformas móviles sobre las que se debe saltar para llegar. Después el jugador encuentra por primera vez a George y Byron con los que podrá iniciar diálogos. Posteriormente, desciende desde la parte superior de la isla realizando saltos sobre pilares, y finalmente se introduce la mecánica del salto pared. 
La segunda mitad de la isla también presenta retos, ya que para ascender es necesario realizar múltiples saltos sobre pilares y saltos en pared hasta llegar arriba.

Isla 3: Esta isla se focaliza en la mecánica del dash, demandando que el jugador realice uno incluso para llegar a esta zona de la isla. Además, para poder atravesarla, se deben ejecutar una serie de saltos con dash de un pilar a otro. En caso de caída, el jugador deberá evadir a los enemigos en la parte inferior y regresar subiendo la rampa.

Isla 4: Esta isla es más grande que las anteriores, y en consecuencia, también tiene más retos. El jugador empieza esta isla con el encuentro nuevamente de George y Byron, quienes proporcionan al jugador una almohada para introducir la mecánica de combate. Inmediatamente después, se presenta un combate obligatorio con los fobos, incitando al jugador a experimentar directamente la mecánica de combate.
Al concluir la pelea el jugador deberá realizar una serie de saltos sobre plataformas móviles, así como saltos en pared, para ascender al siguiente nivel de altura de la isla. En esta nueva área, se presenta un obstáculo con pinchos, un elemento que se utilizará de ahora en adelante. Para superarlo el jugador deberá descubrir la ruta más optima para de saltos, tanto para evitar los pinchos como para lidiar con las plataformas móviles. 
Finalmente, después de esta zona intensa de plataformas, el jugador deberá enfrentar a más fobos para conseguir así acceso al botón que abre el camino a seguir.

Isla 5: En esta sección del nivel, es imprescindible activar tres botones para obtener acceso al que se desplazará hacia la siguiente zona marcada en amarillo. Cada uno de los islotes presenta una prueba específica, y al presionar un botón, se eliminará un anillo de protección asociado al botón principal.
 <p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Level_1.png" width = "auto" height = "250">
</p>

#### Nivel 2
Para el nivel 2 se han respetado las distancias mencionadas para el primer nivel, a excepción de zonas más complejas para seguir con la curva de progresión. Se mencionarán más adelante, en primera instancia se mencionará el recorrido del nivel con imágenes ilustrativas. Las flechas en color amarillo indican el camino principal del jugador, en caso de bifurcaciones se especificarán otros colores.
- Parte 1: El jugador tiene varios enfrentamientos y plataformas por delante. Y se ha seguido un esquema en curva. Posteriormente, se ramifica en tres partes el posible camino, en los de los extremos hay enemigos situados en esas plataformas, lo que, a pesar de que a nivel de habilidad sean más fáciles tiene un valor añadido. Una vez se supera esta parte se toca un botón para pasar a la siguiente.
-	Parte 2: Una vez se avanza por este camino el jugador debe pulsar dos botones para continuar. De esta manera se podrá acceder a la zona del puzle. Dicho puzle, al igual que en el primer nivel, conlleva moverse por distintas secciones para accionar un botón y volver al punto de origen.  Los caminos de ida en esos caminos están señalizados con el color rojo, y el verde para la vuelta.
 <p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Level_2.png" width = "auto" height = "250">
</p>

### Ficha de niveles
#### Título: Campo de amapolas (Tutorial)
##### Ficha
Encuentro: El jugador se materializa en el mundo de los sueños, ubicado en una explanada sobre una cama, desde donde se le proporciona orientación. El propósito principal de este nivel es que el jugador se familiarice con el entorno, los elementos del mundo y las mecánicas fundamentales, convirtiéndose así en una especie de tutorial introductorio. 
Objetivos: El objetivo de este primer nivel para el jugador es conseguir la almohada que se ha dejado aquí anteriormente (lo que narrativamente implica que ya ha estado aquí pero no se acuerda). El progreso de este nivel se verá representado en obstáculos y plataformas de distintos tipos. Habrá los siguientes elementos:
- Columnas rocosas: Serán unas columnas por las cuales el jugador deberá saltar por su parte superior.
-	Paredes: Son una zona en la que el jugador deberá saltar de pared en pared para llegar a la cima.
-	Nubes: Son unas plataformas que se caen si el jugador permanece mucho tiempo. 
-	Pinchos: Los pinchos infringen daño si se chocan lateralmente o si se cae encima de ellos. Visualmente se asemejan a unos conos de helado. 
Enemigos: En esta primera fase, no se presentarán enemigos con los que el jugador deba enfrentarse directamente. No obstante, se introducirán los "fobos". Dado que el jugador no dispone de un arma, la única opción será evadirlos, destacando la necesidad de adquirir algún medio de defensa. Esto preparará la introducción de la almohada, mostrando al jugador su utilidad como herramienta de defensa.
Personajes: Aparecen George y Byron al principio del nivel y al final
##### Objetos 
Al concluir el nivel, el jugador adquiere la almohada, que posteriormente se utilizará como arma en niveles subsiguientes.
##### Recompensas 
Al atravesar ciertas áreas con obstáculos, al jugador se le otorgará vida al recoger un ítem específico.
##### coleccionables
Hasta el momento, no se han introducido coleccionables, aunque se han considerado algunas opciones para su posible implementación en el futuro.

#### Título: el ataque de los fobos (Nivel 1)
##### Ficha
Encuentro: Inmediatamente después de completar el tutorial, el jugador se enfrenta a una pelea para aprender la mecánica de combate. Durante un diálogo con George y Byron, se establece que el mundo de los sueños es un lugar donde se debe permanecer por períodos cortos, o de lo contrario, las pesadillas intentarán "despertar" al jugador. La protagonista responde que busca algo y debe continuar buscando, por lo que desea permanecer en ese mundo. Por lo tanto, el objetivo es seguir avanzando.
Objetivos: Para superar el nivel, el jugador debe enfrentarse a enemigos básicos, superar nuevos obstáculos y resolver los primeros puzles. Los enemigos mueren con un solo golpe. Las nuevas plataformas y obstáculos incluyen:
-	Raíles: Superficies cilíndricas que permiten al jugador avanzar más rápido por el mundo, con obstáculos relacionados.
-	Botones: Al pulsar botones, se activarán mecanismos que moverán plataformas, columnas u otros elementos que obstaculizan al jugador.
-	Zonas de combate obligatorio: No se puede avanzar a la siguiente plataforma hasta que se haya completado el combate.
Enemigos:
-	Fobos: Masa viscosa que se dirige hacia el jugador y ataca cuerpo a cuerpo. Puede resistir un golpe y su función principal es entorpecer las secuencias de obstáculos.
-	Neo Fobos: Similar a los anteriores, pero estos pueden disparar bolas de fuego fatuo a distancia.
Personajes: George y Byron: Elementos narrativos clave que vuelven a aparecer.
##### Objetos
La inclusión de diversos objetos que el jugador debe recoger y colocar para resolver distintos puzles añade una capa adicional de complejidad e interactividad al juego. Esto proporciona oportunidades para desafíos estratégicos y creativos, incentivando la exploración y el pensamiento lógico en la resolución de los rompecabezas.
##### Recompensas 
La implementación de la mecánica donde vencer a un enemigo o destruir objetos destructibles proporciona vida al jugador es una decisión que refuerza la conexión entre la acción del jugador y su recompensa. Esto crea un incentivo adicional para la interacción activa con el entorno y los elementos hostiles del juego, contribuyendo así a la dinámica y estrategia del gameplay. 
##### Coleccionables  
De momento no se introducirán coleccionables, pero se han barajado algunas opciones.

#### Título: Las ovejas Dolly (Nivel 2)
##### Ficha
Encuentro: Este nivel marca la continuación después de establecer las bases del juego, con George y Byron revelando una clave del mundo ficticio: "los muertos con asuntos pendientes pueden manifestarse en este mundo". Esto introduce un nuevo enemigo, la oveja Dolly. Al igual que en el nivel anterior, Lula persiste en su búsqueda de algo que le falta.
Objetivos: El jugador enfrentará combates con enemigos más formidables mientras supera obstáculos conocidos, pero de mayor complejidad. La novedad en el mundo se centra en la introducción de la mecánica de coger un cubo. Este objeto se utiliza para colocarlo en botones y resolver puzles, o incluso lanzarlo para golpear a los fobos. Además, se añaden elementos nuevos al entorno.
-	Mermelada (muelles): Estos elementos se utilizan para añadir dinamismo al salto y evitar que la mecánica resulte monótona.
-	Cubo móvil: Dados que hay botones que deben mantenerse pulsados, el jugador necesita manipular estos cubos móviles estratégicamente para completar los puzles.
Enemigos:
-	Fobos: Se mencionaron en el nivel anterior, siendo una masa viscosa que se dirige hacia el jugador y ataca cuerpo a cuerpo.
-	Neo Fobos: También mencionados previamente, son similares a los Fobos, pero pueden disparar bolas de fuego fatuo a distancia.
-	Dolly: Nombradas en referencia a la primera oveja clonada, estas son enemigos cuerpo a cuerpo más resistentes que los Fobos. Su nombre refleja su naturaleza de clones, y presentan un desafío adicional en el combate.
##### Objetos
La incorporación de pequeños cubos integrados en el mundo, con la utilidad previamente mencionada, aporta una dimensión adicional a la jugabilidad al requerir que los jugadores interactúen con su entorno para resolver puzles y superar obstáculos. Esto fomenta la exploración y la creatividad en la resolución de desafíos dentro del juego.
##### Recompensas 
La mecánica de otorgar vida al jugador al vencer a un enemigo o destruir objetos destructibles es una estrategia efectiva para equilibrar el desafío del juego. Esto recompensa la acción proactiva del jugador y promueve la participación en combates y la exploración del entorno, añadiendo un elemento estratégico al manejo de la salud en el juego.
##### Coleccionables  
La decisión de no introducir coleccionables por el momento, aunque se hayan considerado algunas opciones, permite mantener el enfoque del juego en otros aspectos de la experiencia. La flexibilidad para explorar la inclusión de coleccionables más adelante brinda la posibilidad de ajustar y mejorar la jugabilidad a medida que se desarrolla el proyecto.

#### Título: Para siempre (Final)
##### Ficha
Encuentro: Este es el último nivel, la arena del jefe final, donde el jugador se enfrentará y alcanzará el objetivo final. Se espera que el jugador supere las distintas mecánicas del jefe para vencerlo y así completar el nivel.
Objetivos: El progreso en este nivel se mide por el cambio en el patrón de lucha del jefe, que evoluciona a medida que el jugador avanza.
Enemigos: Eos, el jefe final, es el único enemigo y obstáculo en este nivel.
Personajes: George y Byron, Eos (el jefe final), y la madre de Lulla, Meryl. La presencia de estos personajes en el nivel final agrega un componente narrativo importante al desenlace del juego.
##### Objetos
La inclusión de objetos que restauran un poco de salud durante el combate en este nivel final añade una capa estratégica adicional. Proporciona al jugador la oportunidad de tomar decisiones tácticas sobre cuándo y cómo utilizar estos objetos para maximizar sus posibilidades de derrotar al jefe final. Esto agrega un elemento estratégico y de gestión de recursos al enfrentamiento.
##### Recompensas 
La mecánica de proporcionar vida al jugador al vencer a un enemigo o destruir objetos destructibles sigue presente en este nivel final. Esta decisión continúa reforzando la importancia de la acción proactiva del jugador, al tiempo que garantiza que el enfrentamiento con el jefe final sea desafiante pero equilibrado en términos de gestión de la salud.
##### Coleccionables  
La elección de no introducir coleccionables por el momento, aunque se hayan considerado algunas opciones, permite mantener la simplicidad o centrarse en otros aspectos del diseño del juego. Esta decisión también brinda flexibilidad para ajustar la experiencia del jugador según sea necesario durante el desarrollo del juego.


## 7. ARTE
### Arte conceptual 
Partiendo del estilo visual concretado al inicio del desarrollo, el arte conceptual se centra en la creación de bocetos de personajes y escenarios en los que se describe visualmente cómo debe ser el producto final. 
Para ello, se crean pequeñas ilustraciones de los escenarios y de los elementos, aunque no sea la versión final del arte y esté sujeta a cambios posteriores. Esto dependerá principalmente de los artistas 3D y de la disposición final que se haga del entorno y sus elementos.  

Es la idea artística inicial de la que se parte en la que se guía el modelado, el texturizado, el arte técnico, la iluminación y el postproceso, y donde se combinan para generar las distintas emociones y sensaciones que el juego busca transmitir al jugador. 

En cuento a los personajes y enemigos, el proceso consiste en que las formas de estos, los colores y las texturas cuadren con la narrativa y la personalidad de cada uno de ellos a la perfección, capturando su esencia y plasmándola a través de lo que el jugador ve en la pantalla. 
#### Elementos principales de mundo
Los elementos del mundo se han diseñado siguiendo una base cuadrada para optimizar el rendimiento del juego. Es por ello que se ha hecho una hoja de elementos principales del mundo: las plataformas principales, los pilares, los checkpoints, las puertas, los pinchos, etc. La manera de dar personalidad al entorno ha sido mediante las texturas, ya que la impasibilidad de realizar objetos de geometría compleja limitaba mucho la libertad artística.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Environments/Elements/Element_world_coconcept.jpeg" width = "auto" height = "250">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Environments/Elements/concept_Assets.jpg" width = "auto" height = "250">
</p>

Muchos de estos elementos no se han añadido.

#### Elemento de vida
El desarrollo del objeto de vida se ha llevado a cabo con un enfoque narrativo, dotándolo de significado en lugar de basarse únicamente en consideraciones estéticas. Se crearon dos variantes con una correlación entre ellos, y se fueron evaluando ajustando hasta crear la opción 3, que se estableció como la definitiva. Este proceso se llevó a cabo para mantener la singularidad. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Environments/Elements/Element_life.jpeg" width = "auto" height = "250">
</p>

### Arte 2D 
Utilizando el material producto del arte conceptual, se comienzan a definir los turn arounds de los personajes y de los enemigos, así como de los objetos del mundo. 
También se generan aquí las texturas finales que se aplican a los diferentes modelos 3D, los diferentes elementos 2D que se utilizan en las pantallas e interfaces y las ilustraciones que se usan para la portada del juego y publicidad del mismo. 
#### Texturas 
Se han creado texturas tileables para todos los objetos planos que prescinden del desplegado de UV, asegurando que puedan escalarse en el motor de Unity para adecuarla correctamente.  
Se comenzó con la implementación de colores de las plataformas principales ya que, partiendo de los pesos de color establecidos en la paleta, se eligieron aquellos tonos que predominarían en el entorno, estableciendo la base cromática.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/Environments/Elements/Cocept_colors.jpeg" width = "auto" height = "250">
</p>
Una vez establecido los colores del entorno, se desarrollaron las texturas de los elementos con variaciones de colores.  

##### Plataforma principal
Partiendo del número 13 y 30 se han creado las siguientes texturas para el suelo y la pared. Además, se han creado dos texturas para el suelo en dos tonos cada una de ellas y dos tipos de texturas para el suelo con cuatro variaciones de color cada una de ellas.
La decisión de ello fue añadir viveza al mundo y con ello se saturaron los colores de la paleta incluyendo algún que otro tono que no estaba incluido.
las siguientes son las paredes:
 <p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_platform%20wall_purple_type1.jpg" width = "auto" height = "90">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_platform%20wall_purple_type2.jpg" width = "auto" height = "90">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_platform_wall_red_type1.jpg" width = "auto" height = "90">
    <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_platform%20wall_red_type2.jpg" width = "auto" height = "90">
</p>
Las sigueintes son los suelos
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_platform_floor_blue_type1.jpg" width = "auto" height = "90">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_plaftorm_floor_blue_type2.jpg" width = "auto" height = "90">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_platform_floor_green1_type1.jpg" width = "auto" height = "90">
    <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_plaftorm_floor_green_type2.jpg" width = "auto" height = "90">
   <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_platform_floor_purple_type1.jpg" width = "auto" height = "90">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_plaftorm_floor_purple_type2.jpg" width = "auto" height = "90">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_platform_floor_yellow1_type1.jpg" width = "auto" height = "90">
    <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Platform/main_plaftorm_floor_yellow_type2.jpg" width = "auto" height = "90">
</p>

##### Pilares
Partiendo del número 20 se ha creado la siguiente textura: 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Jumping_pillar/jumping_pillar_purple.jpg" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Jumping_pillar/jumping_pillar_purple_orange.jpg" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Jumping_pillar/jumping_pillar_purple_pink.jpg" width = "auto" height = "150">
</p>

##### Puerta  
Al tener que respetar un peso de colores en el juego, los elementos principales que no son plataformas se han diseñado para resaltar las zonas del juego. Como las puertas deben ser un elemento que debe llamar la atención al jugador y debe destacar entre los muros, se han desarrollado con colores complementarios al morado. 

<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Door/texture_door.PNG" width = "auto" height = "200">
</p>

##### Dados 
Los dados son una plataforma importante en la jugabilidad. Para ello se han combinado dos colores secundarios de la paleta (el azul y el amarillo) con la misma finalidad que el objeto anterior, llamar la atención del jugador. 
En este caso, se han sacado las UVs del modelo 3D para crear la textura.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Dice/DiceUv.png" width = "auto" height = "200">
</p>

##### Railes  
La idea de los raíles era hacer una textura que recordase a un bastón de caramelo. Como el color rojo se ha reservado para ‘peligro’, se han hecho varias opciones de color. Con ambos se ha mantenido el contraste de color y se ha empleado el morado (con base azul y base roja respectivamente). 
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Rails/rail_texture.jpg" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Rails/rail_texture_2.jpg" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Rails/rail_texture_3.jpg" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Rails/rail_texture_4.jpg" width = "auto" height = "150">
</p>

##### Pinchos 
Para los pinchos se ha creado una textura de cono de helado usando las UVs del modelo 3D. 
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Spikes/ConoUV.png" width = "auto" height = "200">
</p>

##### Botón
Para los botones, el diseño original era representarlos mediane una geometría de botón. Sin embargo, debido a las restricciones de polígonos y con el objetivo de optimizar el rendimiento del juego, se ha optado por emplear una textura que simula los agujeros como el reborde de un botón. 
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Button/button.png" width = "auto" height = "200">
</p>

##### Tambores
Para los tambores se sacaron las Uvs del modelo para poder pintar sobre ellas. Se utilizaron colores que se añadieron dentro de la paleta para darle viveza.
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Jumping_platform/Drum_texture.PNG" width = "auto" height = "200">
</p>

##### Vallas
Los colores variaron porque fue el elemento de decoración que más tarde se incluye. Es por eso, que se tenían que cuadrar la tonalidad y se eligieron tres colores finales para añadir en Unity a la versión final de luego. 
Finalmente se escogió el amarillo porque contrastaba muy bien y combinaba con los pilares y los bastones de caramelo.
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Fence/Fence_orange.PNG" width = "auto" height = "150">
   <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Fence/Fence_pink.PNG" width = "auto" height = "150">
   <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Fence/fence_brown.PNG" width = "auto" height = "150">
</p>

##### Libros
Se hicieron dos tipos de tamaños y varios tipos de texturas para dale personalidad al mundo ya que han sido de los pocos elementos de decoración que se han terminado incluyendo en la versión Gold. Es por ello por lo que queríamos otorgar riqueza y lo hicimos a través de la combinación de colores y diseños de las texturas.
Las siguientes es de los libros cerrados:
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Books/book_close_1.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Books/book_close_2.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Books/book_close_3.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Books/book_close_4.PNG" width = "auto" height = "150">
</p>
Las siguientes es de los libros abiertos:
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Books/book_open_1.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Books/book_open_2.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Books/book_open_3.PNG" width = "auto" height = "150">
</p>

##### Cojines
Con los cojines, que son como los libros objeto de decoración, pasó lo mismo. Así que se hicieron dos tamaños distintos y 4 texturas diferentes para seguir aportando personalidad al mundo.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Cushion/Cushion_1.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Cushion/Cushion_2.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Cushion/Cushion_3.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Cushion/Cushion_4.PNG" width = "auto" height = "150">
</p>

##### Bastón de caramelo 
Es nuestro elemento de guía y por lo tanto debía tener colores que llamaran la atención al jugador. Se hizo la textura sacando las UVs.
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Candy/Candy_texture_orange.png" width = "auto" height = "200">
</p>

##### CheckPoint
Para el checkpoint se varió la textura (ya que también lo hizo el modelo) y se añadieron sombras en la parte superior y elementos gráficos y líneas en la parte de la base.
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Control_point/checkpoint_texture.PNG" width = "auto" height = "200">
</p>

##### Arco
Como al comienzo se estableció un peso de colores y el morado debía tener más protagonismo para los arcos se empleó únicamente variaciones de este. Sobre todo, para poder mantener esa armonía que se ha venido buscando a lo largo de todo el desarrollo. Aun así, se desarrolló la textura en varios colores más para tener un comodín.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Arch/Arch_blue.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Arch/Arch_purple.PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Arch/Arch_red.PNG" width = "auto" height = "150">
</p>

Champiñones 
Al igual que con cojines y los libros, al ser elementos de decoración se sacaron las UVs y se hicieron varios diseños de texturas para incluir en los diferentes niveles. Además, se modelaron tres tipos de champiñones diferentes.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Mushroom/mashroom_flat/circles_small_orange_texture(flat).PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Mushroom/mashroom_flat/pink_star_texture(flat).PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Mushroom/mashroom_flat/red_circles_texture(flat).PNG" width = "auto" height = "150">
</p>

##### Lámparas
Son elementos que se desarrollaron para el nivel de noche y hicieron texturas más oscuras siguiendo la estética del HDRI. Al incluirse dos tamaños se diseñó una textura en dos colores diferentes.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Trees/lamp_1%20(1).PNG" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Trees/lamp_2.PNG" width = "auto" height = "150">
</p>

##### Lulla 
Para crear las texturas de Lulla, se extrajeron las coordenadas UV del personaje y se procedió a pintar sobre ellas. Para conseguir una mayor expresividad del personaje, se diseñadores expresiones faciales específicas para Lulla. 
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Lulla's%20Face/Body%26Cap.png" width = "auto" height = "200">
</p>
Las siguientes que aparecen corresponden a las expresiones faciales:
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Lulla's%20Face/EyeLids_Angry.png" width = "auto" height = "100">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Lulla's%20Face/EyeLids_Happy.png" width = "auto" height = "100">
</p>
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Lulla's%20Face/EyeLids_Neutral.png" width = "auto" height = "100">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Lulla's%20Face/EyeLids_Sad.png" width = "auto" height = "100">
</p>

##### George
Para crear las texturas de George, se extrajeron las coordenadas UV del personaje y se procedió a pintar sobre ellas. Para conseguir una mayor expresividad del personaje, se diseñadores expresiones faciales específicas para George.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/George's%20Texture/Texture_George_body.png" width = "auto" height = "150">
</p>
Las siguientes que aparecen corresponden a las expresiones faciales:
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/George's%20Face/EyelidsAll.png" width = "auto" height = "150">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/George's%20Face/MouthAll.png" width = "auto" height = "150">
</p>

##### Byron
Para crear las texturas de Byron, se extrajeron las coordenadas UV del personaje y se procedió a pintar sobre ellas. Para conseguir una mayor expresividad del personaje, se diseñadores expresiones faciales específicas para Byron.
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Byron%C2%B4s%20Texture/Texture_change_byron.png" width = "auto" height = "150">
</p>
Las siguientes que aparecen corresponden a las expresiones faciales:
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Definitive%20Art/Textures/Gold/Byron's%20Face/EyelidsAll.png" width = "auto" height = "150">
</p>

### Arte 3D
A partir de los turn arounds realizados y siguiendo el concepto previamente establecido, se procede a la creación de los modelos de los personajes. Dependiendo del nivel de detalle deseado, se desarrolla un modelo de alta poligonización esculpido, el cual posteriormente se somete a la creación de su topología, o bien se lleva a cabo una modelación directa. 
En el caso de los Fobos, se ha llevado a cabo un modelado directo, a pesar de tratarse de una criatura viscosa con formas curvas. Se logró optimizar eficientemente la cantidad de polígonos, evitando un exceso de estos. Este enfoque también se aplicó al modelado de los personajes George y Byron, los cuales fueron creados mediante una modelación directa.
<p align="center">
  <img src = "" width = "auto" height = "200">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/George%20modelo.png" width = "auto" height = "200">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Fobos%20modelo.png" width = "auto" height = "200">
</p>

Por otro lado, en el caso del personaje principal, Lulla, se diseñó un modelo con una alta poligonalización esculpido específicamente para representar de manera precisa la forma de la lana de oveja. Posteriormente, se creó la topología correspondiente, resultando en un modelo óptimo para el proyecto.
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Lulla%20Modelo.png" width = "auto" height = "250">
</p>

Elementos del mundo:
- Montañas: A pesar de tener un aspecto onírico y una paleta de colores que no es el real, el mundo de plataformas es montañoso, inspirado en juegos como el Super Mario 64, o el Ori de la Nintendo Switch.
- Árboles y vegetación: Este aspecto puede ser el más cambiante del mundo, habrá desde árboles con apariencia de piruleta que cuando caiga la noche serán simplemente los palos desgastados, hasta setas de proporciones enormes, y árboles con hojas moradas. Una de las decisiones que se tomaron para la Beta fue desligar la vegetación tradicional del mundo real y crear elementos de decoración como sustitución. 
- Relación con animales: Lula, al haber sido criada en una zona campestre, ha tenido relación con distintos animales, por lo que, habrá elementos de estos, como nenúfares a modo de plataformas.
Relación con animales: Lula, al haber sido criada en una zona campestre, ha tenido relación con distintos animales, por lo que, habrá elementos de estos, como nenúfares a modo de plataformas. 
Para diseñar los elementos del mundo, se ha buscado minimizar el número de polígonos al máximo, logrando un equilibrio entre la creación de objetos con formas más orgánicas y suavizadas, evitando la rigidez, y una reducción de polígonos suficiente para garantizar un rendimiento adecuado del juego.
#### Plataformas principales 
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Plataforma%20principal%20modelo.png" width = "auto" height = "250">
</p>

#### Rampa
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Rampa%20Modelo.png" width = "auto" height = "200">
</p>

#### Pilares
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Pilar%20Modelo.png" width = "auto" height = "200">
</p>

#### Pinchos
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Plataforma%20Pinchos.png" width = "auto" height = "200">
</p>

#### Plataforma nube
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Plataforma%20nube.png" width = "auto" height = "200">
</p>

#### Objetos descriptivos
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Tambor%20modelo.png" width = "auto" height = "200">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Caramelo%20modelo.png" width = "auto" height = "200">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Plataforma%20hexagonal%20modelo.png" width = "auto" height = "200">
</p>

#### Checkpoint
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Lulla%20Modelo.png" width = "auto" height = "200">
</p>

#### Objeto de vida
<p align="center">
  <img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/Vida%20modelo.png" width = "auto" height = "200">
</p>
### Animaciones
Para llevar a cabo las animaciones, se emplearon distintos tipos de técnicas animativas. Dada la viscosidad y el movimiento irregular del Fobos, se optó por animar por vértices, logrando así transmitir una sensación viscosa. Por otro lado, los demás personajes fueron animados mediante sus respectivos esqueletos, para lo cual se llevó a cabo un riguroso trabajo de rigging y skinning.

### Arte técnico
#### Shaders
El juego sigue una estética cartoon, por lo que todos los elementos de la escena cuentan con materiales que son renderizados con shaders que simulan este estilo. 
También encontramos shaders especiales para otras funcionalidades, como para la barra de vida o el movimiento del dash. 
A continuación, se listan los shaders junto a su función dentro del juego. Algunos de ellos se pueden combinar si se usan para el mismo objeto.
- Toon Shader. Basado en el Cell Shading utilizado en juegos como Zelda BOTW y TOTK, le otorga al juego su característico aspecto de dibujo animado.
- Shader para agua. Utilizado en masas de agua, consigue crear espuma alrededor de los objetos que se crucen con la superficie sombreada con este shader.
- Shader para barra de sueño. Utilizando las lámparas de lava como referencia, este shader es utilizado en la barra de sueño de la protagonista para aportar un toque onírico y dinámico en la interfaz.
- Shader Fobos. Inspirado en el movimiento de la lava y el agua al estilo cartoon, este shader aporta a los enemigos Fobos movimiento en su interios, reforzando la idea de estar formados por un aura maligna y de pesadilla.
- Shader para el Dash. Con él se consigue que Lulla deje un rastro detrás de ella cuando se mueve a gran velocidad.
- Shader para cambiar el color a partes del modelo. Utilizado en el jefe final, se consigue que cuando se clone el modelo, este tenga distintos colores.
- Shader fantasmal. Utilizado para darle un aspecto fantasmal al jefe final, se puede combinar con el shader anterior ya que son parte del mismo modelo. Con él se consigue que la parte inferior del modelo parezca humo que cambia de colores constantemente.
- Shader de desvanecimiento. Utilizado para hacer objetos desaparecer fragmentándolos en pequeñas piezas que desaparecen.
- Shader de daño. Informa visualmente de que un enemigo o el propio jugador ha sido alcanzado por un ataque y ha sufrido daños.
- Shader movimiento de sombras. Parte del sombreado toon que consigue que las sombras no sean estáticas, sino que se muevan. Inspirado en el siguiente apartado de un articulo sobre el juego Crumble.
- Shader de sistema ocular procedural. Partiendo de un shader de creación propia anterior al proyecto, este shader modificado consigue añadir ojos 2D funcionales y personalizables proyectados sobre el modelo 3D de los personajes.
#### VFX
Los diferentes efectos visuales pueden ser lograrse con diferentes técnicas, como por ejemplo usando sistemas de partículas o shaders. Sin embargo, como el resultado final es diferente a lo que tradicionalmente se relaciona con un sombreador, los siguientes efectos no están catalogados como shaders en sí mismos. 
- VFX de ataque. Estela en forma de arco que aparece cuando Lulla golpea con la almohada.
- VFX de salto y aterrizaje. Simula las partículas de polvo que salen volando del suelo cuando un personaje salta y aterriza.
- VFX de caída. Estela que sigue al personaje mientras está cayendo.
- VFX de Fobos. Pequeñas partículas al estilo humo que rodean a estos enemigos.
- VFX de jefe final. Al multiplicarse, la copia desprende unas partículas de humo del color de la copia.
- VFX de aparición. Similar al anterior pero general para cualquier cosa que necesite aparecer en el mundo de repente y sin un color especifico.
- VFX de sueño. Partículas que se encuentran alrededor de los objetos que se pueden recoger para recargar la barra de sueño de Lulla.
- VFX de desvanecimiento. Acompaña al shader de mismo nombre y lo conforman las partículas en las que dicho shader disuelve el objeto.

#### Iluminación 
La iluminación seguirá el enfoque que se ha ido desarrollando a lo largo de todo el proceso artístico; fantasía. Se completará la sensación para con el jugador complementando el mundo con un ambiente mágico. A través del Universal Render Pipeline (URP), se personalizará la iluminación del juego de una manera eficiente para conseguir el resultado esperado. 
#### Postproceso 
En consecuencia, al apartado anterior, con URP se pueden aplicar efectos de posprocesamiento, que realzarán la calidad visual y se terminará de emparejar la atmósfera del mundo. Los sistemas de iluminación global, sombras sueves y efectos de luz volumétrica proporcionarán al juego la estética envolvente. Además, URP es escalable y se adapta a diferentes plataformas, lo que permite trabajar más cómodamente y facilita llevar el final del juego visual a un alto nivel de detalle.

### Música y sonido
#### Temas musicales 
Toda la música y efectos de sonido son de creación propia. En ‘Lullaby’ la música desempeña un papel crucial, ya que el objetivo principal del juego es conseguir la nana (Lullaby en inglés) perdida. Es por ello que, durante el desarrollo, se le concede un peso extra a todo el apartado musical, en especial la nana. 
Toda la música está diseñada para transmitir ese sentimiento onírico y fantástico del mundo a la vez que se mantiene el ritmo de un videojuego de plataformas.  
Como en el juego hay secciones muy diferentes entre ellas (plataformas, puzle, diálogos, cinemáticas con carga narrativa etc.) es muy difícil crear un solo tipo de tema que encaje para todas las situaciones, ya que además la música debe adaptarse adecuadamente. Por esto se han creado diferentes secciones o tipos de temas musicales para el juego: 
- Temas de plataformas:  En estas secciones la acción es rápida, intensa, con peligros y con acciones de movimiento y habilidad continua; por lo que la música tiene pulsos más acelerados, mayor cantidad de instrumentos y una atmósfera emocionante
- Temas de puzles: Estas secciones son más tranquilas, teniendo que pararse a pensar para resolver algunos tipos de problemas, por ello los temas en estas secciones son un pulso más lento, notas más largas, con octavas entre notas más altas y una atmósfera tranquila. Se hace para que el jugador pueda mantener la concentración y, a su vez, se mantenga acompañado sin causar distracciones.
- Temas de combate: Estas secciones son intensas con peligro y enfrentamiento constante, por lo que los temas en estas secciones son con un pulso acelerado e instrumentos relacionados a lo épico, octavas entre notas más altas y atmósfera intensa de combate.
- Temas de fondo en zonas de diálogos, cinemáticas y secuencias: Estas secciones son las más pasivas ya que el jugador casi no tiene actividad o es muy leve, por lo que los temas en estas zonas se centran en transmitir la atmósfera onírica del mundo.

La nana es el tema principal del juego la cual es tranquila. A su vez, también transmite la atmósfera fantástica y onírica del juego. El late Motiv de la nana se repite en otros temas musicales del juego, dando así una armonía a todos los temas y una personalidad.  Se quiere mantener una sincronización y que al escucharse la música se reconozca esa base común en cada uno de los temas. 

Toda la música y efectos de sonido son de creación propia. En ‘Lullaby’ la música desempeña un papel crucial, ya que el objetivo principal del juego es conseguir la nana (Lullaby en inglés) perdida. Es por ello que, durante el desarrollo, se le concede un peso extra a todo el apartado musical, en especial la nana. 

#### Efectos de sonido
El videojuego cuenta con un gran número de efectos de sonido puesto que en el equipo se les da gran importancia para mejorar el game feel. Cuando un sonido acompaña a una acción, esta se intensifica y se comunica de menjor manera con el jugador. Por ejemplo, los sonidos de pisadas al andar, un grito al caerse al vacío, sonidos al hablar en diálogos (lo cual también añade más personalidad a los personajes) o sonidos al recoger algunos objetos. Todo esto refuerza la inmersión y transmiten de manera más exacta y efectiva la acción que se está realizando. 
- OnHoverButtonSound: al pasar el ratón por encima de un botón.
- OnPressButtonSound: al hacer click con el ratón sobre algún botón.
- JumpSound: Sonido que realiza el personaje al saltar, simulando el típico ‘¡Hum!’ al hacer un esfuerzo.
- AttackSound: Sonido que realiza el personaje principal al atacar, un gruñido de esfuerzo. Tiene 3 variantes para no hacerse repetitivo y transmitir una secuencia de 3 ataques en caso de que se produzca.
- StepSound: Sonido que realiza el personaje al andar y correr (en este último caso se acelera el sonido). Cuenta con diferentes variantes para no hacerse repetitivo y otras variantes en función del suelo que se esté pisando.
- ClimbLedgeSound: Sonido de esfuerzo que realiza el personaje principal al escalar un saliente.
- DashSound: Sonido que se reproduce al realizar el air dash. Es como una andanada de viento rápida, similar al que hacen las raquetas o palos al moverlos rápido en el aire.
- TakeDreamSound: Sonido que se reproduce al recoger sueño (representación de la vida del jugador en el videojuego). Es un sonido corto y con sensación onírica, con instrumento de metal haciendo un arpegio hacia arriba.
- TakeDamageSound: Sonido que se reproduce al recibir daño. Un sonido vocal suave y corto transmitiendo ese daño mediante una queja del personaje.
- FobosDefeated: Sonido que se reproduce al derrotar a un Fobos. Un sonido que representa algo volatilizándose.
- GeorgeBarkSound: Sonido que se reproduce cuando George habla en los diálogos. Es el sonido típico de un cerdo.
- ByronBarkSound: Sonido que se reproduce cuando Byron habla en los diálogos. Es el sonido típico de una rana.
- PauseGameSound: Sonido que se reproduce cuando se pausa el juego. Es un sonido cortante y suave.
- FallSound: Sonido que se reproduce cuando el personaje principal se cae al vacío. Es un grito de Lulla con reverberación para transmitir que suena a lo lejos y cada vez escuchándose menos.
- AchievementSound: Sonido que se reproduce al conseguir completar un puzle o encontrar algo importante. Parecido a los de ‘The legend of Zelda’ al completar un enigma. 
#### Inspiraciones
Las principales inspiraciones para la música y sonidos del juego han sido Hollow Knight, Super Mario Galaxy, Final Fantasy XV, Final Fantasy X, Ori and the Will of the Wisps, The Legend of Zelda: Phantom Hourglass and Tears of the Kingdom, Skyrim, Lara Croft: Legend y el Profesor Layton. 


## 8. MODELO DE NEGOCIO 
### Mapa de empatía
#### ¿Qué piensa y siente? 
Piensa en los videojuegos como un ocio y algo que disfruta. Le gusta jugar a ellos en su tiempo libre y le encanta probar juegos creados por pequeños estudios. 
#### ¿Qué oye? 
Ve muchas redes sociales y sigue a los estudios de videojuegos que le gustan, pendiente de nuevos títulos y de recomendaciones de nuevos estudios emergentes. También escucha las recomendaciones de sus amigos y de los diferentes creadores de contenido de las plataformas de streaming. 
#### ¿Qué ve? 
Su entorno cercano también disfruta de los videojuegos y se recomiendan títulos entre ellos. También quedan para jugar y se prestan videojuegos. Ve anuncios de videojuegos en el móvil y a gente cercana y desconocidos disfrutar y hablar de los nuevos lanzamientos. 
#### ¿Qué dice y hace? 
Es una persona muy abierta en cuanto a hablar de sus gustos. Le hace feliz hablar con sus amigos sobre nuevos videojuegos que ha visto por redes sociales, y atraer a nuevos jugadores de su círculo de amigos y familiares. Entra en las plataformas digitales de juegos para ver ofertas y nuevos títulos, así como se acerca a tiendas físicas a ver novedades. 
#### Esfuerzos / Miedos
Tiene miedo de invertir demasiado dinero en un juego sin saber si le va a gustar. Trata de estar al día con los gameplays y trailers de los juegos que le atraen, pero no se decide a comprarlos fácilmente. 
#### Resultados / Beneficios 
Adquiriría un juego de un pequeño estudio y apoyaría a desarrolladores independientes. Compraría un juego con personalidad y creado con cariño. Descubriría un nuevo estudio de videojuegos al que seguir y apoyar.

### Monetización 
Buy to Play: Pago único. Se debe adquirir el juego para poder jugarlo. 

### Marketing 
1- Autopromoción: Se utilizarían las redes sociales oficiales del estudio para publicitar los productos 
2- Word of Mouth (de boca a boca): que se use como método de marketing indirecto. Sería una forma de promoción el juego sin que el propio estudio controle la manera en que se habla del juego.  
### Modelo Canvas
<p align="center">
<img src = "https://github.com/OrigamingCreationsProjects/Art/blob/main/Sketches/GDD_images/ModelCanvas.png" width = "auto" height = "250">
</p>

## 9. ANÁLISIS MDA
### Experiencia de juego 
#### Fantasía
La descripción de la estética principal de Lullaby resalta la ambientación en un mundo completamente fantástico. Desde el inicio de la partida, el jugador se sumerge en un entorno lleno de elementos que no existen en la vida real. La paleta de colores contribuye a transmitir una sensación onírica, y el control de una pequeña oveja bípeda añade un toque único. La narrativa se desarrolla con la tarea de superar obstáculos y luchar con una almohada como arma para encontrar la nana perdida.
Las mecánicas de movimiento refuerzan la atmósfera fantástica, ya que la oveja se desplaza a dos patas, realiza saltos mortales y utiliza un airdash para alcanzar distancias mayores. La interacción con criaturas fantásticas desconocidas, venciéndolas con una almohada, añade un elemento de fantasía y creatividad a la experiencia de juego.
#### Sensación 
La sensación es una estética prominentemente presente en Lullaby, lograda a través de una banda sonora evocadora que despierta sentimientos alegres y emotivos. Se complementa con un apartado artístico que sumerge al jugador en un mundo onírico.
Las mecánicas clave que contribuyen a esta estética incluyen el control de cámara en tercera persona, que proporciona una visión total y abierta del mundo, el toon shader diseñado para otorgar un aspecto adorable, un sistema de sonido dinámico que emite sonidos en respuesta a ciertas acciones, un sistema de partículas que genera efectos visuales al realizar acciones específicas, y un sistema de control de cámaras dinámicas que se activa al entrar en un diálogo o al iniciar una cinemática. Estas características se combinan para inmersar al jugador en una experiencia emotiva y visualmente cautivadora.
#### Narrativo
La narrativa tiene gran peso en Lullaby al querer transmitir emociones al jugador tales como la superación de la pérdida, y del cambio.  
Algunas de las mecánicas que consiguen esta estética son el sistema de diálogo con emociones dinámicas en relación con los personajes, el estilo del texto en relación con lo que se quiere transmitir en ese momento, además de un sistema de cinemáticas para controlar la atención del jugador en ciertos momentos.
#### Desafío 
El desafío es una estética muy presente en Lullaby mediante el uso de puzles a lo largo del transcurso del juego que retan al jugador a usar su ingenio para superarlos y avanzar en la historia.  
Las mecánicas que consiguen esto son el uso de botones para accionar ciertos mecanismos, el sistema de combate para conseguir objetivos necesarios en el avance del juego etc. Además, el sistema de plataformas y obstáculos, repartidos a lo largo del mundo, ponen a prueba las habilidades mecánicas del jugador constantemente.
#### Descubrimiento 
En Lullaby el jugador está en un constante descubrimiento porque se le van mostrando diferentes mecánicas que puede utilizar a lo largo del juego, enseñándoselas poco a poco y dejando tiempo para que las asiente y practique antes de enseñar la siguiente. Además, también puede ir descubriendo enemigos nuevos, escenarios completamente diferentes y personajes con los que interactuar. 
Para ampliar, en cuanto a la dinámica del escenario, que es diferente a medida que el jugador avanza, hace que este ponga en práctica las mecánicas enseñadas y que se atreva a descubrir otros caminos y otras formas de ir superando el nivel.
#### Coleccionismo
La incorporación de objetos coleccionables en Lullaby permite al jugador embarcarse en la búsqueda y recopilación de estos elementos para completar la colección. Esta mecánica añade un elemento adicional de exploración y desafío, motivando a los jugadores a interactuar más profundamente con el mundo del juego para alcanzar el objetivo de obtener todos los objetos coleccionables.
La mecánica que transmite esta estética es la presencia de un álbum en el que aparecerán los objetos recogidos tales como trozos de una foto o letras de canciones.

 ## 10. POSTMORTEM
### ¿Qué ha ido bien?  
Es importante descubrir o discernir que actividades o elecciones han sido las correctas. Si no somos capaces de llevar a cabo esta acción de forma correcta, no podremos asegurar la misma decisión en el próximo videojuego.
  
### Flujo de correcciones  
A lo largo del proyecto, el rumbo va virando para intentar encontrar el rumbo adecuado y “llegar a tierra” en el menor tiempo posible y con el mayor número de viveros en la bodega del barco. Tener en consideración que acciones o tareas fueron acertadas, las cuales fueron corregidas de forma exitosa y por el contrario qué decisiones fueron erróneas y produjeron malestar en el grupo y resintieron el producto final.  

### Feedback o retroalimentación externa  
Esta sección quiere poner en valor las opiniones externas al grupo de trabajo. Normalmente, cuando el videojuego o proyecto no está lo suficientemente maduro es aconsejable realizar una pequeña encuesta de valoración del juego. En este momento del proyecto es interesante de obtener esa retroalimentación de gente cercana al equipo y que no sea claramente una competencia en un futuro cercano. Por ejemplo, familiares, amigos o incluso compañeros de trabajo ajenos al proyecto actual pueden ser un buen ejemplo. Cabe destacar que las críticas no son malas, siempre y cuando, estas sean constructivas.  

### ¿Qué se podría haber mejorado?  
Es evidente que nada es perfecto en esta vida. Por este motivo es necesario encontrar soluciones a los problemas surgidos. ¿Qué quiere decir esto? No vale de nada decir que algo ha salido mal, si no tenemos una posible solución. Es crucial que seamos auto crítico con nosotros mismos y con nuestro equipo, pero también debemos de ser lo suficientemente maduros para encajar los golpes del camino y buscar soluciones. 

Se basa en dos fases. La primera consta de realizar las dos preguntas de forma individual, es decir, ¿Qué cosas han ido bien? ¿Qué cosas habría que mejorar? La idea es dejar por escrito (el papel todo lo aguanta...) todo lo que pensemos. No vale el decir ya lo he pensado. ¿Por qué no vale? Porque ahora mismo el proyecto o videojuego lo tienes muy presente y reconoces los aciertos y errores de forma fácil y sencilla. Sin embargo, cuando el tiempo vaya pasando no te acordaras de todos los detalles, mientras que si lo tienes escrito esto no te pasará, porque todo estará detallado en tu documento.  
La segunda parte se trata de ponerlo en común con el resto del equipo y realizar un documento final que resuma de forma, lo más pormenorizada posible, todos los comentarios y pensamientos de los integrantes del equipo. No hace falta poner nombres, puedes hacer un documento anónimo y poner el nombre del rol que has llevado en ese proyecto, por ejemplo: desarrollador1, artista2, etc. Finalmente, el equipo tendrá un documento robusto que podrá ser consultado en un futuro corto-largo plazo, donde se detallaran qué cosas pueden ayudar al equipo a, nuevamente, alcanzar el éxito. 
### Integrantes

#### Alex 
**Rol: Lead Programmer, Lead Designer, Gameplay Designer, Creative Director.**
**¿Qué ha ido bien?**
Creo que una de las cosas que mejor hemos hecho ha sido la división de tareas y el reparto de roles. Aunque algunas personas puedan ayudar a otras en sus áreas, las tareas se han repartido en base a los puntos fuertes de cada integrante y eso ha hecho que la calidad de los productos de cada uno haya sido lo mejor posible. 
Otro aspecto muy importante para resaltar ha sido que la calidad del trabajo ha superado las expectativas que teníamos del proyecto al comenzarlo. 
Por mi parte, considero que la programación es muy robusta, se ha conseguido un videojuego que se asienta sobre un código sólido y modulable, abierto a futuras modificaciones y ampliaciones, lo cual será provechoso de cara a la versión Gold. 
El diseño de las mecánicas ha resultado en un conjunto de estas muy divertido y orgánico para el usuario, incluso para los propios desarrolladores. 
En cuanto a la comunicación, un aspecto a alabar ha sido la facilidad con la que desde programación se ha pedido a arte los assets con las especificaciones justas y necesarias para no tener que estar modificándolos y adaptándolos continuamente. 

**Flujo de correcciones**
Una de las cosas que ha ido mal y que no quisiera repetir en futuros proyectos es la manera de manejar al equipo que he tenido, ya que en ocasiones debido al estrés del desarrollo he podido dirigirme a ellos de forma brusca y sonar más duro de lo que en realidad quería. 
También he sido muy cabezota con algunas de las ideas que tenía y que no quería cambiar, lo que ha resultado en que no he permitido que mis compañeros tuvieran toda la libertad de la que deberían haber dispuesto desde el principio. Sin embargo, este aspecto ha cambiado a lo largo del desarrollo y poco a poco he abierto la mente a ideas que en un principio habría descartado. 
Otro aspecto en el que he rectificado ha sido la comunicación a tiempo. Hemos conseguido transmitir la información en el momento justo y poder adaptarnos a lo que el resto había hecho. 
Retroalimentación externa 
La gente cercana ha alabado en especial la calidad del proyecto para el tiempo del que disponíamos y la cantidad de personas que éramos. También han dicho que el juego era muy divertido de jugar y que te incitaba a continuar jugando más rato o a pasártelo más veces poniéndote retos tú mismo. 
Sin embargo, algunas de las críticas que nos han realizado sobre programación y mecánicas han sido orientadas hacia la falta de información a la hora de saber qué consecuencias tiene cada acción. 
Otra crítica muy repetida ha sido la velocidad de Lulla a la hora de andar y correr, ya que decían que el juego se hacía lento. Esto se sumó a que el control de correr en mando era muy tedioso de utilizar, por lo que preferían no correr y se hacía aún más lento. 

**¿Qué se podría haber mejorado?**
De cara a futuras entregas y proyectos tendríamos que mejorar la comunicación, ya que ha sido muy frecuente pero no era de calidad. Esto ha hecho que se perdiera información y que hubiera cosas que no llegaban a tiempo. 
Otro aspecto para mejorar es el cumplir con los objetivos de tiempo asignados a las tareas, ya que prácticamente nadie ha llegado con todas las tareas que se propusieron para la Beta a tiempo o completas. 
Por último, de mi parte, creo que habría sido mejor ir haciendo pequeñas builds para que mis compañeros probaran mecánicas y me dieran feedback a medida que las desarrollaba, y así no hubiera tenido que arrastrar errores o hacer que otros compañeros editaran sus partes cuando yo arreglaba las mías más tarde. 

#### Álvaro
**Rol: Level Designer, Script Writer, Community Manager, UI Assistant.** 
**Qué ha ido bien**  
La comunicación en equipo ha sido buena, las reuniones semanales contribuyeron a que estuviésemos al día a pesar de que ocasionasen inconvenientes también. La herramienta de Trello supuso una ayuda respecto a la organización del equipo y a ver qué faltaba por hacer.  

**Flujo de correcciones** 
Tras entregar la versión Beta de Lullaby me di cuenta de que debería haber sido más proactivo respecto a la comunicación con el equipo, con el fin de que se testeasen los niveles antes, ya que por retrasos de comunicación en este aspecto se tuvieron que cambiar partes del nivel que estaban terminadas desde hacía ya varias semanas. Por lo que se podría resumir en menos cantidad de comunicación pero que fuese más efectiva, comunicarse directamente con quien tenía un modelo terminado para sustituirlo en el grayboxing, entre otras cosas. También, al salirme de mi zona de confort y tener que adaptarme a nuevas herramientas y mecánicas fui muy optimista con la organización de tiempos, además de que dependía del visto bueno de muchos miembros para avanzar. 

**Retroalimentación externa**  
Mis compañeros coinciden en que las flaquezas que mencioné fueron ciertas, pero a su vez me animaron a preguntar siempre que sea necesario para que en vez de tardar más tiempo en averiguar cómo funciona algo que se pudiera resolver más rápidamente. 

**Qué se podría haber mejorado**  
Comunicación efectiva: A veces por la cantidad de mensajes era complicado ver si había alguno para ti, lo que hacía que no estuviésemos coordinados, lo que entorpeció el trabajo la última semana de desarrollo de la beta. Además de este punto desenbocan el resto de los problemas, directa o indirectamente.  
SOLUCIÓN: De cara a la versión gold iniciar el proceso de sustitución de los modelos que quedan antes, y comunicarnos con los encargados de las tareas cuando sepamos que es una tarea dependiente de otra.  

#### Betu
**Rol: Level Designer, Script Writer, Character Designer**  
**¿Qué ha ido bien?**
-La organización en Trello, puesto que a pesar de que algunos de los miembros no estábamos acostumbrados, al entrar en el flujo de trabajo hace las cosas más sencillas y permite tener monitoreado el trabajo de cada uno, proporcionando una herramienta para el seguimiento del desarrollo global del proyecto. 
-Las reuniones semanales, que nos han permitido revisar el trabajo global de manera regular, dividir la producción en tareas semanales. 
-El compromiso y la constancia del equipo, con todos los miembros dando su mayor esfuerzo para intentar sacar el mejor producto posible. 

**Flujo de correcciones** 
En el caso específico del grayboxing, siento que hubo fallos en el flujo de correcciones puesto que los niveles, a pesar de estar muy avanzados, se enseñaron al resto del equipo muy tarde. Esto dificultó y apresuró la corrección del nivel, lo que a su vez se tradujo en un aspecto poco pulido en muchos lugares en pos de conseguir un producto funcional. Todo esto se hubiese solucionado de antemano si hubiese pedido más feedback a medida que realizaba el nivel, y en resumidas cuentas el problema radicó en la falta de comunicación. 

**Feedback externo** 
A pesar de que la gente disfrutó del juego y la retroalimentación fue en su mayoría positiva, muchas de las entradas de los bugs report estaban relacionadas a las flaquezas del nivel mencionadas anteriormente. Esto, al contrario de desanimar, funcionó para mí de cara a la Gold como un punto de vista distinto desde el que abordar el diseño de nivel y la integración de elementos artísticos en el mismo.

**¿Qué se podría haber mejorado?** 
La comunicación entre ramas de trabajo, especialmente la de arte-diseño de nivel, ha fallado de cara a la beta, ya que en este sprint tanto las malas prácticas a la hora de crear prefabs y la integración del arte han provocado problemas y retrasos que han afectado a las dos ramas de trabajo. 
Además, haciendo aún hincapié en la comunicación entre miembros del equipo, la experiencia hubiese sido más disfrutable si el feedback que sí hubo de las otras partes fuese traído de una manera más calmada y pacífica, ya que, en muchas ocasiones, no apetecía pedir una opinión pensando en que sería una negativa rotunda, especialmente en el caso de ideas propias. 
Fuera de esto, también debí haber dedicado más tiempo en organizar mis tareas de forma adecuada en el Trello, pues si bien lo utilizaba, no lo hacía aprovechando al máximo lo que ofrece.  
SOLUCIÓN: De cara a la Gold probar las texturas y modelos en el nivel en cuanto están hechos, y probar el nivel a medida que se van haciendo cambios, comunicando el progreso a los demás miembros del equipo y logrando así perder menos tiempo en errores que podrían haberse evitado.

#### Gema
**Rol: Environment Artist, Assets Artist, Environment Lightning and Texturizer** 
**¿Qué ha ido bien?**
- Los elementos y plataformas que se iban a utilizar han gustado en general tanto a los integrantes del grupo como a las personas externas que han jugado el juego. Se han hecho comentarios acerca de la personalidad que había adquirido el mundo y lo bien integrado que estaban los elementos iniciales 
- Las reuniones semanales nos han ayudado a alcanzar objetivos y a mantener un ritmo de trabajo. Además, nos ha permitido hacer un seguimiento de trabajo de cada uno de los integrantes.  
- La constancia y el esfuerzo que le han puesto todos. La ayuda de todos sobre todos, el tener miembros en el equipo multidisciplinares hizo que el ayudar a un compañero fuese rápido y mantuvo el ritmo de trabajo. 
 
**Flujo de correcciones** 
Creo que, aunque los colores del mundo estuvieron mandándose para comprobar el tono, el hecho de no probarlo en el mundo con los diseñadores de niveles y probar una combinación de colores adecuada provocó que, al final, solo hubiese un color en el mundo.  

**Feedback externo** 
Aunque el color monocromático de la beta ha sido un error, a las personas en general le ha gustado la ambientación y el cuidado de las texturas.  
Aunque siempre había alguien dispuesto ayudar se ha estado de acuerdo en general que la restricción artística y creativa que ha supuesto el proyecto ha afectado en gran medida a los bloqueos y los parones de arte. Aun así se ha solventado con la mayor rapidez posible y siempre se ha animado a mantener una decisión competente dirigida por la persona que tenía ese rol principal
  
**¿Qué se podría haber mejorado?**
Podría haberme duplicado el proyecto yo misma para poder probar las texturas poco a poco y hacer las pruebas de color en el mundo directamente.  
De cada a la Gold mejorar no solo la coloración del mundo son también incluir más variedad de texturas al mundo para darle más personalidad. 
Creo que también podría haber tenido más comunicación con mis compañeros que sirven de enlace a mi trabajo directamente. Es decir, supervisar que llegaran bien las Uvs de las texturas o que se importaban en Unity correctamente.  
Mejorar la gama cromática de la paleta ya que, en general, todos los colores tienen poco brillo y saturación. 
El haber sido la encargada de una red social durante la Beta tampoco ha sido sencilla porque, aunque teníamos material para empezar se fue retrasando hasta casi el final de la fase. 
SOLUCIÓN: De cara a la siguiente entrega adoptar más el rol de supervisión de arte para poder encajar con más facilidad las piezas y no retrasar el trabajo de los programadores.  
Cambiar los colores de la paleta facilitará que el proyecto obtenga la sensación de viveza que se había perdido en la Beta. 

#### Mónica
**Rol: 3D artist and animation** 
**¿Qué ha ido bien?**
Los modelos del mundo creados fueron bien recibidos a pesar de la ausencia de decoración. En general, la comunicación con el resto del equipo fue efectiva, especialmente gracias a las reuniones semanales y la herramienta Trello.  

**Flujo de correcciones** 
Considerando las exportaciones de Blender a Unity, habría sido necesario realizar pruebas de todos los modelos en Unity antes de cargarlos como definitivos en Github. Esto habría permitido ahorrar tiempo a los otros compañeros y corregir oportunamente posibles problemas.  
Retroalimentación externa 
Por lo general todo fueron buenas críticas, a nivel funcional el juego tenía pocos bugs y estéticamente si se echó en falta decoración que se añadirá para la gold. 

**¿Qué se podría haber mejorado?**
Como mejoras se ha aprendido que hay que exportar con la escala correcta y aplicar las trasformaciones antes de hacer el skinning de los personajes. Por lo general la comunicación ha sido correcta, pero si se ha tenido que mejorar comunicación entre ramas en ocasiones.  
Así mismo el tiempo jugó mucho en nuestra contra puesto que no ajustamos bien las tareas acordes a este y esto provocó retrasos y agobios. 
SOLUCIÓN  
Como solución para la siguiente entrega ajustar los tiempos de las tareas, que sean tiempos asequibles, probar los modelos en unity antes de pasarlos como definitivos y aumentar la comunicación con el resto de los integrantes sobre todo con la parte de level desing.  

#### Alicia
**Rol: UI Designer, UI Artist, Tecnical Artist, Project Coordinator, Programmer Assistant**
**¿Qué ha ido bien?**
Toda la parte de interfaces ha gustado en general a la gente. Ha sido buena idea seguir un mismo concepto a lo largo de las interfaces y la UI, ya que consigue integrar las pantallas y que no saquen al jugador de la inmersión en el videojuego. 
En esta entrega de la versión Beta he funcionado también como nexo de unión entre arte y programación, lo cual ha mejorado la comunicación entre las dos partes. Esto ha sido beneficioso para dejar claro qué especificaciones necesitaba una parte y cómo la otra podía ajustar su trabajo para no tener que empezar de nuevo.
 
**Flujo de correcciones** 
Creo que, en cuanto a interfaces de usuario, todo el flujo de correcciones se realizó de forma adecuada. Se realizaron pruebas internas y se pidió consejo al resto de integrantes una vez ya había un diseño boceteado de las pantallas, se realizaron los cambios que se consideraron oportunos y se pasó al diseño final, dejando algunos elementos a elegir entre varias opciones ya diseñadas al resto del grupo. Con esto se montaron las pantallas finales y se integraron en el juego. 
En la parte de shaders y VFX, en esta entrega se llegó con muy poca cantidad de trabajo en este ámbito, por lo que no se pudo hacer un gran flujo de correcciones. Sin embargo, algunos de los efectos tenían ligeros fallos, por lo que se editaron sobre la marcha según iban surgiendo, lo cual no es muy eficiente. 

**Feedback externo** 
La mayoría de las personas que probaron el juego cercanas al grupo, pero ajenas, dijeron que las interfaces estaban bien, salvo algún bug relacionado con las resoluciones o ciertos navegadores específicos. 
Algunas quejas sobre mi área de trabajo fueron el escalado de las texturas, el cual se podría haber resuelto con un shader triplanar, y la falta de sombras arrojadas en el mundo. Otras quejas fueron sobre la falta de algunas pantallas como los créditos, y sobre la ausencia de efectos especiales que dieran vida al juego. 

**¿Qué se podría haber mejorado?** 
De cara a la entrega de la fase Beta de Lullaby creo que debería haber aprendido a medir mejor los tiempos de mis tareas y no subestimar cuánto me llevaría completarlas al 100%. 
También creo que el hecho de haber estado intentando ayudar y supervisando a otros compañeros para que las cosas fluyesen entre todas las áreas de trabajo ha hecho que dejase mis propias tareas de lado algunas veces. Esto, sumado a que no he querido delegar partes de mis actividades para poder ayudar yo a otros ha hecho que mi carga de trabajo aumente y me estresara más de la cuenta. 
SOLUCIÓN: De cara a próximas entregas me gustaría ponerme límites de tiempo más realistas y saber desde el primer momento si tengo rol de organización de equipo, para así adaptar mis tareas consecuentemente. 
A rasgo general para todos: Fechas con valores largos, que sean realistas. Avisar con tiempo si no se va a llegar con algo y saber delegar 

## 11. EQUIPO E INTEGRANTES
El equipo está formado por seis integrantes y una persona externa asociada al proyecto encargada de la música y los efectos de sonido. 
Cada integrante interno cuenta con varios roles dentro del proyecto y se encarga de una parte del juego. 
### Alejandro Campbell Legarreta
- Lead Programmer, Creative Director & Gamplay Designer. 
Encargado de la programación de gameplay, IA, sonido y sistemas del juego. Además, toma responsabilidades en el diseño narrativo y diseño de gameplay. 

### Alicia Enríquez Martínez 
- Technical Artist, UI Designer & UI Programmer.
Encargada de los efectos visuales y los shaders del juego. También es la resonsable de diseñar y programar las pantallas e interfaces de juego. Diseñadora del isotipo y logotipo. Artista conceptual de Lulla

### Álvaro Izquierdo Fernández 
- Level Designer, Localizator & Community Manager
Encargada de los efectos visuales y los shaders del juego. También es la resonsable de diseñar y programar las pantallas e interfaces de juego. Diseñadora del isotipo y logotipo. Artista conceptual de Lulla
Encargado del diseño de niveles y grayboxing. Responsable de localizar el juego al idioma inglés. Lleva las redes sociales de la empresa (Instagram, Twitter y Youtube).

### Betuel Jivandec 
- Level Designer & Scriptwriter. 
Encargado del diseño de niveles y grayboxing. Escritor del guión del juego y diseñador conceptual de personajes. 

### Gema López-Pozuelo Senderos 
- Environmental Artist, Web Designer & Community Manager. 
Encargada de diseñar el estilo visual de los escenarios y los objetos del mundo, artista de iluminación y postproceso. Encargada del diseño de la página web de la empresa y del proyecto. Lleva las redes sociales de la empresa (Tik Tok). 

### Mónica Varas García 
- 3D Artist & 3D Animator. 
Encargada de modelar, riggear y animar los enemigos del juego. Modeladora de los escenarios y objetos del juego.

### Iván García Martínez  
- 3D Art Assistant.  
Encargado de ayudar con la creación de arte 3D y de aconsejar y guiar en los procedimientos de arte 3D. Persona asociada al proyecto a tiempo parcial. 

