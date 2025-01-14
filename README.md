Developed a surgically implantable mechatronic pump designed in three phases for patients suffering from end stage heart failure:- Levitation phase: Implemented a Magnetic & Hydrodynamic levitation of an impeller without any contact bearings delivering speed at 1800-4000 rpm with 10 ltr/min maximum flow rate. Drive Electronics phase: Designed a PCB to interface DRV10983-Q1 motor driver IC and MSP430G2553 MCU for control based sinusoidal drive currents providing Torque (BEMF constant) > 30 mN with an accuracy of 2 rpm. Monitoring phase: OLED interfaced with MSP-EXP430G2 TI Launchpad to monitor device health parameters such as battery percentage indication, speed, power etc.

BlocK Diagram:<br />
![image](https://github.com/mvipinchand/3rd-Gen-Left-Ventricular-Assist-Device-Capstone-Project---ISRO-IISU-/assets/73341926/52d09ab1-8cd7-4faf-bf79-af50dab00e71)

Levitation Phase:<br />
Levitation systems utilized in third-generation rotary blood pumps suspend the moving impeller within the blood field without any mechanical contact. The magnetic and hydrodynamic levitation of the impeller without any contact bearings with the pump is the major advancement of the third-generation pumps.<br /> 
![image](https://github.com/mvipinchand/3rd-Gen-Left-Ventricular-Assist-Device-Capstone-Project---ISRO-IISU-/assets/73341926/2df7bd86-dff4-47d6-bf6f-1dd3d746057e)<br />	
The suspended impeller reduces heat generation, increases endurance and also the spiral groove hydrodynamic bearing are a backup in case primary magnetic bearing fails (in larger size LVAD pumps). The rotation speed is 1800-4000 rpm with 10 l/min maximum flow rate. Magnetic bearings over high reliability, show no wear or abrasion and can be used in a high-vacuum environment without the need for lubrication. They show no stiction and have very low rotational losses. They are not susceptible to temperature changes and should be less expensive to produce than conventional ball-bearings due to less demanding manufacturing tolerances. These properties are appreciated for satellite reaction/momentum wheels, which have to operate at high rotational speeds in a vacuum for long periods of time. This section describes the design suspension electronics for magnetic bearing used in Magnetic Suspension Reaction Wheels (MSRW).

Drive Electronics:<br />
This section of our LVAD system was implemented by designing a PCB to drive either a brushless DC electric motor (BLDC motor) or a permanent magnet synchronous motor (PMSM) which has ability to provide Torque (BEMF constant) > 30 mN, in the speed range of 1800-4000 rpm with an accuracy of  2 rpm. Only such a motor will be able to overcome both the Cogging Torque and friction due to blood flow. The design also provides access to proprietary sensorless control (unlike the normal ones using Hall sensors for position tracking) and the ability to tune motor parameters for optimizing performance according to the end-application needs<br />
![image](https://github.com/mvipinchand/3rd-Gen-Left-Ventricular-Assist-Device-Capstone-Project---ISRO-IISU-/assets/73341926/ae6d8c7b-9f76-4a21-a6d9-e4cb1c66464a)



Click link to watch the project fuctioning:
https://www.youtube.com/watch?v=Lj_ukoOZl54
