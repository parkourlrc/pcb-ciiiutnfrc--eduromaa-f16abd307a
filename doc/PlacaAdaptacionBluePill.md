# Placa de adaptación para BluePill
Esta placa permite adaptar el conexionado del EduRoMAA a la placa de desarrollo [BluePill](https://stm32-base.org/boards/STM32F103C8T6-Blue-Pill.html).

<img title="" src="placaBluePill3D.png" alt="a" data-align="center">

## Características
* 3 pulsadores.
* 1 LED tricolor RGB.
* 1 LED color rojo.
* 2 conectores para la utilización con el EduRoMAA.
* 1 conector para entrada de alimentación de 5V.

### Asignación de pines de la BluePill
| Componente      | Pin BluePill | Periférico |
| --------------- |:------------:| ---------- |
| SW1             | PB15         |            |
| SW2             | PB14         |            |
| SW3             | PB13         |            |
| LED RGB (Red)   | PA10         |            |
| LED RGB (Green) | PA9          |            |
| LED RGB (Blue)  | PA8          |            |
| LED Red         | PB12         |            |

#### Header 1 - conector con EduRoMAA
| Pin Conector | Componente EduRoMAA | Pin BluePill |     |
|:------------:| ------------------- |:------------:| --- |
| 1            | 3.3V                | 3.3          |     |
| 2            | GND                 | G            |     |
| 3            | Paragolpe izquiero  | PA15         |     |
| 4            | Paragolpe derecho   | PB3          |     |
| 5            | Encoder izquierdo   | PB4          |     |
| 6            | Enconder On/Off     | PB6          |     |
| 7            | Encoder derecho     | PB5          |     |
| 8            | Sonar trigger       | PB7          |     |
| 9            | Sonar echo          | PB8          |     |
| 10           | Sonar On/Off        | PB9          |     |

#### Header 2 - conector con EduRoMAA
| Pin Conector | Componente                  | Pin BluePill |     |
|:------------:| --------------------------- |:------------:| --- |
| 1            | Sensor de linea izquierdo   | PA0          |     |
| 2            | GND                         | G            |     |
| 3            | Sensor de linea derecho     | PA1          |     |
| 4            | GND                         | G            |     |
| 5            | BlueTooth Rx                | PB11         |     |
| 6            | BlueTooth Tx                | PB10         |     |
| 7            | BlueTooth On/Off            | PA7          |     |
| 8            | Sensor de linea On/Off      | PA6          |     |
| 9            | Bocina                      | PA5          |     |
| 10           | Motor On/Off                | PA4          |     |
| 11           | Motor izquierdo             | PA3          |     |
| 12           | Motor derecho               | PA2          |     |
