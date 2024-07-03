# 1.10 Filtrar por comarca o por municipio
Es posible restringir la búsqueda en una comarca o un municipio, indicando los parámetros **com** o **mun**.

El parámetro **com** permite especificar el nombre de la comarca o su identificador. Se puede consultar el listado de comarcas en [Tabla de comarcas](https://www.idescat.cat/codis/?id=50&n=10&lang=es){target="_blank"}

El parámetro **mun** permite especificar el nombre del municipio o su identificador. Se puede consultar el listado de municipios en [Tabla de municipios](https://www.idescat.cat/codis/?id=50&n=9&lang=es){target="_blank"}

Por ejemplo, la petición [https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca<span style="color:red">*&mun=girona*</span>](https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca&mun=girona){target="_blank"} busca bibliotecas del municipio de Girona

y la petición [https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca<span style="color:red">*&como=girones*</span>](https://eines.icgc.cat/geocodificador/autocompletar?text=biblioteca&com=girones){target="_blank"} busca bibliotecas de la comarca del Gironès