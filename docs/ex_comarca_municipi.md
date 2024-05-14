# 1.10 Filtrar per comarca o per municipi
Es possible restringir la cerca a una comarca o un municipi, indicant els paràmetres **com** o **mun**.

El paràmetre **com** permet especificar el nom de la comarca o el seu identificador. Es pot consultar el llistat de comarques a [Taula de comarques](https://www.idescat.cat/codis/?id=50&n=10){target="_blank"}

El paràmetre **mun** permet especificar el nom del municipi o el seu identificador. Es pot consultar el llistat de municipis a [Taula de municipis](https://www.idescat.cat/codis/?id=50&n=9){target="_blank"}

Per exemple, la petició [https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca<span style="color:red">**&mun=girona**</span>](https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca&mun=girona){target="_blank"} cerca biblioteques del municipi de Girona

i la petició [https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca<span style="color:red">**&com=girones**</span>](https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca&com=girones){target="_blank"} cerca biblioteques de la comarca del Gironès