# Ventilador_IoT

## Ventilador Inteligente: Control por Temperatura y Distancia

# Integrantes
- Braulio Franciso Salas González 1222100471
- Itzel Alejandra Salas Hernández 1222100001
- Jesús Soto Ledezma 1222100475

# Descripción del proyecto
Este proyecto consiste en la creación de un ventilador inteligente que se activa y ajusta su velocidad automáticamente en función de la temperatura ambiente y la distancia a la que se encuentra una persona. El objetivo es proporcionar un flujo de aire personalizado y eficiente, mejorando el confort en espacios interiores.

# Funcionamiento
1- Detección de temperatura: Un sensor de temperatura (LM35) monitorea la temperatura ambiente en tiempo real.
2- Detección de distancia: Un sensor de distancia (HC-SR04) ultrasónico mide la distancia entre el ventilador y la persona más cercana.
3- Procesamiento y control: Una placa microcontroladora (Arduino Uno) recibe y procesa las señales de ambos sensores.
4- Ajuste de velocidad: La velocidad del ventilador se ajusta en función de la temperatura y la distancia, utilizando un (motor DC) y un (controlador PWM).

## Materiales
| Material | Cantidad	| Descripción|
|-|-|-|
| Sensor de temperatura |	1	| LM35 |
| Sensor de distancia |	1	| HC-SR04 |
| Microcontrolador |	1	 | Arduino Uno |
| Motor DC |	1	| 12V, 2A |
| Cables |	N/A	| Para conexiones |
| Fuente de alimentación	| 1	| 12V, 2A |
| Protoboard |	1	| Para montaje del circuito |
| Carcasa	| 1	| Para el ventilador |
| Led  | 1 | Para saber cuando se prende el ventilador |


## Software
| Software |	Descripción |
|-|-|
| Arduino IDE	| Entorno de desarrollo para programar el microcontrolador |
| Librería DHT	| Para leer el sensor de temperatura LM35 |
| Librería NewPing	| Para leer el sensor de distancia HC-SR04 |
| NodeRed | Crear un dashboard para mostrar la temperatura, la distancia y la velocidad del ventilador en tiempo real. |
| Xampp | Crear una base de datos para almacenar históricos de temperatura, distancia y velocidad del ventilador. |
| Mosquitto | Implementar un protocolo de mensajería MQTT para la comunicación entre el ventilador, los sensores y Node-RED. |
