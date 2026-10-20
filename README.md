# Python + LEGO SPIKE Prime (Pybricks)
 
Guía para programar el **LEGO SPIKE Prime** en **Python** con [Pybricks](https://pybricks.com), desde el navegador y por **Bluetooth**, sin instalar programas en la computadora. Organizada en dos niveles: **básico** y **avanzado**.
 
## Guía
 
👉 **[Abrir la guía de Python para SPIKE Prime](https://material-robotica.github.io/python-spikePrime/Guia-python-spike.html)**
 
> Guía previa, con bloques: [Open Roberta + SPIKE Prime](https://eliizquierdo.github.io/openRoberta-spike/Guia-OpenRoberta-SPIKE.html) (incluye la instalación del firmware Pybricks en el hub).
> Guía para LEGO EV3: [Open Roberta + EV3](https://material-robotica.github.io/openRoberta-ev3/Guia-OpenRoberta-EV3.html)
 
---
 
## Qué se necesita
 
- Hub **SPIKE Prime** con el firmware **Pybricks** instalado. Es el mismo firmware que usa Open Roberta: el hub sirve para bloques y para Python sin reinstalar nada.
- Computadora con **Bluetooth** (por ejemplo, Ceibalitas con Windows 11).
- Navegador **Google Chrome** o **Microsoft Edge** (Firefox y Safari no tienen Bluetooth web).
- Editor: [code.pybricks.com](https://code.pybricks.com).
## Contenido
 
| Nivel | Secciones |
|---|---|
| **Básico** | Introducción y entorno · Estructura base de un programa · Luces, sonido y pantalla · Movimiento · Maniobras y giros · Sensores (fuerza y ultrasonido) · Retos básicos |
| **Avanzado** | Funciones · Seguidor de línea proporcional · Giroscopio · Proyectos integradores · Buenas prácticas |
| **Ayuda** | Problemas frecuentes |
 
## Ciclo de trabajo
 
1. Activar el Bluetooth de la computadora (sin emparejar el hub desde Windows) y cerrar cualquier pestaña del Open Roberta Lab.
2. Abrir [code.pybricks.com](https://code.pybricks.com) y crear un archivo nuevo de tipo **Python**.
3. Encender el hub, tocar el botón de **Bluetooth** de Pybricks, elegir el hub y **Emparejar**.
4. Escribir el programa y tocar **▶**. Para detenerlo: **■** o el botón central del hub.
## Programa de prueba
 
```python
from pybricks.hubs import PrimeHub
from pybricks.parameters import Color, Icon
from pybricks.tools import wait
 
hub = PrimeHub()
 
hub.light.on(Color.GREEN)       # luz del botón central en verde
hub.display.icon(Icon.HAPPY)    # cara sonriente en la matriz
hub.speaker.beep(440, 300)      # pitido de 440 Hz durante 300 ms
wait(2000)                      # espera 2 segundos
print("Listo!")                 # mensaje en la consola de la computadora
```
 
## Referencias
 
- Pybricks Code: https://code.pybricks.com
- Documentación de Pybricks: https://docs.pybricks.com
- Open Roberta Lab: https://lab.open-roberta.org
---
 
Prof. Elizabeth Izquierdo · Material de Robótica
 
