# Proyecto-Sistemas-Embebidos
Sistema Automatizado de Monitorización de Salud

## Instrucciones
Si se desea realizar una implementación física, en el sensor de pulso se debe colocar el archivo HeartBeatSensorTEP2.hex

Dentro de Proteus, se encuentra el código del atmega.

El archivo heart_rate_monitor.c debe copiarse en mikroC y además se deben marcar las librerías respectivas dentro del programa para que se pueda correr correctamente.

Si sólo se realiza la simulación en proteus, se debe correr de forma normal y se podrán visualizar los valores de temperatura y latidos por minuto; los latidos serán aleatorios ya que se usa un pulse generator proveniente de Proteus

No fue posible realizar la conexión entre Raspberry y ThingSpeak, por lo que únicamente se pueden visualizar los valores obtenidos mediante ambos sensores que se tenían establecidos previamente.
