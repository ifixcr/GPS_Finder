# GPS_Finder
Localizador RF de GPS

## Descripcion

AddON de Hardware para localizar por RF GPS, Emisor RF y Receptor RF

# Cuestionario de proyecto

|Item|Respuesta|
|----|-------|
|Nombre de proyecto|Localizador RF para GPS|
|Descripción|Se desea por medio de un sensor de rayería, contar la frecuencia de eventos y de dispositivos que alerten a guardaparques en el campo. Existen **dos componentes** principales, el **sensor** de rayería y el dispositivo de **alerta**|
|Case|Sensor: Case IP profesional, con antena externa. Alerta: Case en epoxy transparente|
|Solar o alimentación alternativa|Solar y batería grande para sensor de rayería, carga inductiva para dispositivos de alerta|
|Presentación de datos al usuario|Existen gráficas de AdafruitIO. Los dispositivos de alerta tienen una pantalla con el número de eventos en la última hora|
|Entrada de datos por el usuario|Ninguno|
|Etapas: 1.|Prueba en San José: Solo un sensor de rayería, un dispositivo de alerta. Comparar con [Lightning maps](https://www.lightningmaps.org/)|
|2.|Producción en Isla del Coco: Tres sensores individuales de rayería, en posiciones opuestas. Varios sensores de alerta.|
|3.|Futuro: Realizar cálculo de Time-of-Arrival (TOA), para poder localizar rayos en un mapa. Compatibilidad con [Blitzortung](http://es.blitzortung.org/cover_your_area.php)|
|Hardware: Dispositivo Sensor|TTGO-TBeam, batería 18650, [sensor EMP](https://www.tindie.com/products/SMDKing/emp-sensor-detect-lightning-and-other-phenomena/)|
|Hardware: Dispositivo de Alerta|TTGO ESP32+OLED, batería, cargador inductivo. Alertas visuales y auditivas a definir.|
|Servicios|Adafruit.IO|
|Software|En Arduino, y Node-Red|
|Posibles problemas|Sensor de rayería, carga inductiva, case en epoxy transparente, AdafruitIO en Node-RED|
