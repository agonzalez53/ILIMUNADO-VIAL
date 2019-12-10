# ILUMINADO-VIAL

# Facultad de IngenierÌa Civil

# Ingeniero TopÓgrafo Geomático

# PE-ITP

Alma Judith González Montes 
correo electronico:
galma0564@gmail.com
    
Daniel Alexander Peralta Landin
correo electronico: 
dperalta1@ucol.mx

Héctor Daniel Rosales 
correo electronico:
hector_rome_15@outlook.com

# Resumen

Para este trabajo se realizara un programa para sacar el area donde sea la mejor manera de instalar ilumidado vial en una zona que padese de iluminado en el Municipio de Coquimatlán, con ayuda de el PyQgis y un administrador de Windows.

El programa tomara los datos recaba-dos de archivos vectoriales, que el usuario ingrese en este, de esta manera las instrucciones en el código se guirán hasta que se obtenga lo buscado.

Palabras clave: Iluminado, Vertoriales, PyQgis, Windows, usiario. . 

# Abstract

For this job a program is carried out to remove the area where the best way to install illuminated roads is in an area that suffers from lighting in the Municipality of Coquimatlán, with the help of PyQgis and a Windows administrator.

The program will take the data collected from experienced files, which the user enters into it, in this way the instructions in the code will be guided until the desired thing is obtained.

Keywords: Illuminated, Vertorial, PyQgis, Windows, user. 

# 1. 	Introduction 

QGIS es un excelente software para la manipulación de archivos espaciales y a ello se le suma Python como un lenguaje de programación que está siendo usado para múltiples fines, presentándose así el caso de Python en QGIS, que de una manera rápida mediante scripts podemos tener visualizaciones y resultados de procesos en pocos segundos, además las configuraciones que se hacen en la consola de Python pueden ser guardadas para futuros proyectos ahorrando tiempo y automatizando nuestras actividades.

Como es sabido, QGIS es un Sistema de Información Geográfica (GIS, por su referencia en inglés) de código libre para plataformas GNU/Linux, Unix, Mac OS y Microsoft Windows, que resulta amigable al usuario.


QGIS nos permite crear, visualizar y manejar datos de un mapa en el ordenador. Este software soporta formatos del tipo vector y ráster a través de las bibliotecas GDAL y OGR, así como bases de datos (que pueden ser extensibles p. ejm. desde PostgreSQL y PostGIS), al igual que algunos de los formatos comunes de datos espaciales (p. ejm.: ESRI ShapeFile, geotiff).

Así mismo, QGIS nos permite ampliar las herramientas y capacidades estándar con las que cuenta a través del uso y desarrollo de complementos.

El desarrollo de complementos o aplicaciones personalizadas en PyQGIS está basado en el uso de la QGIS API (Interfaz de programación de aplicaciones de QGIS, por sus siglas en inglés), la misma que cuenta con diferentes métodos que se integran en clases, las que a su vez están comprendidas en 5 módulos.

Python es un lenguaje de programación poderoso y fácil de aprender. Cuenta con estructuras de datos eficientes y de alto nivel y un enfoque simple pero efectivo a la programación orientada a objetos. 

La elegante sintaxis de Python y su tipado dinámico, junto con su naturaleza interpretada, hacen de éste un lenguaje ideal para scripting y desarrollo rápido de aplicaciones en diversas áreas y sobre la mayoría de las plataformas.

El intérprete de Python y la extensa biblioteca estándar están a libre disposición en forma binaria y de código fuente para las principales plataformas desde el sitio web de Python, puede distribuirse libremente. El mismo sitio contiene también distribuciones y enlaces de muchos módulos libres de Python de terceros, programas y herramientas, y documentación adicional.

El intérprete de Python puede extenderse fácilmente con nuevas funcionalidades y tipos de datos implementados en C o C++ (u otros lenguajes accesibles desde C). Python también puede usarse como un lenguaje de extensiones para aplicaciones personalizables.

La iluminación vial juega un papel muy impor-tante en la sociedad pues con ella se pretende mantener visibilidad en la mayor parte de las calles de una ciudad o población, lo que puede ayudar a la seguridad de las personas.

