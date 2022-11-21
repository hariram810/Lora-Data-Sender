# Lora-Data-Sender


![1](https://user-images.githubusercontent.com/118633170/202869681-c2ddbfcf-8b37-4b75-a492-fcdda801e689.png)


if you have hard-time 3d printing stuff and other materials which i have provided in this project please refer the professionals for the help, [JLCPCB](https://jlcpcb.com) is one of the best company from shenzhen china they provide, PCB manufacturing, PCBA and 3D printing services to people in need, they provide good quality products in all sectors



Please use the following link to register an account in [JLCPCB](https://jlcpcb.com)

https://jlcpcb.com/RNA


Pcb Manufacturing

2 layers

4 layers

6 layers



PCBA Services

[JLCPCB](https://jlcpcb.com) have 350k+ Components In-stock. You don’t have to worry about parts sourcing, this helps you to save time and hassle, also keeps your costs down.

Moreover, you can pre-order parts and hold the inventory at [JLCPCB](https://jlcpcb.com), giving you peace-of-mind that you won't run into any last minute part shortages.


3d printing


SLA -- MJF --SLM -- FDM -- & SLS. easy order and fast shipping makes JLCPCB better companion among other manufactures try out [JLCPCB](https://jlcpcb.com) 3D Printing servies

[JLCPCB](https://jlcpcb.com) 3D Printing starts at $1 &Get $54 Coupons for new users


The DHT22 is a basic, low-cost digital temperature and humidity sensor. It uses a capacitive humidity sensor and a thermistor to measure the surrounding air, and spits out a digital signal on the data pin (no analog input pins needed). It's fairly simple to use, but requires careful timing to grab data. The only real downside of this sensor is you can only get new data from it once every 2 seconds, so when using our library, sensor readings can be up to 2 seconds old.


Simply connect the first pin on the left to 3-5V power, the second pin to your data input pin and the rightmost pin to ground. Although it uses a single-wire to send data it is not Dallas One Wire compatible! If you want multiple sensors, each one must have its own data pin.

Compared to the DHT11, this sensor is more precise, more accurate and works in a bigger range of temperature/humidity, but its larger and more expensive.

Comes with a 4.7K - 10K resistor, which you will want to use as a pullup from the data pin to VCC.


The BMP280 Digital Barometer is developed by Bosch Sensortec. Compared with the previous BMP085, BMP180, and BMP183, this BMP280 barometer comes with a higher performance and the smallest size in the industry.

The BMP280 is an absolute barometric pressure sensor especially designed for mobile applications. The sensor module is housed in an extremely compact 8-pin metal-lid LGA package with a footprint of only 2.0x2.5mm2 and 0.95mm package height. Its small dimensions and low power consumption of 2.7μA@1Hz allow the implementation in battery-driven devices such as mobile phones, GPS modules or watches. It supports two types of communication: I2C and SPI.


Power

? VCC: power pin. The working voltage for the chip is 1.71-3.6V. Since the module integrates a 3.3V voltage regulator, the power supply can be either 3.3V or 5V. If you are using an Arduino board, you're recommended to use a 5V power supply.

? 3.3V: the output of the voltage regulator, meaning you can provide the chip with a 3.3V for power here.

? GND: common ground for power and logic.BMP280 supports I2C and SPI communication and the module keeps both ports. If you want to connect a simple circuit, you can use the I2C port; to connect multiple sensors, you can use the SPI port free of I2C address collisions.


I2C interface


The I2C interface uses the following pins:

? SCK: serial clock (SCL)

? SDI: data (SDA)

? SDO: The I2C address decides the pin. If SDO connects to GND(0), the address is 0x76, if it connects to VDDIO(1), the address is 0x77. In this module, we have connected it to VDDIO, so the address should be 0x77.

? CSB: Must be connected to VDDIO to select I2C interface.

SPI interface

The SPI interface uses the following pins:

? CSB: chip select, active low and has an integrated pull-up resistor

? SCK: serial clock

? SDI: serial data input; data input/output in 3-wire mode

? SDO: serial data output; hi-Z in 3-wire mode

Experimental Procedures

BMP280 for Arduino

![2](https://user-images.githubusercontent.com/118633170/202869811-b15118c6-4d9b-4072-bd45-6c9a8b8ccaae.png)
![3](https://user-images.githubusercontent.com/118633170/202869814-ec87bda5-8f9d-40b1-90ec-21a0538cc8b3.png)
![4](https://user-images.githubusercontent.com/118633170/202869817-f8d82017-1403-4a78-88bd-4e2e3cee875d.png)


Components

- 1 * SunFounder Uno board

- 1 * USB Cable

- 1 * BMP280 Module

- Several jump wires

- 1* Breadboard

Step1: Build the circuit


You can connect in the following two ways: I2C and SPI, those two ways will be a little different on the Uno R3 and the Mega2560 (as shown below), taking Uno R3 as an example, choose one way and connect successfully, you can move to the next step then

I2C wiring

LoRa and LoRaWAN together define a Low Power, Wide Area (LPWA) networking protocol designed to wirelessly connect battery operated ‘things’ to the internet in regional, national or global networks, and targets key Internet of things (IoT) requirements such as bi-directional communication, end-to-end security, mobility and localization services. The low power, low bit rate, and IoT use distinguish this type of network from a wireless WAN that is designed to connect users or businesses, and carry more data, using more power. The LoRaWAN data rate ranges from 0.3 kbit/s to 50 kbit/s per channel.

LoRa (from "long range") is the physical proprietary radio modulation technique. It is based on spread-spectrum modulation techniques derived from chirp spread spectrum (CSS) technology.[3] It was developed by Cycleo , a company of Grenoble, France, later acquired by Semtech.


LoRaWAN defines the software communication protocol and system architecture. The continued development of the LoRaWAN protocol is managed by the open, non-profit LoRa Alliance, of which SemTech is a founding member.

![33](https://user-images.githubusercontent.com/118633170/202869836-8138ab69-c304-48ce-b7a9-e28f94d9b527.png)


Features

LoRa uses license-free sub-gigahertz radio frequency bands EU868 (863–870/873 MHz) in Europe; AU915/AS923-1 (915–928 MHz) in South America; US915 (902–928 MHz) in North America; IN865 (865–867 MHz) in India; and AS923 (915–928 MHz) in Asia;[6] and 2.4GHz worldwide.[7] LoRa enables long-range transmissions with low power consumption.[8] The technology covers the physical layer, while other technologies and protocols such as LoRaWAN (Long Range Wide Area Network) cover the upper layers. It can achieve data rates between 0.3 kbit/s and 27 kbit/s, depending upon the spreading factor.


LoRa devices have geolocation capabilities used for trilaterating positions of devices via timestamps from gateways.

Step 2:

LoRa PHY

LoRa uses a proprietary spread spectrum modulation that is similar to and a derivative of chirp spread spectrum (CSS) modulation. The spread spectrum LoRa modulation is performed by representing each bit of payload information by multiple chirps of information. The rate at which the spread information is sent is referred to as the symbol rate, the ratio between the nominal symbol rate and chirp rate is the spreading factor (SF) and represents the number of symbols sent per bit of information.[3] The result is an M-ary digital modulation, where the {\displaystyle M=2^{SF}} possible waveforms at the output of the modulator are chirp modulated signals over the frequency interval ({\displaystyle f_{0}-B/2,f_{0}+B/2}) with M different initial frequencies: the instantaneous frequency is linearly increased, and then wrapped to {\displaystyle f_{0}-B/2} when it reaches the maximum frequency {\displaystyle f_{0}+B/2}.

LoRa can trade off data rate for sensitivity with a fixed channel bandwidth by selecting the amount of spread used (a selectable radio parameter). Lower SF means more chirps are sent per second; hence, you can encode more data per second. Higher SF implies fewer chirps per second;

![sd](https://user-images.githubusercontent.com/118633170/202869852-cb698f8c-cd37-48b8-a1ff-f2b9d7b6d29f.png)
![xdedf](https://user-images.githubusercontent.com/118633170/202869853-8c8e0e14-b53a-4f04-9916-bda8ef1e8565.png)


hence, there are fewer data to encode per second. Compared to lower SF, sending the same amount of data with higher SF needs more transmission time, known as airtime. More airtime means that the modem is up and running longer and consuming more energy. The benefit of high SF is that more extended airtime gives the receiver more opportunities to sample the signal power, which results in better sensitivity.[13] The LoRa modem allows changing of the transmission power from 2dBm to 14dBm (433 MHz) or as high as 20dBm (865 MHz to 867 MHz, 915 MHz, and 923 MHz) as per the regulations of each country. Higher transmission power gives the receiver better signal power and better sensitivity, but at the cost of consuming more energy. There are measurement studies of LoRa performance with regard to energy consumption, communication distances, and medium access efficiency.



According to the LoRa Development Portal, the range provided by LoRa can be up to three miles (five kilometers) in urban areas, and up to 10 miles (15 kilometers) or more in rural areas (line of sight).

In addition, LoRa uses forward error correction coding to improve resilience against interference. LoRa's high range is characterized by high wireless link budgets of around 155 dB to 170 dB.Range extenders for LoRa are called LoRaX.

LoRaWAN

Since LoRa defines the lower physical layer, the upper networking layers were lacking. LoRaWAN is one of several protocols that were developed to define the upper layers of the network. LoRaWAN is a cloud-based medium access control (MAC) layer protocol, but acts mainly as a network layer protocol for managing communication between LPWAN gateways and end-node devices as a routing protocol, maintained by the LoRa Alliance.

LoRaWAN defines the communication protocol and system architecture for the network, while the LoRa physical layer enables the long-range communication link. LoRaWAN is also responsible for managing the communication frequencies, data rate, and power for all devices.[17] Devices in the network are asynchronous and transmit when they have data available to send. Data transmitted by an end-node device are received by multiple gateways, which forward the data packets to a centralized network server.[18] Data are then forwarded to application servers.[19] The technology shows high reliability for the moderate load, however, it has some performance issues related to sending acknowledgements.
