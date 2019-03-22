### Sensor Challenge in C++

+++?color=#1E1F21

@snap[north-west template-note text-white]
#### Arduino 101
@snapend

@snap[west]
![Arduino 101](https://docs.zephyrproject.org/latest/_images/arduino_101.jpg)
@snapend

+++?color=#1E1F21

@snap[north-west template-note text-white]
#### Quark C1000
@snapend

@snap[west]
![Quark SE](https://www.mouser.se/images/IntelQuarkSE-Fig4.jpg)
@snapend

+++?color=#1E1F21
@title[Zephyr RTOS]

@snap[north-west]
Zephyr™: A SMALL, SCALABLE OPEN SOURCE RTOS FOR IOT EMBEDDED DEVICES
@snapend

@snap[west text-gray span-120]
The Zephyr™ Project is a scalable real-time operating system (RTOS) supporting multiple hardware architectures, optimized for resource constrained devices, and built with safety and security in mind.
@snapend

+++?color=#1E1F21

@title[C++ functionality not yet supported in Zephyr]

@snap[north-west]
C++ functionality not yet supported in Zephyr:
<br><br>
@snapend

@snap[west list-content-verbose text-gray]
@ul[](false)
- Dynamic object management with the new and delete operators
- Run-time type identification
- Exceptions
- Static global object destruction
@ulend
@snapend

+++?color=#1E1F21

@title[C++ functionality supported in Zephyr]

@snap[north-west]
While not an exhaustive list, support for the following functionality is included:
<br><br>
@snapend

@snap[west list-content-verbose text-gray]
@ul[](false)
- Inheritance
- Virtual functions
- Virtual tables
- Static global object constructor
@ulend
@snapend

+++?gist=perelloc/1daae7759918dac40e1eb7174ee4929f&lang=c++&color=#1E1F21

@[10-13](generic sensor class)
@[15-30](inheriting gravity/acceleration sensor)

@snap[north template-note text-white]
Polling the sensor
@snapend


+++?gist=perelloc/3288fe83b50f0591eb6081e651c0b802&color=#1E1F21


+++

