---
title: Resistive Sensors
bibFile: sensors
category: Sensors
permalink: /:categories/:title/

---

A resistive sensor changes its resistance due to changes in physical quantity such as mechanical, thermal, magnetic, optical, and chemical. Now, let us look into different types of resistive sensors.

### Potentiometers (Variable Resistors)
##### Great Videos
1.  [Potentiometers - Basic Introduction](https://www.youtube.com/watch?v=XuBx9eQYscU)
2.  [Types of Potentiometers and Practical Aspects](https://www.youtube.com/watch?v=5d_TTQ2OJtM)
3.  [Digital Potentiometer](https://www.youtube.com/watch?v=uezoQ5fkixY&t=241s)
	1.  [[pull up resistors]]
	2.  [[debouncing capacitors]]

##### Potential Issues from {% cite Pallas-Areny2001Sensors %} 
1.  Resistance fluctuation due to temperature.
2.  A potentiometer is a [[zero-order system]].
3.  The resistance is not perfectly uniform, limiting the potentiometer's linearity. The agreement between the actual and the theoretical transfer characteristic (here, a straight line) is termed [[conformity]](here linearity).
4.  For high values of resistance, parasitic capacitance may be important .

### Force Sensitive Resistor

FSR is similar to a potentiometer, but here, the wiper is the point of application of force and amount of force.

##### Great Videos

1.  [Basic Introduction](https://www.youtube.com/watch?v=1p8AE_QA8qQ)
2.  [Simple application](https://www.youtube.com/watch?v=u2EHDyrV_F0)
3.  [Advanced with op-amps](https://www.youtube.com/watch?v=f00t2liHl3Q)


### Magnetoresistors

The resistivity of ferromagnetic materials depends on the angle between the direction of electric current and the orientation of magnetization. This is known as anisotropic magnetoresistive (AMR) effect {% cite Jogschies2015Recent %}. In most conductors, the magnetoresistive effect is of a second-order compared to the Hall effect. The giant magnetoresistive effect was observed in multilayered structures made up from alternating layers of magnetic and nonmagnetic materials {% cite Pallas-Areny2001Sensors %}.

Anisotropic magneto resistors (AMRs) and giant magneto resistors (GMRs) offer several advantages compared to other magnetic sensors. First, their mathematical model is a zero-order system. This differs from inductive sensors, whose response depends on the time derivative of magnetic flux density. Compared with Hall effect sensors, which also have a zero-order model and measure without contact, magneto resistors show increased sensitivity, temperature range, high-frequency passband, and insensitivity to mechanical stress. On the other hand, they saturate at lower field strengths and are more expensive {% cite Pallas-Areny2001Sensors %}.
