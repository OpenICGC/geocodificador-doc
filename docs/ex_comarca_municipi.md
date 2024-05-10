# 1.10 Filtrar per comarca o per municipi.
Es possible restringir la cerca a una comarca o un municipi, indicant els paràmere **com** o **mun**.

El paràmetre **com** permet especificar el nom de la comarca o el seu identificador. Es pot consultar el llistat de comarques a [https://www.idescat.cat/codis/?id=50&n=10](https://www.idescat.cat/codis/?id=50&n=10)

El paràmetre **mun** permet especificar el nom del municipi o el seu identificador. Es pot consultar el llistat de municipis a [https://www.idescat.cat/codis/?id=50&n=10](https://www.idescat.cat/codis/?id=50&n=9)

Per exemple, la petició [https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca&mun=girona](https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca&mun=girona) cerca biblioteques del municipi de Girona

i la petició [https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca&com=girones](https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca&com=girones)  cerca biblioteques de la comarca del Gironès