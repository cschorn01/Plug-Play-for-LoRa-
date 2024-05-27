# PlugAndPlayForLoRa

[![By Chris Schorn](https://img.shields.io/badge/Author-Chris_Schorn-FFFFFF?style=for-the-badge)](https://github.com/cschorn01)
![Status](https://img.shields.io/badge/Status-Working-FFFFFF?style=for-the-badge)
[![Download Repository Zip](https://img.shields.io/badge/Download_Repository_Zip-FFFFFF?style=for-the-badge)](https://github.com/cschorn01/PlugAndPlayForLoRa/archive/refs/heads/main.zip)

[![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)](https://www.arduino.cc/)
[![Semtech LoRa](https://img.shields.io/badge/LoRa-1CAEED?style=for-the-badge)](https://www.semtech.com/lora)
[![DLP Design](https://img.shields.io/badge/DLP_Design-0D6696?style=for-the-badge)](https://www.dlpdesign.com/rf/rfs1280.php)
[![Tindie](https://img.shields.io/badge/tindie-113C77?style=for-the-badge)](https://www.tindie.com/products/olivetreelabs/24ghz-lora-arduino-shield/)


[![Description](https://img.shields.io/badge/Description-FFFFFF?style=for-the-badge)](https://github.com/cschorn01/PlugAndPlayForLoRa/tree/main#)
[![Functionality](https://img.shields.io/badge/Functionality-FFFFFF?style=for-the-badge)](https://github.com/cschorn01/PlugAndPlayForLoRa/tree/main#-1)
[![File Structure](https://img.shields.io/badge/file_structure-FFFFFF?style=for-the-badge)](https://github.com/cschorn01/PlugAndPlayForLoRa/tree/main#-2)
[![How to Use](https://img.shields.io/badge/how_to_use-FFFFFF?style=for-the-badge)](https://github.com/cschorn01/PlugAndPlayForLoRa/tree/main#-3)
[![Issues](https://img.shields.io/badge/issues-FFFFFF?style=for-the-badge)](https://github.com/cschorn01/PlugAndPlayForLoRa/tree/main#-4)

<!-- [![DLP-RFS1280 Arduino Shield](https://github.com/cschorn01/images/blob/main/Olive%20Tree%20Labs/IMG_0547.jpg)](https://www.tindie.com/products/olivetreelabs/24ghz-lora-arduino-shield/ "Buy on Tindie") -->


<a href="https://www.tindie.com/products/olivetreelabs/24ghz-lora-arduino-shield/" target="_blank">
  <img src="https://github.com/cschorn01/images/blob/main/Olive%20Tree%20Labs/IMG_0547.jpg" alt="DLP-RFS1280 Arduino Shield" width="45%" height="auto" title="Buy on Tindie">
</a>


<!-- [![Stargazers repo roster for @cschorn01/4GHz_Lora_for_Arduino](https://reporoster.com/stars/cschorn01/2.4GHz_Lora_for_Arduino)](https://github.com/cschorn01/PlugAndPlayForLoRa/stargazers) -->

<!-- ![GitHub Contributors Image](https://contrib.rocks/image?repo=cschorn01/rpi_pico_lora_template) -->

<!-- [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=cschorn01&layout=compact&theme=dark)](https://github.com/cschorn01/Lora_Pico_Driver) -->

## ![Description](https://img.shields.io/badge/Description-FFFFFF?style=for-the-badge)
<!-- This is a library meant for the Arduino IDE. It is based on the code from my [rpi_pico_lora_template](https://github.com/cschorn01/rpi_pico_lora_template/blob/main/README.md), which uses FreeRTOS on the Raspberry Pi Pico to allow for more expandability. However, this library is aimed at hobbyists using either the Pi Pico or any of the other boards supported by the Arduino IDE to expand their long range networking capabilities. The LoRa Modem of choice is the [Semtech sx1280](https://www.semtech.com/products/wireless-rf/lora-connect/sx1280). This gives access to the 2.4GHz spectrum which is useable without a license worldwide, sharing the frequency with [Bluetooth and WiFi](https://semtech.my.salesforce.com/sfc/p/#E0000000JelG/a/44000000MDcO/Ll4bon.4HPwcyXv9fegcfcgbpvLYd7Lx_aZLMzYNLIQ). -->

<!-- This Arduino library alows for streamlined use of the [Semtech sx1280 LoRa Radio](https://www.semtech.com/products/wireless-rf/lora-connect/sx1280) over SPI communication for point to point messaging. Meant to enable hobbyists worldwide by allowing long range radio transmission without license on the 2.4 GHz frequency. -->

The Arduino LoRa Shield is a versatile add-on board for Arduino compatible microcontrollers, designed to enable long-range wireless communication using the LoRa modulation technique. This shield incorporates a 2.4GHz LoRa module, providing reliable connectivity over extended distances while consuming minimal power. Coupled with the LoRa PHY Arduino library, users can seamlessly integrate the shield into their projects and leverage its capabilities for various applications, including remote sensing, telemetry, and IoT (Internet of Things) deployments.

Additionally, the LoRa PHY Arduino library simplifies the process of learning LoRa technology, offering a user-friendly interface and comprehensive documentation. With easy-to-understand functions and example sketches, beginners can quickly grasp the fundamentals of LoRa communication, while advanced users can delve into more complex applications with confidence. This combination of hardware and software makes the Arduino LoRa Shield an excellent educational tool for teaching and learning LoRa technology.

## ![Functionality](https://img.shields.io/badge/Functionality-FFFFFF?style=for-the-badge)

<!-- Three functions are made available to use:

1. `sx1280Setup` prepares the sx1280 Lora module for message transmission or reception by setting the message and buffer parameters. 
2. `sx1280Tx` sets the sx1280 module parameters for  message transmission, and the IRQ, which will alert the Arduino when the message is sent. Once a message is transmitted the IRQ will read `0x01`.
3. `sx1280Rx` sets the sx1280 module parameters for message reception, and the IRQ, which will alert the Arduino if a message is received. If a message is received this function will fill the array passed to it with the message data. -->

1. **Long-Range Communication**: Utilizes LoRa modulation to achieve extended communication range, making it ideal for applications requiring connectivity over large distances.
2. **Low Power Consumption**: Designed to operate efficiently, minimizing power consumption to prolong battery life in battery-powered applications.
3. **Plug and Play Integration**: Seamlessly integrates with Arduino compatible microcontrollers, allowing for easy setup and configuration.
4. **Versatile Applications**: Suitable for a wide range of applications, including environmental monitoring, asset tracking, and remote control systems.

## ![File Structure](https://img.shields.io/badge/file_structure-FFFFFF?style=for-the-badge)

- :file_folder: [examples](https://github.com/cschorn01/2.4GHz_Lora_for_Arduino/tree/main/examples)
- :file_folder: [src](https://github.com/cschorn01/PlugAndPlayForLoRa/tree/main/src) 
  - :page_facing_up: [sx1280OverSpi.cpp](https://github.com/cschorn01/PlugAndPlayForLoRa/blob/main/src/sx1280OverSpi.cpp)  
  - :page_facing_up: [sx1280OverSpi.h](https://github.com/cschorn01/PlugAndPlayForLoRa/blob/main/src/sx1280OverSpi.h)
- :page_facing_up: [README.md](https://github.com/cschorn01/PlugAndPlayForLoRa/blob/main/README.md)  
- :page_facing_up: [keywords.txt](https://github.com/cschorn01/PlugAndPlayForLoRa/blob/main/keywords.txt)
- :page_facing_up: [library.properties](https://github.com/cschorn01/PlugAndPlayForLoRa/blob/main/library.properties)

## ![How to Use](https://img.shields.io/badge/how_to_use-FFFFFF?style=for-the-badge)

<!-- Each of the functions contain print outs for the serial monitor. In `sx1280Setup` you will only see the busy status of the sx1280. `sx1280Rx` prints its *Listening* loop iteration, then breaks and fills the arrays passed in with any received message data. If there was any message data received then it is printed in `void loop`.  `sx1280Tx` prints the IRQ, which if it equals `0x01` the message is sent and the function is exited. If you want to input your own messages you can change the lines which fill the writeData array with 'hi', to input over the serial monitor, which will be added in the examples soon.

There are two examples to aid in a more thorough understanding. The first is for using an Arduino Uno and the second a Raspberry Pi Pico. In each example an sx1280 module called the [DLP-RFS1280](https://www.dlpdesign.com/rf/rfs1280.php) is used. This module has a built in antenna so there is no need to purchase one. I will soon be coming out with an arduino shield for this product to make it even easier to use. -->

1. **Hardware Setup**: Mount the Arduino LoRa Shield onto your Arduino compatible microcontroller. Ensure proper connection of power and communication pins between the shield and the microcontroller.
2. **Software Installation**: Download and install the "2.4GHz Lora for Arduino" Arduino library from the Library manager in the Arduino IDE. Open the included example in your Arduino IDE by navigating to File > Examples > sx1280OverSpi > arduinoSendAndReceive, then selecting the downloaded library file.
3. **Initialization**: Include the "2.4GHz Lora for Arduino" library in your Arduino sketch using #include <sx1280overspi>. Initialize the LoRa module with appropriate settings such as frequency, spreading factor, and transmission power.
4. **Sending Data**: Use the provided functions in the library to transmit data over the LoRa network. Format your data appropriately and call the transmission function with the desired payload.
5. **Receiving Data**: Implement a receiving routine in your Arduino sketch to listen for incoming data packets. Parse the received data and process it according to your application requirements.
6. **Example Sketches**: Explore the example sketches provided with the library to understand basic usage and functionality. Modify and extend these sketches to suit your specific project needs.
7. **Troubleshooting**: Refer to the troubleshooting section in the library documentation for common issues and solutions. Ensure proper antenna connection and signal strength for optimal performance.

## ![Issues](https://img.shields.io/badge/issues-FFFFFF?style=for-the-badge)

- ![Error](https://img.shields.io/badge/Error-A31B34?style=for-the-badge) Arduino IDE output error read `Failed to install library: 'sx1280OverSpi:1.1.0'. No valid dependencies solution found: dependency 'SPI' is not available`
  - ![Solution](https://img.shields.io/badge/Solution-5CBA5B?style=for-the-badge) Deleted the "depends" line from the library.properties file


<div align="center" dir="auto">
  <a href="https://github.com/cschorn01/PlugAndPlayForLoRa">
    <img src="https://img.shields.io/badge/Back_To_Top-FFFFFF?style=for-the-badge" alt="Back To Top">
  </a>
</div>

