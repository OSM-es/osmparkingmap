# OSM Parking Map : Motivo
OSM Parking Map nace de la adaptación del mapa de la comunidad catalana a mostrar cualquier tipo de información temática, aprovechando la base de datos de Openstreetmap. En este caso se usa para mostrar información sobre aparcamiento.

# 0-La Base de datos: Openstreetmap
OSM (Openstreetmap) no es un mapa, es una base de datos de puntos y líneas geolocalizados, que entre otras cosas se puede aprovechar para realizar mapas (renderizaciones). Pero también se pueden aprovechar los datos. Todo ello se hace con claves, valores y relaciones en estos puntos y líneas.

En este mapa se tienen en cuenta las etiquetas para detectar:

*	parquímetros
* 	Tiquet
*	Residentes
*	Gratuito
*	Motos
*	De pago
*	Carga y descarga
*	Cargadores
*	Vados
*	Aparcamiento en la calle
*	Plazas para aparcamiento para minusválidos.

# 1-Mapa

-Mapa basado en [Bicycle tags map](https://wiki.openstreetmap.org/wiki/Bicycle_tags_map)

-Con modificaciones de [Ramiro Balado](https://github.com/Qjammer)

-Versión nueva Openlayers hecha por [Ripollx](https://github.com/Ripollx)

-Posibilidad de añadir JSONs hecha por [Hugoren Martinako ](https://github.com/Crashillo)

-Consultas complejas añadidas por [Ismael Luceno](https://github.com/ismaell)

-Ideas adicionales por [yopaseopor](https://github.com/yopaseopor)

El mapa nos permite la muestra de elementos determinados personalizables teniendo como fondo varios mapas distintos.

Directamente se puede modificar la página editando los archivos correspondientes:

* index.html contiene el esqueleto de la página.
* index.js contiene el orquestador para utilizar OpenLayers (sólo se requiere modificar para añadir nuevas funcionalidades).
* config.js contiene la definición de las capas, idioma y características que se quieren mostrar.


# 2-Mapcomplete

Utilitzem un repte personalitzat de [Mapcomplete](https://mapcomplete.osm.be)-[font]-(https://github.com/pietervdvn/MapComplete) per tal d'aportar les dades que faltin, fent-ho en idioma "natural" (no de la màquina ni d'Openstreetmap) i des de qualsevol dispositiu mòbil amb l'únic requisit de [registrar-se com a usuari/a d'OpenStreetMap](https://www.openstreetmap.org/login).

# [Completador de Mapcomplete sobre aparcaments](https://mapcomplete.osm.be/theme.html?userlayout=https://raw.githubusercontent.com/yopaseopor/mcquests/main/libraries.json)

# [Ejemplo del mapa funcionando](https://osm-es.github.io/osmparkingmap)

# Agradecimientos

A la [Comunidad Catalana de Openstreetmap](https://t.me/osmcat) y a [OSM España](https://t.me/osmes) por permitir estos mapas, así como a los desarrolladores que han colaborado. 

