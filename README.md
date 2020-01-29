Nueva información: **Exploit del modo avión para salir de las raids**: añadida 05/01/2020

# **Bienvenidos a la MEGAGUÍA del RNG Abuse y varios exploits de Pokémon SW/SH en Español.**

Esta guía ha sido desarrollada por Lay (@Layshiba) para uso y disfrute de toda la comunidad de Pokémon de habla hispana. Si se plantean dudas ya sea por twitter a la cuenta mencionada arriba y/o en el discord (discord.gg/QFRSmXk) se intentarán paliar a la mayor brevedad, ¡gracias por vuestra paciencia!

En esta guía os expondré de la manera más breve y concisa posible los pasos a seguir en el proceso de conseguir una Raid shiny de Pokémon Espada y Escudo explotable, es decir, una raid la cual, cada vez que se resetea, tiene un pokémon shiny distinto. De esta manera se pueden conseguir shiny **todos** y cada uno de los pokémon que haya en el den, **incluídos los Pokémon G-Max** si los hubiese. Este es un proceso tedioso y largo, pero muy asequible. 

Los Pokémon generados son totalmente legales ya que no hay ninguna manera física de alterar el contenido de un Den o Nido salvo esta que vamos a explicar (por el momento). Si bien este es el método de obtención más tedioso de conseguir shinys, es el más efectivo y el más rápido de todos los que hasta ahora prometen G-max shiny.

### IMPORTANTE: En esta guía se explica el método en su expresión más "vanilla", es decir, no se utilizan métodos de obtención de código de seed y comprobación de frames restantes para raid shiny, puesto que conlleva utilizar en todos los casos algún tipo de Custom Firmware.

Primero de todo: 
## **Cómo funcionan los nidos en Pokémon: Espada y Escudo**

Los nidos funcionan por criptocódigos, generados cuando la raid es creada, o, en su defecto, cuando se lanza un Trozo Deseo dentro del nido y por ende se genera un nuevo nido. A este criptocódigo lo llamaremos semilla o _**"seed"**_. En el momento que la seed se genera, se decide en cual frame (día) saldrá la raid shiny. Este número es totalmente aleatorio, utiliza la probabilidad shiny base del juego **SIN APLICAR AMULETO IRIS**, por tanto, dicho número puede ser 20, 83, 562 o 15639, dependerá de vuestra suerte únicamente. Las seed se pueden **cambiar** batiendo la raid o echando un Trozo Deseo a otro nido. 

Los nidos guardan del frame en el que se encuentran **TODO**: la especie, los stats, la condición de shiny, etc.. del Pokémon, es decir, que si sales y entras del juego, encontrarás siempre el mismo Pokémon en esa raid, porque está **fixed**. Bien, una vez entendemos esto, viene lo complicado:

El juego también fixea/guarda TODA la información acerca de los siguientes 3 frames de la raid. A partir del 4 frame, la especie del Pokémon se vuelve aleatoria, sin embargo su cantidad de IVs, stats en general y **la condición de shiny** se mantienen guardadas. Por tanto, si guardamos la partida 3 frames antes de que sepamos que sale un shiny, el juego no guardará nunca la información de **qué especie es el shiny**, creando la posibilidad de un abuso en el RNG del juego.

**Por ejemplo:** Imaginemos que nuestra raid shiny se va a celebrar en el frame 435. Si guardamos la partida en el frame 432, es decir, 3 frames antes, nuestro shiny estará permanentemente cambiando de especie.

Una vez entendemos cómo funcionan los nidos, vamos a hablar de: 
## **El exploit de los días.**

