# Build Guide

A trackpad build guide for the Corne keyboard.

## Parts
| Name | Number | Notes | 
|:-|:-|:-|
| Adapter PCB | 1 |
| Connector PCB | 1 | v1 or v2, based on the sensor mount type
| [Elite-C](https://keeb.io/products/elite-c-usb-c-pro-micro-replacement-arduino-compatible-atmega32u4) | 1 |
| [BlackBerry 8520 trackpad](https://www.ebay.com/i/281933297131) | 1 |
| [TXB0106PWR](https://www.digikey.com/product-detail/en/texas-instruments/TXB0106PWR/296-23759-1-ND/1951146) | 1 | Bidirectional level shifter 5V <-> 2.85V
| [DF30FB-20DS-0.4V](https://www.digikey.com/product-detail/en/hirose-electric-co-ltd/DF30FB-20DS-0.4V(82)/H11591CT-ND/1949227) | 1 | SMD connector for BB8520 
| [LT1117CST-2.85](https://www.digikey.com/product-detail/en/linear-technology/LT1117CST-2.85%23PBF/LT1117CST-2.85%23PBF-ND/890802) | 1 | 2.85V DC Regulator
| [Mill-Max sockets](https://www.digikey.com/product-detail/en/mill-max-manufacturing-corp/315-43-164-41-003000/ED4764-64-ND/1212143) | 1 |
| [Mill-Max pins](https://www.digikey.com/product-detail/en/mill-max-manufacturing-corp/3320-0-00-15-00-00-03-0/ED1134-ND/4147392) | 50 |
| [10 Position Cable Socket](https://www.digikey.com/product-detail/en/samtec-inc/IDSD-05-D-20.00-T/SAM8929-ND/3679935) | 1 | Or any compatible
| [Connector header 10POS 2.54MM](https://www.digikey.com/product-detail/en/amphenol-icc-fci/67997-410HLF/609-3243-ND/1878475) | 1 |
| [Capacitor 10uF](https://www.digikey.com/product-detail/en/kemet/T491C106K010AT/399-3731-1-ND/819056) | 2 |
| [Capacitor 100pF](https://www.digikey.com/product-detail/en/samsung-electro-mechanics/CL21C101JC61PNC/1276-2569-1-ND/3890655) | 3 |
| [Capacitor 0.1uF](https://www.digikey.com/product-detail/en/kemet/C0805X104K4RACTU/399-5331-1-ND/1842310) | 3 |
| [Resistor 2.5k](https://www.digikey.com/product-detail/en/vishay-thin-film/PTN0805E2501BST1/764-1508-1-ND/7103292) | 2 |
| [Resistor 3.3k](https://www.digikey.com/product-detail/en/panasonic-electronic-components/ERJ-PB6B3301V/P20651CT-ND/6214906) | 2 |
| [Resistor 220k](https://www.digikey.com/product-detail/en/panasonic-electronic-components/ERA-6AEB224V/P220KDACT-ND/1466003) | 2 |
| Spacer M2 10mm | 4 |

![List](https://user-images.githubusercontent.com/8005242/55285775-b28e5800-5346-11e9-8c32-920e328bca29.JPG)

## Options
There are two options for the BlackBerry 8520 sensor mount:
- v1 connector PCB - with flex cable. The sensor is mounted directly on the 'H' keycap.
- v2 connector PCB - no flex mount. The sensor is mounted directly on the connector PCB.

This build guide shows the v2 option, but v1 is very similar from the build perspective.

## Build Steps

#### 1. TXB0106PWR
![1](https://user-images.githubusercontent.com/8005242/55286152-b45b1a00-534c-11e9-92e7-a0a4ce89b9d1.JPG)

#### 2. 2.85V DC Regulator
![2](https://user-images.githubusercontent.com/8005242/55286153-b45b1a00-534c-11e9-8970-07a5e1bbaec8.JPG)

#### 3. Capacitors 10uF
![3](https://user-images.githubusercontent.com/8005242/55286154-b45b1a00-534c-11e9-953f-c5bd2d4f7251.JPG)

#### 4. Capacitors 0.1uF
![4](https://user-images.githubusercontent.com/8005242/55286155-b45b1a00-534c-11e9-9d50-7289af5e4da7.JPG)

#### 5. Capacitors 100pF
![5](https://user-images.githubusercontent.com/8005242/55286156-b45b1a00-534c-11e9-826a-aa754bbfc532.JPG)

#### 6. Resistors 2.5k
![6](https://user-images.githubusercontent.com/8005242/55286157-b4f3b080-534c-11e9-923a-f740519a293c.JPG)

#### 7. Resistors 3.3k
![7](https://user-images.githubusercontent.com/8005242/55286158-b4f3b080-534c-11e9-87e9-add114edfdd1.JPG)

#### 8. Mill-Max sockets
![8](https://user-images.githubusercontent.com/8005242/55286159-b4f3b080-534c-11e9-9516-7537df99b1c7.JPG)
![9](https://user-images.githubusercontent.com/8005242/55286160-b58c4700-534c-11e9-81f5-a58333e14482.JPG)

#### 9. Solder Mill-Max pins to Elite-C
![10](https://user-images.githubusercontent.com/8005242/55286161-b58c4700-534c-11e9-9168-623ee257b967.JPG)
![11](https://user-images.githubusercontent.com/8005242/55286162-b58c4700-534c-11e9-9efb-fe647e5982fb.JPG)
![12](https://user-images.githubusercontent.com/8005242/55286164-b624dd80-534c-11e9-8195-a4a91b826c4f.JPG)

#### 10. Connector header 10POS
![13](https://user-images.githubusercontent.com/8005242/55286165-b624dd80-534c-11e9-99c6-a88c51486a18.JPG)

#### 11. SMD connector for BB8520, reqires small soldering tip
![14](https://user-images.githubusercontent.com/8005242/55286166-b6bd7400-534c-11e9-9298-4bff27a99309.JPG)

#### 12. 0.1uF and 100pF capacitors 
![15](https://user-images.githubusercontent.com/8005242/55286167-b6bd7400-534c-11e9-97d9-6d7388963aed.JPG)

#### 13. Resistors 220k
![16](https://user-images.githubusercontent.com/8005242/55286168-b6bd7400-534c-11e9-823e-ff1ebb3b0707.JPG)

#### 14. Prepare and solder connector cable.
![17](https://user-images.githubusercontent.com/8005242/55286169-b7560a80-534c-11e9-85f0-7da56cfa428e.JPG)
![18](https://user-images.githubusercontent.com/8005242/55286171-b7560a80-534c-11e9-8c57-db8f35981fe6.JPG)
![19](https://user-images.githubusercontent.com/8005242/55286172-b7560a80-534c-11e9-9382-518e60418033.JPG)
![20](https://user-images.githubusercontent.com/8005242/55286173-b7eea100-534c-11e9-99b8-4013a56d7e59.JPG)

#### 15. Connect and glue Trackpad sensor to the PCB
![22](https://user-images.githubusercontent.com/8005242/55286175-b8873780-534c-11e9-95e3-2c2e075c4750.JPG)
![23](https://user-images.githubusercontent.com/8005242/55286176-b8873780-534c-11e9-829f-9be68c4ec8e6.JPG)
![24](https://user-images.githubusercontent.com/8005242/55286177-b91fce00-534c-11e9-91d0-e0b70364a1cb.JPG)

#### 16. Solder Mill-Max pins to the Adapter PCB
![21](https://user-images.githubusercontent.com/8005242/55286174-b7eea100-534c-11e9-8534-2cbc675a0996.JPG)

#### 17. Assemble the module
![25](https://user-images.githubusercontent.com/8005242/55286178-b91fce00-534c-11e9-9dd3-ac4dc086ab2a.JPG)

#### 18. Connect to Corne keyboard
![26](https://user-images.githubusercontent.com/8005242/55286179-b91fce00-534c-11e9-9434-f2b575b2b1d0.JPG)
![27](https://user-images.githubusercontent.com/8005242/55286180-b9b86480-534c-11e9-8c8a-0b9ddae888fb.JPG)