Con este proyecto se busca la mejora de las lámparas para que estas ayuden a obtener el objetivo que estas tienen. Si es que alcanzan a abarcar la mayor área posible y también mejorar el rendimiento y menor gastos en la electricidad. Todo esto en el municipio de coquimatlan en la zona centro.

# 2. 	Desarrollo

Para hacer una renovación de cualquier cosa para minimizar los gastos en su utilización, es necesario tener en cuenta todos los aspectos necesarios que ayudaran a tomar decisiones al momento de elegir los nuevos recursos.

Que tanto será la disminución de gastos que se generaran a partir de la renovación, en este caso, se busca minimizar gastos en electricidad y también, que las lámparas abarquen una ma-yor área para que estas ayuden a tener la mayor parte de las vialidades iluminadas.

Es necesario conocer qué tipo de lámparas están siendo utilizadas actualmente, así como el precio que tienen y también el área de superficie que alcanzan a iluminar para posteriormente comenzar con la búsqueda de un nuevo modelo que mejore todos los aspectos posibles.

También debemos tomar en cuenta que este tipo de lámpara son utilizadas en muchos dife-rentes lugares que requieren iluminación.

En la figura de abajo vamos a ilustrar La altura del poste o la altura a la que se piensa a colocar la lámpara o luminaria.
Debemos tomar en cuenta que estas cifras son en en función de la cantidad de área que se pretende iluminar y la cantidad de luz con la que se pretenda proveer a ese espacio.

