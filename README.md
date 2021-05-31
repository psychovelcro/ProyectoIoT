<img src="https://hackster.imgix.net/uploads/attachments/723841/blob_fXIeojA4b3.blob?auto=compress%2Cformat&w=900&h=675&fit=min" align="left" height="100" width="100" ></a>

# Proyecto Integrador IoT. Hot Wheels Gallinero
----------

1. ## Objetivos
- El presente proyecto, trata de implementar una solución con el apoyo de la tecnología IoT
para sofisticar la industria agrícola, en concreto la relacionada a la avicultura.
Para comenzar, vamos a conectar mediante un fotoresistor un arduino que envía el mensaje al ordenaador 
una vez que se ha emitido la señal. 
La siguiente etapa, constaría de utilizar un arduino MKR-WIFI-1010 para enviar las señales a un dashboard a través de una seña de wifi. 

----------

2. ## Materiales

<img src="https://i.blogs.es/ad563d/arduino/1366_2000.jpg" align="right" height="100" width="100" ></a>
- Arduino UNO R3
Arduino es una plataforma de creación de electrónica de código abierto, la cual está basada en hardware y software libre, flexible y fácil de utilizar para los creadores y desarrolladores. Esta plataforma permite crear diferentes tipos de microordenadores de una sola placa a los que la comunidad de creadores puede darles diferentes tipos de uso.

----------

<img src="https://www.luisllamas.es/wp-content/uploads/2015/04/arduino-ldr.png" align="left" height="100" width="100" ></a>

- Un fotoresistor, o LDR (light-dependent resistor) es un dispositivo cuya resistencia varia en función de la luz recibida. Podemos usar esta variación para medir, a través de las entradas analógicas, una estimación del nivel del luz.
Un fotoresistor está formado por un semiconductor, típicamente sulfuro de cadmio CdS. Al incidir la luz sobre él algunos de los fotones son absorbidos, provocando que electrones pasen a la banda de conducción y, por tanto, disminuyendo la resistencia del componente. 

----------

<img src="https://jovenesmakers.files.wordpress.com/2016/12/830-pts-full-sized-solderless-breadboard.jpg" align="right" height="100" width="100" ></a>
- Una Protoboard o breadboard es una tabla rectangular de plástico con un montón de pequeños agujeros en ella. Estos agujeros permiten insertar fácilmente componentes electrónicos para hacer un prototipo (es decir, construir y probar una versión temprana de) un circuito electrónico, como por ejemplo con una batería, un interruptor, una resistencia y un LED (diodo emisor de luz).

----------

<img src="https://mascotasornipet.es/wp-content/uploads/2019/09/copele-ponedero-gallinas-accesorio-cubeta.jpg" align="left" height="100" width="100" ></a>

- Ponedero y canaleta

----------

<img src="https://www.aprendiendoarduino.com/wordpress/wp-content/uploads/2016/03/arduino-genuino.png" align="right" height="100" width="100" ></a>

3. ## Código Fuente Arduino





----------

4. ## Conclusión
- Al parecer, el campo en el que nos estamo moviendo es muy virgen y árido como para encontrar una variedad de proyectos en lo cuales soportar nuestra teoría, a continuación, se encuentra el enlace único que muestra un proyecto realizado con el arduino mkr1010 wifi. 
https://create.arduino.cc/projecthub/ahmadradhy/mqtt-protocol-with-thingsboard-cloud-using-arduino-mkr1010-3a8cdb

Con respecto a esta primera etapa, hemos conseguido enviar la señal del fotosensor, al mecanismo y recibir señal directa del arduino. Siguiente etapa, implementacion con arduino mkr1010.

5. Codigo fuente arduino MKR1010 y Thingsboard (en archivo alojado en repositorio)


