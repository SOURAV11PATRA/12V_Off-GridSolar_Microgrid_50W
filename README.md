# 12V_Off-Grid_Solar_Microgrid_50W
<h3 align="center">A personal project originally developed in 2020</h3>

![image alt]()


![image alt]()


Designed and assembled an independent 12V off-grid solar microgrid for domestic supply. This system is engineered for maximum efficiency by utilizing a direct-DC load circuit(PWM solar charge controller), which completely eliminates AC inversion losses and perfectly balances energy generation with the consumption of domestic fixtures.

However, I have also connected an inverter via an MPPT solar charge controller, allowing us to expand the solar panel capacity and run AC loads if desired.

 Hardware Components:-

*   **Photovoltaic Panel:** 50W (Loom Solar)
*   **Charge Controller:** 10A PWM Solar Charge Controller (AmiciSmart)
*   **Battery Storage:** 40Ah Lead-Acid Battery
*   **Output Loads:** Dual 12V DC fans and DC LED lighting fixtures
*   **Safety & Distribution:** Integrated MCBs for circuit protection and manual isolation

## System Architecture & Efficiency Optimization:-

Traditional solar setups often lose 10-15% of their power during the DC-to-AC inversion process. By engineering a purely direct-DC load circuit, this microgrid bypasses the inverter for primary lighting and cooling loads. 

The 50W panel feeds directly into the 10A PWM controller, which regulates the charge to the 40Ah battery. The domestic loads (dual fans and LEDs) draw 12V DC directly from the controller's load terminals or battery, resulting in a near zero-loss conversion chain from generation to consumption.

## Visual Documentation

### Solar Generation
![50W Solar Panel](https://github.com/SOURAV11PATRA/12V_Off-GridSolar_Microgrid_50W/blob/55a5963d12df29266c8830c079b5a1b4b6c9ed9a/images/IMG20260508080818.jpg)
*50W Loom Solar PV Panel.*

### Power Regulation
![10A PWM Charge Controller](https://github.com/SOURAV11PATRA/12V_Off-GridSolar_Microgrid_50W/blob/bbab9331e610b224ec75aff32a4312f465def060/images/IMG20260508081123.jpg)
*AmiciSmart 10A PWM Charge Controller regulating the 12V system.*

### Storage & Distribution Setup
![Battery and Setup](https://github.com/SOURAV11PATRA/12V_Off-GridSolar_Microgrid_50W/blob/bdbe4f8d1d9ed8c256735b46629cacb9fcd65969/images/IMG20260508081103.jpg)
*40Ah Battery storage and main distribution board.*