![PalabrasdelTextoAlternativo](https://github.com/agonzalez53/ILIMUNADO-VIAL/blob/master/IMAGENES/ilumi.jpg)

Es necesario también ubicar los puntos que indiquen la ubicación de los postes de luz sobre el polígono generado a través de un mapa para conocer que partes de las vialidades pueden estar siendo ignoradas o en otras palabras, que no están siendo iluminadas, para buscar otros puntos estratégicos que ayuden a mantener el máximo porcentaje de la vialidad iluminada.

Actualmente los luminarios convencionales para el alumbrado público de vialidades a nivel mun-dial que aun operan lámparas de aditivos metá-licos y de vapor de mercurio con potencias de 175 y 250 W o de vapor de sodio en alta presión con potencias de 150 y 250 W (mediante sus respectivos balastros electromagnéticos en todos los casos ) y que se encuentran instalados en postes a 9 metros de altura de montaje, se pueden reemplazar de forma integral por nuevos luminarios que operan lámparas tubulares rectangulares de inducción electromagnética con arillos inductores externos con potencias de 80 W (para sustituir potencias de 175 y 150 W) y 120 W (para sustituir potencias de 250W) que tienen las siguientes características:

* Carcasa que aloja al módulo de potencia y conjunto óptico fabricada en fundición de alumi-nio inyectada en alta presión con acabado de pintura de resina poliéster en polvo aplicada mediante proceso electrostático.

* Tapa de apertura superior con abatimiento trasero o lateral para acceso al conjunto óptico y módulo de potencia fabricada en fundición de aluminio inyectada en alta presión con acabado de pintura de resina poliéster en polvo aplicada mediante proceso electrostático.
* Conjunto óptico con alto grado de protección ante el ingreso de partículas sólidas y liquidas (IP65), integrado por un refractor curvo o plano de vidrio claro termotemplado resistente a cam-bios bruscos de temperatura y un reflector con diseño facetado fabricado de aluminio hidrofor-mado anodizado de alta reflectancia con acaba-do especular.

* Empaques o sellos termoformados de hule silicón con larga vida útil para asegurar una alta hermeticidad entre la carcasa y la tapa de aper-tura superior.

* Filtro de carbón activado situado en la parte posterior del reflector para evitar altas presiones de operación dentro del conjunto óptico.

* Sistema de cierre entre la tapa de apertura superior y la carcasa mediante broches frontales o laterales fabricados de acero inoxidable.

* Lámpara tubular rectangular de inducción elec-tromagnética con arillos inductores externos con potencias de 80 o 120 W.

* Generador electrónico de alta frecuencia para operar una lámpara tubular rectangular de in-ducción electromagnética con arillos inductores externos con potencias de 80 o 120 W.

![PalabrasdelTextoAlternativo](https://github.com/agonzalez53/ILIMUNADO-VIAL/blob/master/IMAGENES/mapa.jpg)

* Receptáculo superior para incorporar foto interruptor electrónico para el control automático del encendido y apagado.
* Sistema de montaje del luminario mediante adaptador horizontal ajustable con entrada para brazo a poste y/o acoplamiento vertical para colocación en punta de poste.

* Curvas de distribución fotométrica IES tipo II corta o media con control cut-off que limita al máximo el flujo luminoso emitido hacia el hemisferio superior del luminario.

* Eficiencia promedio del luminario de 80% con un alto coeficiente de utilización del lado calle para una mejor uniformidad del flujo luminoso enviado hacia la carpeta asfáltica.

Mostrando el código que se generó en Python de PyQgis.


# 2.1. 	Manejo de datos

# 1.	Tratamiento de datos

El programa tomara los datos recaba-dos de archivos vectoriales para que puedan ser procesados en el software PyQgis, el usuario ingresara en este y puedan llevar el mejor manejo adecuado para obtener resultados satisfactorios, de esta manera las instrucciones en el código seguirán hasta que se obtenga lo buscado y que la finalidad de esta es que sea de buen provecho para que esa área sea iluminada y puedan tener una seguridad los habitantes de la comunidad, que en realidad es para ellos y esten de una manera seguros que tendran la iluminacion adecuada .

![PalabrasdelTextoAlternativo](https://github.com/agonzalez53/ILIMUNADO-VIAL/blob/master/IMAGENES/poli.jpg)

Archivo vectorial de la mancha urbana del municipio de Coquimatlán.

# 2.	Plataforma

Se pretende que este programa funcio-né con la plataforma Windows, anqué se espera que para poder aumentar el uso de este programa se convierta en multiplataforma y tenga un mejor funcionamiento para que sea muy util, no solo con ciertos puntos si no que abarque la mayor parte de ella.

# 3.	Programas

El programa que tiene una gran rele-vancia en este proyecto es el de PyQgis. Esto por  la gran cantidad de li-brerías que podrán facilitar estos proce-dimientos. 

Dentro de este software se esncuentra el Python que es en el que se va manejar el codgo y se iran procesando los datos  necesarios paar utilizar y encontrar el area y los mejores punto para la intalacion de laparas en la colonia del Municipio de Coquimatlán.

# 2.2. 	Resultados

# Tratamiento de datos

El programa tomara los datos recaba-dos de archivos vectoriales para que puedan ser procesados en el software PyQgis, el usuario ingresara en este y puedan llevar el mejor manejo adecuado para obtener resultados satisfactorios, de esta manera las instrucciones en el código seguirán hasta que se obtenga lo buscado y que la finalidad de esta es que sea de buen provecho para que esa área sea iluminada y puedan tener una seguridad los habitantes de la comunidad, que en realidad es para ellos y esten de una manera seguros que tendran la iluminacion adecuada

![PalabrasdelTextoAlternativo](https://github.com/agonzalez53/ILIMUNADO-VIAL/blob/master/IMAGENES/poli.jpg)

Archivo vectorial de la mancha urbana del muni-cipio de Coquimatlán.

Se pretende que este programa funcioné con la plataforma Windows, anqué se espera que para poder aumentar el uso de este programa se convierta en multiplataforma y tenga un mejor funcionamiento para que sea muy util, no solo con ciertos puntos si no que abarque la mayor parte de ella.

# Programas
El programa que tiene una gran relevancia en este proyecto es el de PyQgis. Esto por  la gran cantidad de librerías que podrán facilitar estos procedimientos.

Las coordenadas que se mandan llamar por medio de un código ya establecido hacen que se relacionen con  lugares en la tierra reales. La decisión sobre el sistema de proyecciones y el sistema de coordenadas de referencia a usar depende de la zona que se desea trabajar, del análisis que se pretende hacer y  a menudo de la disponibilidad.

También como el sistema de proyecciones de coordenadas existen otra forma de representar la tierra que es muy útil y en este caso a noso-tros nos facilitó un poco más las cosas para poder llevar con mayor facilidad el proyecto para representar la forma del lugar donde será el estudio.

Pueden existir algunos problemas con este enfoque, ya que en la mayoría se consérvenla mayor parte de la forma de la tierra e ilustra la configuración espacial de los objetos del tamaño continental.

![PalabrasdelTextoAlternativo](https://github.com/agonzalez53/ILIMUNADO-VIAL/blob/master/IMAGENES/poli%20pun.jpg)

En esta muestra ya se dan a conocer los puntos la localización que son los que se buscan para tener mejor la iluminación, son los que se pre-tenden instalar para que en esta área que se llevó el proyecto en práctica  tenga una mejor ycómoda iluminación para los habitantes de esta colonia del municipio de Coquimatlán.

Para poder llegar a tener la localización de cada punto estos fueron llamados de un archivo en  con extensión  de csv. Que  se tenían   con coordenadas. 

Una vez que ya se tenían las coordenadas esto trajo consigo cada punto como se muestra en la imagen. Teniendo también con este procesa-miento se puede obtener el área total de la su-perficie a trabajar y tener en cuenta los gastos que se llegaran a utilizar en un proyecto como este si es que se llevara a la vida cotidiana.

Posteriormente ya que se ubicaron los punto  y se obtuvo el área en una base de dato se guar-daron todo los datos obtenidos, llamándole a esta base de datos postes de luz.

![PalabrasdelTextoAlternativo](https://github.com/agonzalez53/ILIMUNADO-VIAL/blob/master/IMAGENES/poste.jpg)

Finalmente todos los datos obtenidos de dicho código de dicho proyecto quedaran guardados  en esta base de datos.

# CODIGO

capa = QgsVectorLayer(data_source, layer_name, provider_name)
if not layer.isValid():
  print "Layer failed to load!"
#creamos una memoria layer
mem_layer = QgsVectorLayer("Point?crs=epsg:4326&field=id:integer""&field=area:double&index=yes",
                            "Points",
                            "memory")
                              
  
#agregamos un mapa
QgsMapLayerRegistry.instance().addMapLayer(mem_layer)
  
#Preparamos el mapa para editar
mem_layer.startEditing()
  
#agregamos puntos
points = [QgsPoint(-150,61),QgsPoint(-151,61),QgsPoint(-151,62)]
 
#calculamos el numero de puntos
n = len(points)
if n <= 0:
    print ("area =", n*5)
feature = []
 
for i in range(n):
    feat =QgsFeature()
    feature.append(feat)

  
#set attributes values 
for i in range(n):
    feature[i].setGeometry(QgsGeometry.fromPoint(points[i]))  #Set geometry
    feature[i].setAttributes([i,area[i]])
    mem_layer.addFeature(feature[i], True)
  
#paramos la edicion
mem_layer.commitChanges()
 
#hacemos zoom a la layer y la activmos
iface.zoomToActiveLayer()


# PÓSTER

![PalabrasdelTextoAlternativo](https://github.com/agonzalez53/ILIMUNADO-VIAL/blob/master/IMAGENES/POSTER.jpg)

# CONLUCIONES

# Hector Daniel Rosales Medina

En este proyecto tube la oportunidad de trabajar con un codigo, el cual note que puede ser muy eficiente al momento de que necesitamos que algo se haga de una manera automaizada, principalmente para ahorrar tiempo y para evitar errores en el manejo de estos datos.

En lo personal considero que el proyecto como tal puede traer un fin postivo a la sociedad, esto por el estudio que se realizo con anterioridad y por supuesto por la informacion que se recuepra de este estudio.

# Daniel Alexandro Peralta Landin

Este proyecto me ayudo mucho en la materia de programación, esto debido a que en la necesidad de crear un programa que automatice los pasos para agilizar cualquier tratamiento de datos. 

En general el proyecto me ayudo en mejorar mis habilidades con PyQGIS, principalmente por que no había utilizado todos estos pasos en un proyecto real, pero al poco tiempo de estar trabajando en este proyecto me percate de mis debilidades y fortalezas en el área. 

# Alma Judith Gonzalez Montes

En este proyecto se puede concluir que puede ser muy útil el código elaborado en cuanto beneficio a la sociedad para resolver un problema de alumbrado público como fue en esta ocasión o también puede funcionar con todos los servicios públicos para una comunidad. Esto agilizará las cosas para que puedan tener una respuesta más pronta y que sus necesidades sean tomadas en cuenta de inmediato.

En cuanto a la elaboración de dicho producto fue un poco complicado para nosotros elaborarlo ya que no es muy sencillo delimitar ciertos aspectos que son necesarios para que el programa funcione y vaya compilando paraq ue no resulte error.
