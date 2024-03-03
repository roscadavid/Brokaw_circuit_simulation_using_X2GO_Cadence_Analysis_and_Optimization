Brokaw circuit simulation using X2GO Cadence:Analysis and Optimization

The project I undertook was part of the optional course organized by Infineon Cluj, titled "Integrated Systems and Circuits for Automotive Applications". I chose to participate in this course voluntarily, aiming to learn new things and enrich my knowledge. Throughout this course, I learned about the X2GO Cadence hardware environment, becoming familiar with the program and its operation. As a culmination of the course, I completed a project titled "Brokaw Circuit Simulation using X2GO Cadence: Analysis and Optimization". In this project, we discussed voltage reference, dimensioning of the Brokaw circuit, startup circuit, simulations, and circuit optimization in the Cadence program. The voltage reference is a simple circuit that provides a stable voltage over time and against variations in the manufacturing process, supply voltage, and temperature (PVT), as well as environmental conditions: mechanical stress, pressure, humidity, radiation, etc. The Bandgap voltage reference is based on the sum of two voltages: the base-emitter voltage of the bipolar transistor, with complementary temperature variation (CTAT) with a typical value of 0.65V at room temperature, and the difference between two base-emitter voltages, DVbe, proportional to the absolute temperature (PTAT) with a typical value of less than 100mV at the same temperature. The compensation condition is that the two voltages have equal and opposite slopes with temperature. Therefore, the second PTAT voltage is amplified by a factor kp, with values between 5 and 10. The startup circuit operates when the reference is powered. The peculiarity of these circuits is that they are active only during the startup phase, afterwards they no longer function. Simulations in Cadence were performed with an ideal amplifier, with process resistances, but also with a real amplifier in which a Miller-type configuration was used inside. In the end, we observed how the circuit functions with the two amplifiers, we saw the Bandgap characteristic, as well as phase and amplification parameters, etc.
