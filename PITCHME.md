### Sensor Challenge in C++

+++?color=#1E1F21

@snap[north-west template-note text-white]
#### Arduino 101
@snapend

@snap[west]
![Arduino 101](https://lh3.googleusercontent.com/AyyTzU343m373iH4GLJyuzOHy6wgV7Uemyni10Gjv96ypxZeJc4vnU6U6RXHtXJjcq-85Cu537shT2iBFxj_4BAJrgVWU93cIArFww3m4ne7sFZyvKbE7olRNLhRdmMwNAYWMeuq4lqMpokAoNr4amDPEjd1F7MCMvSBKFMl7GC8Cg4RVJbJRvHKt0c1TTxT9X8LiNJf8azPgbu4ovEu8MeF0RsxNAJbRBgczalCmNm29-IWkUaQlkrdijXAWKyzzEq8n9vssuf2FXWFsnq56fEaWjdgsrZ85-jGv9zEir8a2miORRPQxB40SOT3vCmm2Y-EKt5--qlgj2vCroPj42ASwuD0xjCo3OxeRp94icgRkjnlN5o4mf5WRl--yK632TM52HeaZq5MyArXGHy020ZyBzuMHu_wk4pZo7HL7iBkFb6dUBRIJ-ZqqxH_fwgcmR2thbstmIp4he_nZjSmfYs0JhnUMNgorGV2ob0ecQ8JC9nDbWxoqmEd3hFRI9gSGAd0IyhsQ9RVtKZQv2KLm_f7nMnGbWBitTdFTqRIq7ko9GS7APAbpAW7pCPgXXBv7THlkawKKVJU0eSBgjeiyF7Vh41XuYCE4oIJFF_iWoI6arhaT4PO3bOJPtITovyee6l8nJEA1hp5yg6cm85oSy22zqzL2Mg)
@snapend

+++?color=#1E1F21

@snap[north-west template-note text-white]
#### Quark C1000
@snapend

@snap[west]
![Quark SE](https://www.mouser.se/images/IntelQuarkSE-Fig4.jpg)
@snapend

+++?image=https://www.zephyrproject.org/wp-content/uploads/sites/38/2017/08/zephyr-logo.png&position=left&size=20%&color=#1E1F21
@title[Zephyr RTOS]

@snap[north-west]
Zephyr™ : A SMALL, SCALABLE OPEN SOURCE RTOS FOR IOT EMBEDDED DEVICES
@snapend

@snap[west text-gray]
@quote[...supports multiple hardware architectures, optimized for resource constrained devices, and built with safety and security in mind](The Zephyr™ Project - The Linux Foundation)
@snapend

@snap[south span-100]
@size[0.7em](https://www.zephyrproject.org/what-is-zephyr)
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

