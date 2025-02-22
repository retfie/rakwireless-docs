---
rak_desc: Provides comprehensive information for your RAK12017 to help you use it. This information includes technical specifications, characteristics, and requirements, and it also discusses the device components.
rak_img: /assets/images/wisblock/rak12017/overview/RAK12017_home.png
tags:
  - datasheet
  - wisblock
  - RAK12017
prev: ../Quickstart/
next: false
---

# RAK12017 WisBlock IR Detection Module Datasheet

## Overview

### Description

The RAK12017 is an IR detection module. This module uses ITR20001 optical switch from Everlight to detect whether the IR Signal reflects. Sample applications of this module are: to identify if an object is approaching and check changes between black and white lines. 


### Features

- Detect whether IR Signal is reflected back
- λP=940&nbsp;nm
- 3.3&nbsp;V Power supply
- Infrared Line Tracking Range: 1&nbsp;cm to 5&nbsp;cm
- Module Size: 15&nbsp;mm x 25&nbsp;mm

## Specifications

### Overview 

#### Mounting

The RAK12017 WisBlock IR Detection Module can be mounted to IO slot of the WisBlock Base board. **Figure 1** shows the mounting mechanism of the RAK12017 on a WisBlock Base board, such as the [RAK5005-O](https://store.rakwireless.com/products/rak5005-o-base-board).

<rk-img
  src="/assets/images/wisblock/rak12017/datasheet/mounting.png"
  width="60%"
  caption="RAK12017 WisBlock IR Detection Module Mounting"
/>

::: tip 📝 NOTE
- RAK12017 has a connector(default NC), and if you need to get the module out of WisBlock Base board, you can solder it with cable and [RAK13003 WisBlock IO Expansion Module](https://store.rakwireless.com/products/io-expansion-module-rak13003) to position the module however you like.
:::

### Hardware
The hardware specification is categorized into four parts. It discusses the pinouts and their corresponding functions and diagrams of the module. It also covers the electrical and mechanical parameters that include the tabular data of the functionalities and standard values of the RAK12017 WisBlock IR Detection Module.

#### Pin Definition

The RAK12017 WisBlock IR Detection Module comprises a standard WisIO connector. The WisIO connector allows the RAK12017 module to be mounted to a WisBlock baseboard, such as RAK5005-O. The pin order of the connector and the pinout definition is shown in **Figure 2**.

::: tip 📝 NOTE
- **3V3_S**, **GND**, **AIN1**, **OUT** are connected to WisIO connector.
:::

 <rk-img
  src="/assets/images/wisblock/rak12017/datasheet/RAK12017_Pinouts.svg"
  width="80%"
  caption="RAK12017 WisBlock IR Detection Module Pinout"
/>
  

#### Electrical Characteristics


| Symbol   | Description            | Min. | Nom. | Max. | Unit |
| -------- | ---------------------- | ---- | ---- | ---- | ---- |
| VDD      | Power supply           | -    | 3.3  | -    | V    |
| λP       | Peak Wavelength        | -    | 940  | -    | nm   |
| VF       | Forward Voltage        | -    | 1.2  | 1.5  | V    |
| IF       | Forward Current        | 18   | 21   | -    | ma   |
| ICEO     | Dark Current           | -    | -    | 100  | nA   |
| VCE(sat) | C-E Saturation Voltage | -    | -    | 0.4  | V    |
| tR       | Rise Time              | -    | 25   | -    | us   |
| tF       | Fall Time              | -    | 25   | -    | us   |

#### Mechanical Characteristics

##### Board Dimensions

**Figure 3** shows the dimensions and the mechanical drawing of the RAK12017 module.

 <rk-img
  src="/assets/images/wisblock/rak12017/datasheet/mechanical-drawing.png"
  width="60%"
  caption="RAK12017 WisBlock IR Detection Module Dimensions"
/>


##### WisConnector PCB Layout

<rk-img
  src="/assets/images/wisblock/rak12017/datasheet/pcb_footprint.png"
  width="100%"
  caption="WisConnector PCB Footprint and Recommendations"
/>


#### Schematic Diagram

<rk-img
  src="/assets/images/wisblock/rak12017/datasheet/schematic.png"
  width="75%"
  caption="WisConnector and RAK12017 Schematic"
/>

::: tip 📝 NOTE
- **3V3_S** is supported by WisBase.
- **AIN1** is an analog input.
- The voltage depends on reflection strength.
- The reverse level of MCP606 can be adjusted by indicator.
- **D1** is an LED used as an indicator light.
- **J2** is used for cable when the module is out of the base.
:::
​      


