# Project-Helix-SV08

Everything I used to modify my Sovol SV08. Will be updated regularly! This is a WiP at the moment.

The next planned upgrade is an improved Double Shear Gantry with 9mm Belts.


# Prerequisites ⚠️

***All the modifications were tested to work on my specific machine. I cannot guarantee that they will work on yours as well, unless you are running the exact same Hardware.*** 

***Im also not an engineer so theres definitely room for improvement in many areas but hey as long as it works!***


# Materials 🗂️

Sunlu Matte HS PETG Black/Jayo ABS Black (Electronics Bay)
Eryone ASA/ABS CF (Structural Parts, Black/Blue)


# Electronics 🔌

This section is split into Electronics Bay and Chamber Electronics for better readability. 
The Printer is running on CAN with the M8P V2.0 being configured as a USB-CAN Bridge with a CB2. The Electronics are mounted to 25cm long DIN rails or 2020 Extrusions. The toolhead is an A4T with Rapido Ace HF Hotend and PT1000 Thermistor.

## Electronics Bay

***MCU's:***

1: BigTreeTech Manta M8P V2.0 (6x BTT TMC2209 V1.3)
2: Meanwell LRS-350-24 PSU + Original SV08 SSR
3: BigTreeTech USB Adapter Board (For CAN communication and safety features)
4: BigTreeTech PI4B Adapter Board + BigTreeTech CB2

***FANS:***

1: 4010 24v Radial for XY Driver cooling
2: 2x 5010 12v for general Airflow
3: 120mm 12v for SSR cooling
4: 3010 24v for CB2 cooling 

## Chamber Electronics

***Toolhead:***

1: BigTreeTech EBB36 Gen2 
2: Delta 2510 5v Hotend Fan
3: 2x GDSTime 4010 24v Radial Part Cooling Fans


***Chamber:***

1: GDSTime 6025 24v Exhaust Fan + 9025 Intake Fan
2: GDSTime 5015 8500rpm 24v Fan (BentoBox)
