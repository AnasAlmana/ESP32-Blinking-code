# ESP32-Blinking-code
This code is to check if the ESP32 device is running or not. By running this code, if the built-in LED blinked, then the ESP32 is running properly.

## Downlading Arduino IDE:
1- First, we need to download and install Arduino IDE from Mirosoft Store.

2- After installing Arduino IDE, run the program.

3- Connect the ESP32 device to the computer.

## ESP32 LED code to blink:
```
Void setup(){
pinMode(LED_BUILLTIN,OUTPUT);

}

Void loop(){
digitalwrite( LED_BUILTIN, HIGH);
delay(1000);
digitalwrite( LED_BUILTIN, LOW);
delay(1000);

}
```

4- After writing the code above, click verify and save the file.

5- After verifying that there wasn't any error, make sure the ESP32 is connected and then click upload.

6- You will see the built-in LED blinking.
