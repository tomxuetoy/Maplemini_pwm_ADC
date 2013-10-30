Maplemini_pwm_ADC
=================

the official example of Maple mini pwm output and ADC input, note: BUG on official page

Official page http://leaflabs.com/docs/lang/api/pwmwrite.html#lang-pwmwrite contains **BUG**

pinMode(BOARD_LED_PIN, OUTPUT);   // sets the LED pin as output

should be 

pinMode(BOARD_LED_PIN, PWM);   // sets the LED pin as pwm
