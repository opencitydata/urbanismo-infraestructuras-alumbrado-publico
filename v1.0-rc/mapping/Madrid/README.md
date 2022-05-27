# Ejemplos
# ULuminosa1.csv
Conjunto de datos que se ha obtenido a partir del ayuntamiento de la ciudad de Madrid 
- https://datos.madrid.es/sites/v/index.jsp?vgnextoid=72b76cc09a800810VgnVCM1000001d4a900aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD
- Origen de los datos: Ayuntamiento de Madrid 
- Licencia: https://datos.madrid.es/egob/catalogo/aviso-legal

# mapping.rml
Es el archivo que contiene los datos del csv estructurados, a partir del vocabulario desarrollado, por rmlMapper.
  ## Atributos
  - tipoLampara: Lista skos en la que se encuentra el modelo de lampara que está utilizando la farola.
  - modeloBombilla: Modelo de bombilla concreto que está usando la farola.
  - streetAddress: Atributo que represente el tipo de vía, el nombre de la calle y el número de la calle en el que se encuentra la farola.
  - codigo: Representa el código que comparten un número de unidades luminosas que están en la misma calle.
  - distrito: Representa los 21 distritos de Madrid.
  - barrio: Represente los barrios que hay en Madrid.
  - long: Representa la coorddenada X.
  - lat: Representa la coordenada Y.

# salida.nt
Es el resultado obtenido tras procesar los datos con rmlmapper.
- salida.nt: resultado con 300 ejemplos.
- salidaCorta: resultado con solo 1 ejemplo.

# mappingC.rml
Es el archivo que contempla todos los atribtuos de el vocabulario.
