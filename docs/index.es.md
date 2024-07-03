# Geocodificador ICGC-docs/es/index.md
La **geocodificación** es el proceso de convertir direcciones postales, nombres de lugar o puntos de interés a coordenadas.

El **Geocodificador ICGC** permite obtener las coordenadas de un lugar ubicado en Catalunya a partir de su dirección postal o de su nombre (topónimo). También permite la operación contraria, la **geocodificació inversa**, que consiste a obtener la dirección postal o el nombre del topónimo más próximo a una posición expresada en coordenadas.

 
#URL de conexión: [https://eines.icgc.cat/geocodificador](){target="_blank"}

El **Geocodificador ICGC** es una interfaz de programación de aplicaciones web *API REST**, integrable en otras aplicaciones, de forma que es sencillo añadir un búsquedador de direcciones y/o topónimos a un visor de mapas.

## Funcionalidades

* Localización de direcciones postales de los tipos siguientes:
     - portal (nombre de calle + portal + municipio o aldea).
     - edificaciones aisladas (nombre de la edificación aislada + municipio o aldea).
* Localización de calles (nombre de calle + municipio o aldea).
* Consulta del cuadro envolvente de cada calle obtenida.
* Localización de topónimos (nombre + municipio).
* Geocodificación inversa para encontrar la dirección o topónimo más próximo a un punto indicado por sus coordenadas.
* Restringir la búsqueda en una área geográfica circular o rectangular.
* Restringir la búsqueda en una comarca o un municipio.
* Restringir la búsqueda a determinados tipos de topónimos.
* Priorización de las soluciones más próximas geográficamente a un punto dado.
* Disponibilidad de dos operaciones de geocodificación directa, que es aconsejable combinar en la integración en otras aplicaciones:
     - **autocompletar**: a medida que el usuario va tecleando el texto a búscar, enviar peticiones a **autocompletar**, con el fin de encontrar respuestas de forma rápida. 
     - **cerca** (búsqueda completa): devuelve los datos y la ubicación de una dirección o topónimo indicados de forma completa. Una vez se ha completado el texto, si las respuestas proporcionadas por **autocompletar** no son suficientes, se puede hacer una petición a la operación **cerca** al oprimir la tecla [Intro].


Se recomienda utilizar librerías cliente que incorporen estas pautas de uso, como Leaflet y el plugin Nextzen (anteriormente Mapzen), como se ha hecho en el Visor ejemplo, implementado con Leaflet y explicado en  Visor de mapas con consultas al servicio Geocodificació ICGC.

## Operaciones
Dispone de las operaciones siguientes:

* [**cerca**** (geocodificación directa indicando dirección completa)](parametres_cerca.md)

* [**autocompletar** (geocodificación directa sin necesidad de completar todos los datos de identificación)](parametres_autocompletar.md)
*
* [**invers**  (geocodificación inversa)](parametres_invers.md)

## Documentación

[https://eines.icgc.cat/geocodificador/api-docs/](https://eines.icgc.cat/geocodificador/api-docs/){target="_blank"}

## Ejemplos

 * [1.1 Buscar una dirección postal](ex_adreca.md)
 * [1.2 Buscar un topónimo](ex_toponim.md)
 * [1.3 Geocodificación inversa](ex_invers.md)
 * [1.4 Obtener la aldea a la que pertenece una dirección](ex_llogaret1.md)
 * [1.5 Buscar una dirección postal según la aldea](ex_llogaret2.md)
 * [1.6 Integración en un visor Leaflet](visor.md)
 * [1.7 Priorizar los resultados más próximos a un punto](ex_prioritzar.md)
 * [1.8 Restringir la búsqueda dentro de una área geográfica circular o rectangular](ex_area.md)
 * [1.9 Filtrar según tipo de topónimo](ex_tipus.md)
 * [1.10 Filtrar por comarca o por municipio](ex_comarca_municipi.md)

## Visor

[Visor](visor.md)

