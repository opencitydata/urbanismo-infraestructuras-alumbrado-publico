# Ejemplos
# Alumbrado.csv
Conjunto de datos que se ha obtenido a partir del ayuntamiento de la ciudad de Madrid 
- https://datos.madrid.es/sites/v/index.jsp?vgnextoid=72b76cc09a800810VgnVCM1000001d4a900aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD
- Origen de los datos: Ayuntamiento de Madrid 
- Licencia: https://datos.madrid.es/egob/catalogo/aviso-legal

# mapping.rml
Es el archivo que contiene los datos del csv estructurados, a partir del vocabulario desarrollado, por rmlMapper.
  ## Atributos
  - tipoLampara: Representa el modelo específico de la bombilla.
  - tipoLuminaria: Tiene tres posibilidades a representar, la primera sería tipo LED, la segunda opción sería de tipo DESCARGA (es lo mismo que las antiguas de incandescencia, halogenuros, etc) y por último el tipo LED-DESCARGA cuando se combinan ambos tipos.
  - tipoVia: Representa el tipo de vía de un lugar.
  - calle: Representa el nombre de la calle o vía.
  - codigo: Representa el código que comparten un número de unidades luminosas que están en la misma calle.
  - distrito: Representa los 21 distritos de Madrid.
  - barrio: Represente los barrios que hay en Madrid.
  - Longitude: Representa la coorddenada X.
  - Latitude: Representa la coordenada Y.

# salida.nt
Es el resultado obtenido tras procesar los datos con rmlmapper.
