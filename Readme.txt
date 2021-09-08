From the simulation on Proteus, one more LED is connected to pin PA6 of the STM32
(negative pin of the LED is connected to PA6). The component suggested in this exercise
is LED-YELLOW, which can be found from the device list.
In this exercise, the status of two LEDs are switched every 2 seconds, as demonstrated in
the figure bellow.
Report 1: Depict the schematic from Proteus simulation in this report. The caption of the
figure is a downloadable link to the Proteus project file (e.g. a github link).

Report 2: Present the source code in the infinite loop while of your project. If a userdefined functions is used, it is required to present in this part. A brief description can be
added for this function (e.g. using comments). A template to present your source code is
presented bellow

1 while (1) {
2 HAL_GPIO_TogglePin (GPIOA , GPIO_PIN_5 );
3 HAL_Delay (1000) ;
4 }