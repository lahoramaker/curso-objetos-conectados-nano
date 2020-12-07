# Módulo 2 - Trabajando con sensores
En este segundo módulo vamos a ver cómo podemos empezar a trabajar con sensores.

# Videos del módulo 2
Los contenidos de este módulo están distribuidos en dos videos.

## Midiendo la aceleración con Arduino Nano 33 IoT
En este video vamos a empezar a trabajar con los sensores que vienen incluidos en nuestra placa Arduino Nano 33 IoT. En concreto trabajaremos con el acelerómetro, para leer los movimientos de la placa en tiempo real desde nuestro ordenador, utilizando la conexión serie.

También veremos cómo pintar estos datos utilizando el plotter serie, una herramienta no muy conocida, que se ofrece en el Arduino IDE.

(Ojo, no vamos a medir la aceleración a la que viaja nuestro Arduino en un coche ni nada parecido, sólo utilizaremos el acelerómetro integrado en la placa para medir sus movimientos)

URL del vídeo: https://youtu.be/baqWMYMkOb4

### Ejercicios avanzados planteados en el vídeo
Si queréis realizar unos ejercicios más avanzados basados en estos mismos elementos podéis probar a:
- Combinar las escrituras de los valores del acelerómetro a través del puerto serie con el parpadeo del led de la placa ¿Qué ocurre con la frecuencia de refresco?
- Personalizar la salida del puerto serie para adecuarla a nuestro gusto ¿Podemos escribir un fichero separado por comas (csv) que sea leido por Excel/Calc de LibreOffice?
- ¿Qué ocurre si configuro una velocidad diferente en el programa y en el monitor serie? ¿Se ve más rápido? ¿No sale nada? ¿Sale "ruido"?


## Midiendo la temperatura y humedad con Arduino Nano 33 IoT
En este vídeo vamos a empezar a trabajar con sensores externos conectados a nuestra placa Arduino Nano 33 IoT. En concreto trabajaremos con el sensor de temperatura y humedad DHT11. Para conectar este sensor vamos a necesitar una placa de prototipado externa, cables para conectar el sensor a Arduino y una resistencia de 10k Ohmios. Necesitaremos esta resistencia ya que vamos a crear un divisor de tensión para leer los datos del sensor.

URL del vídeo: https://youtu.be/WygmqJ6PXKE
