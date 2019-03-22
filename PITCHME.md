Sensor Challenge in C++
+++
@snap[north-west template-note text-white]
Arduino 101
@snapend

@snap[span-100]
![Arduino 101](https://docs.zephyrproject.org/latest/_images/arduino_101.jpg)
@snapend

+++

@snap[north-west template-note text-white]
Quark C1000
@snapend

@snap[span-100]
![Quark SE](https://www.mouser.se/images/IntelQuarkSE-Fig4.jpg)
@snapend

+++@snap[north-west]
The kernel currently provides only a subset of C++ functionality. The following features are not supported:
@snapend

@ul
- Dynamic object management with the new and delete operators
- Run-time type identification
- Exceptions
- Static global object destruction
@ulend

+++@snap[north-west]While not an exhaustive list, support for the following functionality is included:

@ul
- Inheritance
- Virtual functions
- Virtual tables
- Static global object constructor
@ulend



+++?gist=perelloc/1daae7759918dac40e1eb7174ee4929f&lang=c++&color=#1E1F21

@[10-13](generic sensor class)
@[15-30](inheriting gravity/acceleration sensor)

@snap[north template-note text-white]
Polling the sensor
@snapend


+++?gist=perelloc/3288fe83b50f0591eb6081e651c0b802&color=#1E1F21


+++

