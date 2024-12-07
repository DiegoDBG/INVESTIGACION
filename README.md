# INVESTIGACION
## 1.- ¿Qué es una tarjeta de adquisición de datos?
Las tarjetas de adquisición de datos (hardware) actúan como la interfaz entre una computadora y señales físicas, es decir, la información recaudada por el sensor se pasa al DAQ, el cual se encarga de transformar los códigos del mundo real a los códigos digitales, como si se tratara de un intérprete que traduce de un lenguaje a otro, con el fin de que el sistema digital (es decir, cualquier computadora o dispositivo electrónico) sea capaz de comprender los signos del analógico.
Las tarjetas de adquisición de datos consisten en tres partes principales: por un lado, está el circuito de acondicionamiento de señales, después está el convertidor analógico-digital (ADC por sus siglas en inglés) y, finalmente, el bus del ordenador.

![](https://github.com/DiegoDBG/INVESTIGACION/blob/main/BasicDAQ.jpg?raw=true)

## 2.- ¿Qué es un HMI?
HMI es el acrónimo de Human Machine Interface (interfaz humano-máquina). La definición de una interfaz humano-máquina es la de una interfaz de usuario o un panel de control que combina software y hardware para ayudar al operario a comunicarse entre sistemas y máquinas.
Su objetivo es aumentar la productividad, incrementar el tiempo de funcionamiento y proporcionar una calidad de producto constante.

![](https://github.com/DiegoDBG/INVESTIGACION/blob/main/HMI.jpg?raw=true)

## 3.- Menciona los Elementos de un sistema de adquisición
La adquisición de datos es un proceso mediante el cual fenómenos físicos del mundo real (sistema analógico) son transformados en señales eléctricas. Estas señales son medidas y convertidas en formato digital (conversión analógica-digital) para su procesamiento, análisis y almacenamiento en una computadora. Para ello se utiliza un módulo de digitalización o tarjeta de Adquisición de Datos (DAQ). Un sistema de adquisición de datos se compone básicamente de: 
- Sensores y transductores
- Acondicionamiento de la señal 
- Hardware y software para la adquisición de datos, PC (sistema de operación)
  
![](https://github.com/DiegoDBG/INVESTIGACION/blob/main/image.png?raw=true)

**Transductores y sensores:** Los transductores y sensores son la interfaz entre el mundo real y el sistema de adquisición. Éstos convierten un fenómeno físico en señales eléctricas. El transductor es un elemento de censado que responde directamente a la cantidad física que se quiere medir (el transductor es referido frecuentemente como un sensor).

**Acondicionamiento de la señal:** Las señales de los sensores o del mundo exterior pueden ser ruidosas o demasiado peligrosas para medirse directamente. El circuito de acondicionamiento de señales manipula una señal convirtiéndola en una señal apropiada para la entrada de la tarjeta de adquisición de datos. Este circuito puede incluir amplificación, atenuación, filtrado y aislamiento.

**Hardware – software para la adquisición de datos (DAQ):** En esta etapa la señal analógica medida se convierte a formato digital (usando un conversor analógico-digital: conversor A/D) y luego los datos se transfieren a una computadora (mediante un software) para su almacenamiento y análisis.

## 4.- Los diferentes sensores que existen y ¿Qué es un sensor?
### ¿Qué es un sensor?
Un sensor es un dispositivo tecnológico que tiene la capacidad de percibir ciertos estímulos del exterior y transformarlos en impulsos eléctricos, que pueden ser interpretados por ordenadores u otras máquinas.

- Sensores de distancia:
Los sensores de distancia permiten medir cuánto espacio separa un punto de otro.

- Sensores de frecuencia de luz:
Los sensores de frecuencia de luz pueden percibir impulsos lumínicos y decodificar la intensidad de frecuencia de estos, dando como resultado un parámetro que puede contrastarse en una escala ayudando a detectar color.

- Sensores de humedad:
Los sensores de humedad permiten medir la temperatura y la cantidad de humedad relativa en el aire dentro de un espacio específico. Los resultados de estas medidas son transmitidos a impulsos eléctricos, usualmente para disparar un mecanismo mayor.

- Sensores de luz:
Un sensor de luz es un dispositivo capaz de percibir la luz ambiental (o la que se origina de un punto en concreto) y luego reaccionar a ella con un impulso eléctrico que varía dependiendo de la intensidad de la luz que ha detectado. a mayor lectura de luz, mayor intensidad en la respuesta eléctrica.

- Sensores de Posición:
Permiten medir la posición lineal o angular de un objeto con respecto a un plano (o usándose a sí mismo como referencia), para transformarla en una señal eléctrica que puede ser interpretada por un sistema de control mayor.

- Sensores de presión:
Los sensores de presión permiten determinar el nivel de presión que ejerce un fluido dentro de un espacio definido. A través de esta medición se pueden controlar un sinfín de acciones dentro de una industria. Son especialmente demandados en seguridad industrial para la prevención de eventos catastróficos.

- Sensores de proximidad:
Los detectores de proximidad ayudan a detectar la presencia de un objeto y su cercanía con el punto de referencia (usualmente el mismo sensor). Suelen funcionar con un par de dispositivos, un emisor y un receptor. El emisor envía una señal cada cierto tiempo y el receptor busca el rebote de la señal lo que le indica la proximidad del objeto.

- Sensores de sonido:
Los detectores de sonido reciben ondas acústicas en el ambiente producto de las ondas mecánicas que se generan a partir de las oscilaciones de precio de aire y, dependiendo de los niveles de intensidad para los que esté programada su respuesta, convierte estas perturbaciones en impulsos eléctricos.

- Sensores de temperatura:
Los sensores de temperatura son los más utilizados dentro del ámbito industrial y ayudan a medir la diferencia de energía calórica que existe entre un punto de referencia y el campo que se está midiendo, convirtiendo dichos datos en salidas eléctricas. Miden el calor.

- Sensores de velocidad:
Los sensores de velocidad ayudan a detectar el lapso que existe entre los cambios de posición de un objeto. Miden la velocidad de un cuerpo con relación a un punto de referencia. Los datos obtenidos son transformados en impulsos eléctricos.

- Sensores magnéticos:
Los sensores magnéticos son dispositivos medianamente sofisticados que, gracias a placas imantadas o conducción eléctrica, pueden detectar campos magnéticos (y su intensidad) dentro de un área sensible, convirtiendo dichos datos en impulsos eléctricos.

- Sensores ópticos:
Los sensores ópticos son esenciales dentro de la robótica porque son los que permiten “ver” determinados objetos y transformar esta respuesta visual a un impulso eléctrico. Estos sensores no poseen una visión convencional, sino que perciben un haz de luz constante que al ser interrumpido (o al variar de intensidad) genera un estímulo medible.

## 5.- ¿Qué es un acondicionador de señal? Y los diferentes que existen.
### ¿Qué es un acondicionador de señal?
El acondicionamiento de señal es un proceso de adquisición de datos que se lleva a cabo mediante un instrumento llamado acondicionador de señal. Ese instrumento convierte un tipo de señal eléctrica o mecánica (señal de entrada) en otro (señal de salida).  El objetivo consiste en amplificar la señal y convertirla a otro formato fácil de leer y compatible con fines de adquisición de datos o de control de una máquina.
Un acondicionador de señal ayuda a obtener medidas precisas, como condición esencial para la exactitud de la adquisición de datos o del control de máquinas. Este tipo de instrumentos son capaces de efectuar otras funciones adicionales.

-	Acondicionadores de señal analógicos: Operan con señales continuas y se utilizan ampliamente en aplicaciones como el control de procesos industriales.
  
-	Acondicionadores de señal digitales: Trabajan con señales discretas y son esenciales en la era moderna de la tecnología digital, especialmente en la comunicación y la informática.

-	Acondicionadores de señal de frecuencia: Estos están diseñados para manejar señales de frecuencia específicas y se utilizan en aplicaciones como la radio y la televisión

### Desarrollado por 
Diego David Bahena Galan

[GitHub](https://github.com/DiegoDBG)
