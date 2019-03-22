Sensor Challenge in C++
---
@title[Polling the sensor]


@snap[north-east template-note text-gray]
Code presenting repository source file template.
@snapend

+++?color=lavender @title[Fenced Code Block]

```C++
int main(void)
{
    sensor* GravitySensor;

    printk("Using Bosch BMI160\n");
    bmi160 bmi160;

    GravitySensor = &bmi160;

    printk("Testing the polling mode.\n");

    GravitySensor->Poll();
	
	printk("Testing the polling mode finished.\n");

	return 0;
}
```
---
Slide 2
