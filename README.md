# R3-SoftwareTask1-Bekhbat Davaatseren
 https://www.tinkercad.com/things/4fJKb4MMd83
 The value from the potentiometer(0-1023) has to turn into values of 0-99. 1023/100= 10.23 meaning the value has a 1:10.23 ratio. Although the math is off its good enough 
Now the 0-99 has to translate to the display each with 0-9 and 0-9.
The idea first is to simply use the raw value of 0-1023 to if statements then to show the first digit.
Then the second digit I had to create another method to take the second digit. (0-1023)/10.23 creates the value that will be shown on the display
The second digit is then taken simply by using modulo or the remainder % method. Then the simple if statements come foward. 
  