yvytu
=====

###Proyecto de tesis - Analisis de Sistemas UCA
===============================================

####Objetivo general
Desarrollar un kit **Hágalo Usted Mismo** de una central meteorológica utilizando materiales disponibles en ferreterías, usando la plataforma **Arduino** para el prototipado de hardware y el software de control de sensores, y proveer de una plataforma web de visualización con herramientas para docentes.

####Objetivos específicos (En ningún orden)
1. Medir la velocidad del viento, la dirección del viento, la temperatura ambiente, la humedad relativa, la lluvia, la calidad del aire (NO2, CO2), luminosidad, ruido ambiental.
2. Seleccionar los sensores que tengan menor costo y facilidad de instalación.
3. Utilizar tarjetas perforadas para montaje de las placas de los sensores
4. Utilizar cable telefónico y conectores rj11 para conectar las placas de los sensores a la placa principal.
5. Desarrollar la placa de producción del Arduino UNO, integrada a la ethernet shield y el conector para un modem SMS.
6. Enviar los datos de la captura de sensores cada 2 minutos, adicionar el georeferenciamiento de los datos.
7. Proveer de una API para el consumo de la información almacenada.
8. Instalar un sitio con información geográfica de la ubicación de las centrales instaladas, links de descarga de los datos, visualizaciones configurables e información didáctica para trabajar los datos en el aula.

####Lista de sensores y hw en general
1. Temperatura: LM35 [datasheet](http://www.ti.com/lit/ds/symlink/lm35.pdf)
2. Humedad: HIH-4000-001 [datasheet](http://sensing.honeywell.com/honeywell-sensing-hih4000%20series-product-sheet-009017-5-en.pdf?name=HIH-4000-001)
3. Ruido: COM-08635 [datasheet](http://dlnmh9ip6v2uc.cloudfront.net/datasheets/Sensors/Sound/CEM-C9745JAD462P2.54R.pdf)
4. Luz (fotocelula): SEN-09088 [datasheet](http://qed.princeton.edu/images/6/60/Photoresistor_SEN-09088-datasheet.pdf)
5. NO2: MICS-2710 [datasheet](http://www.cdiweb.com/datasheets/e2v/mics-2710.pdf)
6. CO2: MICS-5134 [datasheet](http://cfile204.uf.daum.net/attach/0207074B50EBD7042D607A)
