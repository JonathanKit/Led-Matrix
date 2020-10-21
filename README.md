# 16x16Led-Matrix
https://youtu.be/l0b-Z6QaZlE
[![Demo video](http://img.youtube.com/vi/l0b-Z6QaZlE/0.jpg)](http://www.youtube.com/watch?v=l0b-Z6QaZlE "Demo Video")

This resporitory provides a ready to go code to upload on a microcontroller. In my case a ESP8266. The buildinstructions how to build this matrix can be found under https://www.youtube.com/watch?v=D_QBlFIQk-o.
This code features a network clock and a animation mode with different animations controllable by mobile (Blynk)

This code uses following librarys:

  -FastLed 
	
  -NTPClient, to get a precies network time 
	
  -BlynkSimple, when scanning the QR code with the App the project is imported automatically
	
  -LEDMatrix, LEDText, FontMatrise from https://github.com/AaronLiddiment 
  
	
	
Following Hardware:
  -ESP8266
  -256x WS2812B Leds
  -100 watt power supply
  
