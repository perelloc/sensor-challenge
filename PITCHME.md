Sensor Challenge in C++
---
@title[Code Presenting Templates]

a

+++?code=the-template-master/template/src/go/server.go&lang=golang
@title[Repo Source File]

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
