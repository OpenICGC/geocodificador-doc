# Geocodificador ICGC
La **geocodificació** és el procés de convertir adreces postals, noms de lloc o punts d'interès a coordenades.

El **Geocodificador ICGC** permet obtenir les coordenades d’un lloc ubicat a Catalunya a partir de la seva adreça postal o del seu nom (topònim). També permet l'operació contrària, la **geocodificació inversa**, que consisteix a obtenir l'adreça postal o el nom del topònim més proper a una posició expressada en coordenades.

 
URL de connexió: [https://eines.icgc.cat/geocodificador](https://eines.icgc.cat/geocodificador)

El **Geocodificador ICGC** és una interfície de programació d'aplicacions web **API REST**, integrable en altres aplicacions, de manera que és senzill afegir un cercador d'adreces i/o topònims a un visor de mapes.

## Funcionalitats

* Localització d'adreces postals dels tipus següents:
     - portal (nom de carrer + portal + municipi o llogaret).
     - edificacions aïllades (nom de l'edificació aïllada + municipi o llogaret).
* Localització de carrers (nom de carrer + municipi o llogaret).
* Consulta del quadre envolvent de cada carrer obtingut.
* Localització de topònims (nom + municipi).
* Geocodificació inversa per a trobar l'adreça o topònim més proper a un punt indicat per les seves coordenades.
* Restringir la cerca dins una àrea geogràfica circular o rectangular.
* Restringir la cerca a una comarca o un municipi.
* Restringir la cerca a determinats tipus de topònims.
* Priorització de les solucions més properes geogràficament a un punt donat.
* Disponibilitat de dues operacions de geocodificació directa, que és aconsellable combinar en la integració en altres aplicacions:
     - **autocompletar**: a mesura que l'usuari va teclejant el text a cercar, enviar peticions a **autocompletar**, amb la finalitat de trobar respostes de forma ràpida. 
     - **cerca** (cerca completa): retorna les dades i la ubicació d’una adreça o topònim indicats de forma completa. Un cop s'ha completat el text, si les respostes proporcionades per **autocompletar** no són suficients, es pot fer una petició a l'operació **cerca** al prèmer la tecla [Intro].


Es recomana utilitzar llibreries client que incorporin aquestes pautes d'ús, com Leaflet i el plugin Nextzen (anteriorment Mapzen), com s'ha fet al Visor exemple, implementat amb Leaflet i explicat a  Visor de mapes amb consultes al servei Geocodificació ICGC.

## Operacions
Disposa de les operacions següents:

* [**cerca** (geocodificació directa indicant adreça completa)](parametres_cerca.md)

* [**autocompletar** (geocodificació directa sense necessitat de completar totes les dades d’identificació)](parametres_autocompletar.md)

* [**invers**  (geocodificació inversa)](parametres_invers.md)

## Documentació

[https://eines.icgc.cat/geocodificador/api-docs/](https://eines.icgc.cat/geocodificador/api-docs/)

## Exemples

 * [1.1 Cercar una adreça postal](ex_adreca.md)
 * [1.2 Cercar un topònim](ex_toponim.md)
 * [1.3 Geocodificació inversa](ex_invers.md)
 * [1.4 Obtenir el llogaret al que pertany una adreça](ex_llogaret1.md)
 * [1.5 Cercar una adreça postal segons el llogaret](ex_llogaret2.md)
 * [1.6 Integració en un visor Leaflet](visor.md)
 * [1.7 Prioritzar els resultats més propers a un punt](ex_prioritzar.md)
 * [1.8 Restringir la cerca dins una àrea geogràfica circular o rectangular](ex_area.md)
 * [1.9 Filtrar segons tipus de topònim](ex_tipus.md)
 * [1.10 Filtrar per comarca o per municipi](ex_comarca_municipi.md)

