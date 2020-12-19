<p><img src="https://github.com/oxinon/IOTA-price-ticker-V2-TTGO-T-Display/blob/master/picture/IOTA-Price-Ticker.png" alt="Cover" width="400"></p>

<br>

<p><img src="https://github.com/oxinon/IOTA-price-ticker-V2-TTGO-T-Display/blob/master/picture/priceticker2.png" alt="Cover" width="600"></p>
<br>
<br>
<b>Update with new Coinmarketcap2 API key</b>
<br>
<br>
Simple IOTA price ticker by using ESP32 based TTGO-T-Display and CoinMarketcap API for the Arduino IDE platform
<br>
IOTA ticker V2 on Youtube: https://youtu.be/vdw2eKsP-xM
<br>
<br>

* * *

<b>Index of this project</b>

+ [Add ESP32 Arduino IDE](#ESP32)
+ [Libraries for Arduino IDE](#libraries)
+ [Case information](#case)

* * *
<br>
<a name="ESP32"></a><h2>Add ESP32 in Arduino IDE</h2>

Before we can start compiling, the Arduino IDE must have the TTGO-T-Display board, based on an ESP32 in the board selection available.
The instruction on https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
In board selector you can select "ESP32 Dev Module" for TTGO-T-Display.
<br>
<br>
For MAC users install the "CP210x USB to UART Bridge VCP Drivers" from Silicon Labs, the port to select is /dev/cu.SLAB_USBtoUART in Arduino IDE under tools-->Port
<br>
https://www.silabs.com/community/interface/knowledge-base.entry.html/2017/01/10/legacy_os_softwarea-bgvU
<br>

<a name="libraries"></a><h2>Libraries for Arduino IDE</h2>
Now we add libraries for Arduino IDE 1.8.7:<br>
The new api requires a developer key, so you must apply for a key to use https://pro.coinmarketcap.com/account
<br>

+ [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) 
+ [CoinMarketCapApi.h](https://github.com/lewisxhe/CoinMarketCapApi2) 
+ [ArduinoJSON](https://github.com/bblanchon/ArduinoJson) version 6.x is testet 
   
The instruction for the "TFT_eSPI" and TTGO-T-Display can be found here https://github.com/Xinyuan-LilyGO/TTGO-T-Display<br>
If you are have problem with the "wifi.h" delete the arduino/libraries/wiFi directory, you can use the esp32 WiFi.h
<br>
<br>
<a name="case"></a><h2>Case information</h2>
You find two files in case directory, .dxf and .stp With the files you can cut stainless steel sheet. I use a laser cuter for this.
<p><img src="https://github.com/oxinon/IOTA-price-ticker-V2-TTGO-T-Display/blob/master/case/case2.png" alt="Cover" width="600"></p>
<br>
<p><img src="https://github.com/oxinon/IOTA-price-ticker-V2-TTGO-T-Display/blob/master/picture/IOTA-Price-Ticker-build.png.jpg" alt="Cover" width="600"></p>

* * *

If you like my work, you can give me a tip for a beer :)<br><br>
<b>IOTA Donate address:</b> 
EDNXLYOLMNKISRPBN99DQOO9RWOHTIGTRQOCXPKTZIUUKNCYJDJUS9XHXSIPEMNNSHZHVQZQSSWWVWSH9GVUYGNQT9 <br>

<p><img src="https://github.com/oxinon/IOTA-price-ticker-V2-TTGO-T-Display/blob/master/picture/qrcode.png" alt="Cover" width="200"></p>
