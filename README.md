# MbitBot
* micro:bit motor and sensor shields.
<p align="center">
  <img src="https://github.com/YisrealHung/MbitBotT/blob/master/MbitBot%20pinout%20diagram.jpg" width="280"/>
</p>

# MbitBot_V1.2
* 新增DHT11溫濕度感測器，可搭配空氣品質感測器(PMS3003)組成環境感測聯盟。
* 新增震動感測器Vibration。
  
# Previous Versions
MbitBot_V1.1
* 修正了馬達輸出延遲問題。
* 感謝眾多老師於研習時提供建議，新增馬達控制積木 move Motor at port，
  只需一個積木即可控制一個馬達，數值由-100~100，正值表示正轉，負值為反轉。
* 新增空氣品質感測器PMS3003(G3)，可偵測PM1.0、PM2.5、PM10 。
* 新增可同時設定各伺服馬達的積木，方便老師用於Q腳獸校正。

MbitBot_V1.0
* 換了一個PCA9685 driver，原PCA9685 driver 有些Bug。
* 將原本馬達輸出PWM(0到4095)的控制方式，更換為直覺的0~100%輸出。
* 新增部分Makeblock inventor electronic kit 程式積木。

# Support
MOTOR:
* DC motor X4
* Servo motor X8

CIRCUS IO:
* Push Bottom
* Analog VR
* Relay
* LCD1602 I2C(0x20, 0x27)
* PMS3003(G3)
* DHT11
* Vibration

Makeblock IO:
* Me line Follower
* Me Ultrasonic Sensor
* Me Joystick
* Me Potentionmeter
* Me Sound Sensor

# Reference
* github:microsoft/pxt-neopixel
* https://github.com/lioujj
* https://github.com/DFRobot/pxt-maqueen
