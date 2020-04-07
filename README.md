
# Open**ICU**

The situation of recent months and the COVID-19 pandemic has shown how great a threat there may be insufficient medical resources including life-saving equipment. In a triage situation (https://en.wikipedia.org/wiki/Triage), doctors have to make extremely difficult decisions every day. We offer an **Open Source / Open Hardware device project** for life-saving applications (**_ONLY with no other means available_**) containing "ICU in a suitcase" for **as low as 300$ per bed**. This solution consisting of hardware and software developed in an open license using of the shelf, widely available components, using CrowdSourcing (development, prototyping, testing, and distributed production) and driven by CrowdFunding. How you can help? 
**Please, consider supporting us financially to build first prototypes through PayPal, donating your ideas to GitHub or sharing this project on social media!**

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=barteklecki%40o2.pl&item_name=support+OpenICU+project&currency_code=EUR&source=url)

> _**Disclamer: the devices and systems shown are intended for educational and training purposes only. This is NOT certified medical equipment. The possibility of using equipment in a crisis situation can be regulated by law - please refer to local legislation. Please proceed with caution!**_

## TECH-TALK

**Goal:** to design and build a low-cost "ICU in a suitcase" from standard, commercial of the shelf and widely available components, inexpensive and enabling production using relatively simple tools, but also automated production. 

### V1 Kit include:
- 3-point / 5-point ECG (Open Hardware module) with gates for other sensors
- finger pulse oximeter (SpO2) sensor
- body temperature sensor 
- pendrive with Linux software that changes any PC in the so-called patient monitor / cardiac monitor (no installation needed) and doubles as a doc-friendly interface to set ventilator parameters
- emergency low-cost ventilator (ONLY for in “right to try” situation) incl. with the function of smart control and "breathing with the patient" (A/C mode, PSV - no need for muscle paralysis, CPAP), safety alarms for staff, working using “dirty” and common compressed air sources to create clean breaths. 

## Open-ICU - building blocks:
![Alt text](https://github.com/barteklecki/OpenICU/blob/master/OpenICU_blok_design.png?raw=true)

## Emergency ventilator principle:
![Alt text](https://github.com/barteklecki/OpenICU/blob/master/Ventillo_mechanics_gif.gif?raw=true)

## 3D concept model 
![Alt text](https://github.com/barteklecki/OpenICU/blob/master/Ventillo_3d_model_gif.gif?raw=true)


# Q&A

### Who are you?
We are a group of friends, and in the professional life we are engineers (automation, electronics, IT). We hope that some part of our work and ideas can be used to make a difference. That is why all materials are available as Open Source.

### There are already several ventilator designs on the internet - what is so unusual about this project?
That's right, there are currently many great ventilator designs created by enthusiasts around the world. However, in our opinion, there is a need and space for a tool to fit specifically to combat COVID-19. Treatment is complicated, it requires constant heart and blood oxidation diagnostics. Additionally construction of the ventilator should allow precise changes and control of parameters. We would like to understand what is particularly required in the treatment of this disease and provide the right tools for doctors in one cheap and as possibly reliable Open Hardware package.

### The respiratory device is powered by compressed air - why?
Although the electric motor as a actuator is a solution used in many professional respirators, creating a very reliable electro-mechanical system from widely available components is a big challenge. On the other hand, pneumatic systems such as actuators, solenoid valves and connection fittings are extremely popular, available from many sources and standardized. Pneumatic cylinders, e.g. in factories, perform millions of cycles without fail, which is crucial for this device. Since the compressed air is not used directly to vent a patient, standard "dirty" piston or screw air compressors can be used, which can be found in almost every factory. In the scenario where we have a field hospital consisting of hundreds of beds, a set of standard air compressors can work reliably for months or years, and in the event of a power outage, the pressure in tanks serve as a backup for the entire system, because compressed air consumption is low.

### Why is the electrical system 12V?
The idea behind it is that you can use any car battery (AGM, all maintenance-free) for emergency power supply, and any laptop power supply as the AC adapter. This significantly reduces costs and is widely available.

### Is any oxygen source or generator part of this project?
No, we assume that oxygen will be supplied from the existing installation. In addition, other projects are underway, which aim to e.g. design open-source oxygen generators

_author: Bartek Ł., V.0.23/4-2020
contact: barteklecki (a) o2.pl_