Cada vez que el juego detecta que estás jugando a las 00:00 am / 01:00 am, los nidos del Área Silvestre se resetean, dando pie a nuevas raids para el jugador. A este "reset" lo llamamos "Avance de Frame", **1 frame = 1 día.** Hay otra manera distinta de avanzar frames que no requiere esperar a cada noche a la 1:00 am, **cambiar la fecha de la consola**. Si estamos dentro de una raid, ya sea buscando jugadores (online u offline, **preferiblemente offline para no molestar a otros jugadores** y agilizar un poco el proceso además) y la consola detecta un cambio de fecha (un día en avance, como mínimo) las seeds de los nidos de toda el Área Silvestre cambiarán con el frame, **EXCEPTO** la seed de la raid en la que tú estás participando, que mantendrá la seed y avanzará de frame al mismo tiempo. Hay que comentar que pasar los frames no solo sirve para las raids, sirve para resetear los Pokémon salvajes/Árboles de Bayas/Objetos del suelo/Vendedores del Área Silvestre, así como la lotería (**Exploit de las MasterBall**)

Ahora bien, hay una manera bastante más reciente y rápida de pasar los días, que se tarda unos 3-5 minutos en generar, pero a la larga te ahorra bastante tiempo, unos 10-20 segundos por reset, el **método VS**

## **Método VS**

### **IMPORTANTE: PARA ESTE MÉTODO ES NECESARIO TENER SUSCRIPCIÓN A NINTENDO SWITCH ONLINE**

Si eres un/a Shiny Hunter, y no juegas al competitivo de Pokémon, o sólamente te centras en uno de los dos tipos de combate (Combates individuales/Combates Dobles), hay una manera mucho más rápida de pasar los frames en el juego, y es siguiendo estos pasos:

1. Entras a VS desde el menú de inicio, y seleccionas "Combatir"
2. Selecciona combate individual/doble (según lo que más te convenga) y crea un equipo o selecciona uno de préstamo.
3. Al encontrar contrincante, selecciona tres/cuatro Pokémon aleatorios y en el primer turno de combate, **retírate**
4. Pulsa B repetidamente hasta que abandones el menú VS
5. ¡Felicidades! Ahora puedes pasar de frame sin necesidad de estar dentro de una raid.

También se ha descubierto que se puede realizar este exploit en los combates amistosos, poniendo el modo avión al estar en la pantalla de las tarjetas de entrenador (y volviéndolo a quitar al instante) pero puede fallar en comparación a los combates clasificatorios.

Para pasar de frame, simplemente visita una raid, recoge los vatios, cambia la fecha **SIN** buscar jugadores **ni salir de internet**, si sales o buscas, harás que el exploit deje de funcionar.

## Llevando a cabo el método de los 3 días

Una vez nos situamos en el nido que queremos explotar (por ejemplo, el Den 97, que pertenece al Gigamax Charizard), y hemos conseguido mediante el exploit del SoftReset (explicación de este exploit más adelante) nuestra raid dorada, dejaremos que el juego guarde la partida y comenzaremos la búsqueda.

1. Avanzaremos 3 frames hacia delante. (Por ejemplo, si comenzáramos en 1 de Abril, avanzaríamos hasta el 4 de Abril).
2. Una vez en el día 4, comprobaremos si la raid es shiny. **SI NO ES SHINY**, continúa leyendo. **SI ES SHINY**, ve al paso 1b.
3. Cierra el juego nada más empezar la raid no shiny y vuelve a iniciarlo. Una vez en el juego comprobarás que vuelves a tener la raid del día 1 de Abril (puesto que aunque los frames hayan avanzado, no hemos guardado partida en ningún momento)
4. Avanza 1 frame (5 de Abril) y guarda la partida.
5. Repite desde el paso 1 hasta obtener un shiny.

1b. ¿Tienes un shiny? Bien, cierra el juego al entrar en la raid y vuelve a iniciarlo.

2b. Ahora volverás a estar 3 días antes del shiny, y si los avanzas, obtendrás un shiny de distinta especie al anterior.

3b. Repite todas las veces necesarias


Cabe recalcar que el host de la raid nunca obtiene el Pokémon, a no ser que haya una persona capturándole siempre los suyos en las raids. Si el host lo captura y guarda la partida (o tiene el autoguardado y sale de la raid o intercambia con alguien) se perderá la raid shiny.

