# Light-Detection-using-LDR--KiCAD
PCB of Darkness Detector project implemented using LDR and transistor BC547. I have attached BOM, documents, schematics view, 3D design of PCB, and python code from Ki-CAD software in the zipped submitted file.

# Introduction
A circuit that detects darkness or a lack of light is known as a darkness detector or dark detector. In this
project, we've used the LDR, the most basic of all light sensors, to construct a straightforward darkness
detector circuit (Light Dependent Resistor). These darkness detector circuits can be utilised in systems
that switch on lights automatically when it becomes dark. Some parts are passive, such as capacitors and
resistors. LED has been used as an alarm to signal nighttime. This straightforward project's goal is to use
an LDR to detect darkness and an LED to illuminate it.
# Circuit Diagram of Darkness Detector
The following image shows the simple circuit diagram for the Darkness Detector project implemented
using LDR and transistor BC547:

![image](https://github.com/darknight2163/Light-Detection-using-LDR--KiCAD/assets/108399066/bfbba964-f4e4-42b9-9bb1-b5e33bc0bda7)

![image](https://github.com/darknight2163/Light-Detection-using-LDR--KiCAD/assets/108399066/308f78df-1036-4914-b787-385ece164312)

![image](https://github.com/darknight2163/Light-Detection-using-LDR--KiCAD/assets/108399066/6f482878-efe9-4625-b7a4-c8a197c28aca)

# Working
1. In this project, a straightforward darkness detector is created. Transistor and LDR are two
extremely basic components used in the project's implementation (a few passive components as
well). Here, the project's operation is discussed.
2. The LDR's resistance decreases dramatically in the presence of sufficient light. Under these
circumstances, the voltage divider created by the LDR and 1 k resistor will output almost 0V. You
won't see any output at the transistor's output pin as a consequence.
3. The amount of light shining on the LDR will be reduced if we obstruct it with a hand or other
object. The LDR's resistance will rise as resistance does. The light detection will work since an
LED was attached to the transistor IC's output pin. As a result, the LED will be off while there is
sufficient light on the LDR, and it will turn on and shine when it is dark.
# Advantages
1. It is a very straightforward darkness detector with extremely minimal hardware and circuitry.
2. This project may be implemented without the need of any complicated microcontroller circuitry
or programming.
# Disadvantages
1. The system is transistor-controlled; therefore, the outcomes might not be as precise as
anticipated.
# Applications
1. This project may be used in systems that turn on lights automatically when it becomes dark.
2. This circuit may be a component of a larger system or undertaking, such as a home automation or
security system.
