<img src="./UdG_dues_linies_centrat_blau.png" alt="Logotip UdG" width="150">

| *Grau en Disseny i Desenvolupament de Videojocs*
----
|  **Programació de dispositius mòbils**

&nbsp;


Projecte 1. Pautes i criteris d'avaluació
============

Es permetrà canviar alguns d'aquests requeriments per uns altres d'equivalents, prèvia consulta al professor.

Temàtica
--------
Criatures fantàstiques.


Tecnologies
-----------
Android natiu. Kotlin i Jetpack Compose.

Java i Views no!

Equips
-------
2 o 3 persones (implica diferent complexitat).

UI
----------------------
Wireframes: clars, comprensibles, consistents. Digitals o sobre paper.

Pantalles: Segueixen les pautes dels wireframes. Bona estètica i disseny general.


Arquitectura
------------
Imprescindible separar UI de les dades. Poden utilitzar-se [capes](https://en.wikipedia.org/wiki/Multitier_architecture), [MVC](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) o similar.

Més informació a [Guide to app architecture](https://developer.android.com/topic/architecture).


Programació
-----------
Es revisarà que el codi sigui net. Concretament:
1. Noms de variables i funcions ben escollits, indiquen funcionalitat.
2. Funcions fan 1 sola cosa.
3. El codi s'entén fàcilment sense comentaris, o amb pocs comentaris. No hi han comentaris innecessaris.
4. Sense codi duplicat.
5. Codi intentat.
6. Funciones/mètodes curts (idealment 10-20 línies) i no tallades artificialment.
7. Processament d'error correcte, utilitzant excepcions.

Més informació a _Clean Code: A Handbook of Agile Software Craftsmanship_ by Robert C. Martin


Requeriments funcionals
----------
- Mostrar dades de criatures fantàstiques: nom, descripció, foto, tipus, localització, atributs.
- Mostrar dades dels tipus: nom, descripció, criatures associades.
- Cerques de criatures i de tipus per nom.
- Pels equips de 3 membres:
  * obtenció de les dades d'un servidor. 
  * Ús d'una tecnologia dissenyada per a connexions lentes i/o inestables, com API Rest o GraphQL.
  * Es pot utilitzar un de ja creat, com https://pokeapi.co/


Requeriments no funcionals
-------------
- S'adapta a diferents mides de pantalla i disposicions (horitzontal i vertical).
- Desplegat a Google Play (pot ser aquest projecte o els propers).


Seguiment
---------
- Es mostren els progressos setmanalment.
- Ritme de creixement de l'aplicació adequat.
- Demostració, per tots els membres de l'equip, del coneixement dels detalls de la implementació.


Lliuraments
-----------
Seguir les instruccions marcades a les tasques del Moodle.

Qualificació
---------------------

- UI: 10%
- Arquitectura: 10%
- Programació: 20%
- Requeriments funcionals: 20%
- Requeriments no funcionals: 10%
- Seguiment: 30%