## Consejos y FAQ una vez obtienes una raid shiny

1. Si es una raid Gigamax, sigue haciendo incursiones hasta que te salga el pokémon deseado, merecen mucho más la pena que quedarse con Pokémon normales que puedes obtener mediante otros métodos como la crianza.
2. Desactiva el autoguardado si no lo tenías desactivado ya.
3. Cuando invites a otras personas a las incursiones, abandónalas tras hacer el primer turno, de manera que tu personaje se transforma en un bot en la raid y tú puedes preparar la siguiente raid.
4. Una vez consigas el Gigamax, o, en su defecto, el Pokémon más complicado del Den, puedes decidir si guardar partida (recomiendo que sí lo hagas, son muy puñeteros a la hora de salir) y quedarte con el Gigamax Shiny fixeado, para hacerlo cuantas veces quieras/necesites. **EDIT: Nuevo exploit al respecto de este punto, explicado en el último apartado.
5. Cuando decidas finalizar la raid y capturar al Pokémon, puedes usar cualquier Pokéball (incluída la EnteBall, con ratio negativo). Al ser el host de la raid (**raids que no son de evento**) tienes 100% de probabilidad de capturar.
6. No, no te van a banear por usar el método de los tres días, los abusos de RNG son totalmente legales a ojos de Game Freak.

## El exploit del SoftReset

No creo que sea muy necesario explicar este exploit, puesto que lo sabe todo aquel que ha jugado a Pokémon, pero básicamente al usar un Trozo Deseo, el tiempo que tarda el cuadro de diálogo en decirte que está guardando la partida puedes ver si la raid va a ser roja o morada, y por tanto darle al botón Home y reiniciar el juego, de modo que nunca gastarás el Trozo Deseo hasta que tú quieras.

## El exploit del modo avión

Si bien puedes guardar al conseguir el pokémon más complicado del nido y repetir hasta que te canses, hay nidos en los que el segundo pokémon más complicado a veces tarda más en salir que los propios jefes de nido (como los gigamax). Por tanto, al guardar en el jefe de nido perdíamos la oportunidad de conseguir absolutamente todos los pokémon del nido shiny. Ahora esto ha cambiado.

Este método es algo más complicado de hacer, puesto que hay que ser rápido, y cualquier missclick o distracción puede hacer que pierdas el gigamax y lo tengas que volver a buscar. Pero como estamos aquí para informar, encantada os lo explico:

Una vez consigues el gigamax, **NO GUARDES**, invita a jugadores, para explotar la raid, y si puedes, coméntales que en el primer turno esperen a que tú hagas una acción antes de hacer ellos (si eres la última persona en atacar no te dará casi tiempo a hacer este método y perderás el pokémon/giga casi seguro).

**SWITCH EN MODO PORTATIL / SOBREMESA CON WIFI** Al hacer tu acción, mientras el cuadro de diálogo te indica "Conectando, por favor espera", mantén el botón "Home" pulsado y pon la consola en modo avión (Si está en el dock, quítala del dock o no podrás poner el Modo Avión). Al momento recibirás una notificación de que has perdido la conexión y el juego te echará de la raid.

**SWITCH EN MODO SOBREMESA CONECTADA POR CABLE** Al hacer tu acción, mientras el cuadro de diálogo te indica "Conectando, por favor espera", quita la consola del dock y recibirás al instante una notificación de que has perdido la conexión. El juego te echará de la raid y la volverás a tener preparada para volver a hacerla.

Este método, además de no obligarte a guardar y lockear al shiny más complicado, agiliza bastante el reseteo de las raids a los host.

Si has llegado hasta aquí, has terminado lo que hay hasta este momento en la guía. Todas las dudas las puedes consultar por las vías especificadas al principio de la guía, **Twitter/Discord**. Gracias por el apoyo y:
### HAPPY SHINY HUNTING! <3
