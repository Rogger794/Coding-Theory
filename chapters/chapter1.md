# Capítulo 1

## Introducción

Desde siempre, la transmisión de la información digital ha presentado un reto constante, debido a que los medios de transmisión generan ruido en los mensajes transmitidos corrompiendo los datos. Para evitar este problema, existen métodos que permiten detectar y corregir los errores de estos mensajes, los denominados códigos correctores de errores.

En el presente trabajo se desarrolla fundamentalmente el análisis y evaluación de los códigos de Hamming y los códigos de Reed-Muller. Los cuales sirven como métodos fundamentales para verificar que una cadena de bits no se reciba con errores a la hora de la transmisión de datos a través de un canal con ruido; en caso contrario, estos métodos nos permiterán corregir esos errores. Siendo esta característica fundamental en el campo de la computación, existe una gran variedad de métodos correctores que permiten reducir o en el mejor de los casos, obviar la retransmisión de datos.

Un ejemplo claro de código es el habla humana: las personas pueden cometer errores en su comunicación, ya sea, hablada o escrita, y aún así dejarse comprender por otras personas. Esto se debe a que el habla humana presenta redundancia, lo que permite que podamos extraer el significado real sin necesidad de oír o leer a la perfección un mensaje, ya sea por cuestiones de estructura o contexto, etc.

Imagine ahora una situación en la que controla un robot que se encuentra en la Luna. En este escenario la retransmisión de datos es muy costosa debido al tiempo que demora la transmisión. Su robot se encuentra frente a un acantilado, pero usted solo puede enviar un mensaje indicándole una de estas cuatro direcciones: (00) al frente, (10) atrás, (01) a la derecha y (11) a la izquierda. Obviamente, usted enviará (10), pero el canal de transmisión le genera ruido, lo que resulta en un mensaje (00), y entonces habrá perdido a su robot. Es por ello que el robot necesitaría un método que le permita detectar ese error, y si es posible corregirlo para evitar el triste desenlace.

En nuestro mundo digital actual, los códigos son ampliamente utilizados, incluso sin que lo notemos: en los sistemas de comunicación vía satelital, en la telefonía cableada e inhalámbrica, radio, TV digital, Wi-Fi, grabadoras de CDs y DVDs, en el proceso de escritura y lectura de una memoria RAM, etc. Por ello el siglo XXI puede ser considerado como el siglo de la información.

Respecto a las técnicas desarrolladas en la teoría de códigos, este estudio se centra en el uso de los códigos de Hamming (1950) y Reed-Muller (1956) para la detección y corrección de errores. Como dijo Richard W. Hamming, ganador del premio Turing en 1968 : “Parece entonces deseable examinar el próximo paso más allá de la detección de errores, la corrección de errores”.
