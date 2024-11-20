# Tracking Via Ultra-wideband(UWB)+GPS+LoRa
A high-precision tracking module designed for close-range tracking via ultra-wideband and long-distance tracking via GPS.

## 🚩 Table of Contents

- [Project Description](#-project-description)
- [Schematics](#-schematics)
- [PCB Design Properties and Specifications](#-pcb-design-properties-and-specifications)
- [Board Presentation](#-board-presentation)
- [Bill of Materials](#-bill-of-materials)
- [Version History](#-version-history)
- [Download Project Files](#-download-project-files)
- [Used By](#-used-by)
- [License](#-license)



## UWB Specifics 
### Module Positioning (UWB)
The antenna-related diagrams below are references from the DWl001 Datasheet. 
The DWM1001 antenna is vertically polarised, meaning that the module is intended to be positioned vertically
upright when used in an RTLS system. 

<img src="https://github.com/user-attachments/assets/6196ac97-3b40-405a-8ca4-8553dbd1e030"/>

### Antenna Characteristics (DW1001)
<img src="https://github.com/user-attachments/assets/7524e91a-64d2-4c9a-a782-98cdc63d85e7"/>



### UWB Chip Placement Guidelines (DW1001)
The proximity of the DWM1001 on-board
antenna to metal and other non-RF transparent materials needs to be considered carefully.
For best RF performance, ground copper should be flooded in all areas of the application board, except
in the areas marked “Keep-Out Area”, where there should be no metal on either side, above or below (e.g.
do not place any battery under the antenna).

![keepout](https://github.com/user-attachments/assets/3528bf69-dfea-45ba-84cc-e1a84dd0264f)
