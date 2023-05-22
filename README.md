# BDHShell (CLI over Serial Terminal)

# Requirments
- [ModusToolbox™ software](https://www.infineon.com/cms/en/design-support/tools/sdk/modustoolbox-software/?redirId=178597) v3.0 or later (tested with v3.0)
- CY8CKIT-062s2-43012
- CY8CKIT-028-SENSE.
- Programming language: C
- Associated parts: All [PSoC™ 6 MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-psoc-arm-cortex-microcontroller/psoc-6-32-bit-arm-cortex-m4-mcu/) parts, [XMC7000 MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-industrial-microcontroller-based-on-arm-cortex-m/), and [AIROC™ CYW20829 Bluetooth® LE SoC](https://www.infineon.com/cms/en/product/promopages/airoc20829/)

# Let's start
## Updating a latest bootloader
To install Modus-Shell, follow these steps:
  1. Open your terminal.<br />
  ![image](https://github.com/sriengchhunchheang/BUU_Infineon/assets/88732241/a8422700-df32-4626-a7a8-90f95861940e)
  2. Change the directory to ModusToolbox/tools_3.0/fw-loader/bin/.<br />
  ```
  $ cd ModusToolbox/tools_3.0/fw-loader/bin/
  ./fw-loader --device-list
  ```
  ![image](https://github.com/Advance-Innovation-Centre-AIC/BDH_Shell_over_Serial_Terminalminal-/assets/88732241/876c9eb6-848a-4195-add0-d0bd521386bc)

  3. Adding the BDH Code Template:
  ``` 
  echo 'https://raw.githubusercontent.com/Advance-Innovation-Centre-AIC/mtb2-bdh-academy-manifests/master/bdh-academy-super-manifest.xml' > ~/.modustoolbox/manifest.loc
  ```
  4. Open Eclipse IDE for ModusToolbox™ and Create the New Apllication <br />
    > Select the board <br />
![image](https://github.com/Advance-Innovation-Centre-AIC/BDH_Shell_over_Serial_Terminalminal-/assets/88732241/d8b4b913-4223-4e6d-b328-317b98dc2e76)
    > Select the project <br />
![image](https://github.com/Advance-Innovation-Centre-AIC/BDH_Shell_over_Serial_Terminalminal-/assets/88732241/94e81668-edfc-4900-b7e9-2bbe215d7813)

# Create the New CLI for the board
## 1. Sample CLI 
### [1.1 Create CLI for check the Temperature from the board](https://github.com/Advance-Innovation-Centre-AIC/BDH_Shell_over_Serial_Terminalminal-/wiki)

## [2. Advance CLI ](https://github.com/Advance-Innovation-Centre-AIC/BDH_Shell_over_Serial_Terminal/wiki/****2.-Advance-CLI)



