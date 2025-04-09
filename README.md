# Boardoza TP4056 Lithium Battery Charging & UPS Module

The **Boardoza TP4056 Module** is a versatile and compact **1-cell lithium-ion/lithium-polymer battery charging and power management module**, based on the widely-used TP4056 chip. It combines safe charging with UPS (uninterruptible power supply) capability, making it ideal for battery-powered embedded systems, IoT devices, and portable electronics.

This module integrates **over-voltage, over-current, and thermal protection** features, ensuring safe and reliable operation. Its **Type-C input** offers modern and universal compatibility for power delivery. With **dual status LEDs**, onboard battery terminals, and efficient regulation, it's a great addition to any low-power project requiring rechargeable battery integration.

## [Click here to purchase!](https://www.ozdisan.com/maker-ve-iot-urunleri/boardoza/boardoza-modulleri/TP4056-BREAKOUT-BOARD/1065568)

|Front Side|Back Side|
|:---:|:---:|
| ![Quectel FC41D Front](./assets/TP4056%20Front.png)| ![Quectel FC41d Back](./assets/TP4056%20Back.png)|

---

## Key Features

- **Comprehensive Protection Systems:** Built-in over-current, over-voltage, and thermal protection mechanisms ensure battery safety.
- **High Efficiency Charging:** Optimized 4.2V charging with up to 1A current for fast and controlled recharging.
- **UPS Capability:** Allows simultaneous charging and powering of the load, suitable for uninterrupted operation.
- **Modern Input Interface:** Type-C USB input for reliable and reversible power connections.
- **Compact Footprint:** Fits into space-constrained enclosures or mobile designs with ease.

---

## Technical Specifications

**Model:** TP4056  
**Input Voltage:** 5V  
**Power Input Type:** Type-C USB  
**Functions:** 1S Li-ion / Li-Po Battery Charging, Mini UPS  
**Charge Voltage:** 4.2V Fixed  
**Charge Current:** Up to 1A  
**Operating Temperature:** -10°C ~ +70°C  
**Board Dimensions:** 20mm x 40mm  

---

## Status LEDs

| Charge State         | Red (Charge) | Green (Standby) |
|----------------------|--------------|-----------------|
| Charging             | ON           | OFF             |
| Charge Termination   | OFF          | ON              |
| No Battery           | OFF          | OFF             |
| Low Voltage Input    | OFF          | OFF             |

---

## Board Pinout

### ( J1 ) Battery Terminal

| Pin Number | Pin Name | Description             |
|:----------:|:--------:|-------------------------|
| 1          | BAT+     | Positive Battery Terminal |
| 2          | BAT-     | Negative Battery Terminal |

### ( J2 ) Power Output Connector

| Pin Number | Pin Name | Description      |
|:----------:|:--------:|------------------|
| 1          | V+       | Regulated Voltage Output |
| 2          | GND      | Ground           |

---

## Board Dimensions

<img src="./assets/TP4056 Dimension.png" alt="Board Dimensions" width="550"/>

---

## Step Files

[Boardoza TP4056.step](./assets/TP4056%20Step.step)

---

## Datasheet

[TP4056 Datasheet.pdf](./assets/TP4056%20Datasheet.pdf)

---

## Version History

- V1.0.0 – Initial Release

---

## Support

For technical questions, please contact **<support@boardoza.com>**

---

## License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]  

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].  

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]  

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/  
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png  
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
