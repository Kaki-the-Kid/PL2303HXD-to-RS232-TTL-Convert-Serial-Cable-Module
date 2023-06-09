# PL2303HXD-to-RS232-TTL-Convert-Serial-Cable-Module

|     |     |
| --- | --- |
| ![image max-width: 250px](https://user-images.githubusercontent.com/44589560/225892775-e9538c0c-79ec-41bb-94ca-b78f704b19f2.png)  | ![image](https://user-images.githubusercontent.com/44589560/225892976-89cc2b65-e42e-414e-b59a-2268f055f661.png)  |

Beskrivelse
PL2303HXD to RS232 TTL Convert Serial Cable Module. The PL-2303HXD is a low cost and high performance USB-to-Serial Bridge Controller. The PL-2303HXD provides a convenient solution for connecting an RS-232 full-duplex asynchronous serial device to any Universal Serial Bus (USB) capable host. The PL-2303HXD highly compatible drivers could simulate the traditional COM port on most operating systems allowing the existing applications based on COM port to easily migrate and be made USB ready.

Tekniske detaljer:
Supports RS-232 serial interface with Programmable baud rate from 75 bps to 12 Mbps
Supports RS422/RS485 interface
Extensive flow control mechanism like adjustable high/low watermark level, automatic hardware or software flow control, and inbound data buffer overflow detection
This product is designed for laboratory, product testing, low-cost MCU communications and other applications, there are four lead,

Color:
Red +5 V
Black GND
White RXD
Green TXD
Yellow RTS
Blue CTS

Product Applications:
Single-chip upgrade solution for Legacy RS232 devices to USB interface
USB to RS232 converters/cables/dongles
Healthcare/Medical USB Interface Data Transfer Cable
Personal Infotainment/Media Player Docking USB Interface
Cellular/PDA USB Interface Data Transfer Cable
Serial-over-IP Wireless Solution
USB Barcode/Smart Card Readers
GPS/Navigation USB Interface
Point-of-Sale (POS) Terminals/Printers
PC Docking Station/Port Replicators
Industrial/Instrumentation/Automation Control USB Interface
USB Modem/Wireless/Zigbee USB Interface

![image](https://user-images.githubusercontent.com/44589560/225899659-f9a60b1b-bcfd-4f02-b1ad-219e7f4f3826.png)

## Referencer
* https://www.prolific.com.tw/US/ShowProduct.aspx?p_id=225&pcid=41

## Schematic

|     |     |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/44589560/226277792-edaa1dbe-ae77-4c8d-bec2-070ad1ba1230.png) | ![image](https://user-images.githubusercontent.com/44589560/226277962-3641dbfc-3d53-40d1-9112-d1b312d3dde8.png) |

## Wiring RS422
![image](https://user-images.githubusercontent.com/44589560/226272169-a6c733ac-f699-4368-b2aa-5caf5c2a7ea4.png)

But when I wired this as RS422 as usual it didn't work I didn't receive or send data through Hyper-terminal. But when I wired it as following it worked:

```
  DB9 port pin -->Instrument pin

  pin1 TxD- -----> TxD+
  pin2 TxD+ -----> TxD-
  
  pin3 RxD+ -----> RxD-
  pin4 RxD- -----> RxD+

  pin5 GND to GND
```
It works as above but this is very different than usual wiring. Im really confused what could be the reason?

## Wiring NMEA0183
![image](https://user-images.githubusercontent.com/44589560/226274242-4b115e12-56f8-4af0-b2ff-88d8c4971bfe.png)

![image](https://user-images.githubusercontent.com/44589560/226275398-813a7be2-1616-42ae-ae7e-d068398d7f80.png)

### NMEA0183 References
* https://www.cruiserswiki.org/wiki/NMEA_0183

## Wiring NMEA2000
