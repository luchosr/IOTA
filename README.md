# IOTA - Nodo Documentación.


#### Como realizar el setup de un nodo con un VPS (Servidor virtual privado).

* video explicativo [aquí](https://docs.google.com/presentation/...).
* Explicación en PPT [aquí](https://www.youtube.com/redirect?redir_token=QUFFLUhqbnYtbTdkUHBpLTJnOTZ0NnQzaV9TcklRZ09RZ3xBQ3Jtc0trMFFFT0RUZjZxS3R3WXBldFpfb2twdmllZldUSHZGckJQUVZIZDJ2RkZ6d01lbGRwRmEtaXZQY0tLMlZkMnROb2RnTkN1dUNya1RSeVg2X0FrTlU0T0l3dURDdUg1cUVoU1JXMGFkRkZsYlB2SEEyNA%3D%3D&event=video_description&v=nfBhdRCV2kw&q=https%3A%2F%2Fdocs.google.com%2Fpresentation%2Fd%2F1YUtu4-322cS6eZXYZk-bvLszRqR_utBReC2beKHQ-5Q%2Fedit%23slide%3Did.g6323f58ee9_0_127).

#### Como realizar el set up de Raspberry pi zero w
+ [Setup remoto usando wifi](https://desertbot.io/blog/headless-pi-zero-w-wifi-setup-windows)
+ [Setup usando interfaz grafica por micro usb](https://www.circuitbasics.com/access-raspberry-pi-desktop-remote-connection/), aquí [otra opción](https://www.circuitbasics.com/access-raspberry-pi-desktop-remote-connection/).

#### Setup de sensores con Raspberry pi
+ Temperatura y humedad: [sensor DHT11](https://www.raspberrypi-spy.co.uk/2017/09/dht11-temperature-and-humidity-sensor-raspberry-pi/)
+ Calidad de aire (detección de NH3, NOx, alcohol, benceno, humo, CO2, etc.): [sensor MQ135](https://tutorials-raspberrypi.com/configure-and-read-out-the-raspberry-pi-gas-sensor-mq-x/)

###### Links útiles para el setup:
* [Qué es una protoboard y como usarla](https://www.youtube.com/watch?v=99Rqlf5T00w), aquí otro [link alternativo](https://www.youtube.com/watch?v=ZSuSIBA6phE)


#### Enviar mensajes desde un sensor conectado a Raspberry Pi a la tangle de IOTA

+ Repositorio de [IOT2Tangle](https://github.com/iot2tangle/Raspberry).


#### Como realizar una red Tangle privada
+ Tutorial para montar una red privada en ["Un click"](https://docs.iota.org/docs/hornet/1.1/tutorials/one-click-private-tangle).
+ [OPC2](https://btcmanager.com/private-iota-tangle-amazon-web-service/).


#### ROADMAP
* [Link.](https://roadmap.iota.org/)
* Entendiendo un poco a IOTA:
            - **¿Qué es Chrysalis?**: Es un estado intermedio y previo al coordicidio de la red principal.
            - **¿Qué es un Nodo Bee?**: Es un software de nodo implementado en *Rust* (lenguaje de programación) que permite conectarte a nodos vecinos en la red.
            - **¿Qué es IOTA Streams?**:(previamente Masked Autenticated Messaging) es un protocolo que permite transmitir datos encriptados desde cualquier dispositivo.
            - **¿Qué es Chronicle?**: es un nodo permanente que almacena todo el hisorial desde el inicio de la tangle de IOTA, su software está escrito en *Rust*.