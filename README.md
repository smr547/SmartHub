# SmartHub
Open source power measurement device

## Objective
The objective of this project is to develop a SmartHub device that will monitor a battery (or battery bank) measuring

- [ ] Battery voltage
- [ ] Current (charge and discharge)
- [ ] Battery temperatures

These results will be reported to a central monitoring system which will display current operating parameters,
time graphs and alert/alarm conditions.

## Functional requirements

* 12/24V operation
* standalone (powered by the battery bank itself)
* instantaneous voltage, current and power
* cumulative energy status (State of Charge)
* historical records/graphs
* warnings and alerts

## Notes

* An [excellent video](https://youtu.be/jiSZUbQVQRk?si=NomNqURFb63rSNtr) from Texas Intruments outlining the design of a signal conditioning circut for use with current shunts
* Article describing the use of [an external ADC and amplifier](https://learnarduinonow.com/2015/05/11/reading-current-shunt-with-arduino.html)
* An [inline sensing device](https://riedon.com/media/pdf/SSA.pdf)
