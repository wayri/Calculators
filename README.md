# Calculators
This repository contains several calculators for design of electrical converters etc. For now it is an excel sheet...

## Capacitor Bank Calculator
This is an excel sheet, where you just type some requirements in. The sheet does the rest.
+ It can calculate capacitor bank values, equivalent ESR, total energy stored, voltage rating for a given configuration
+ It can also calculate the configuration for you, like if your voltage requirement is 10V and Capacitance "C" or Energy Requirement is "E", provided the values for an individual capacitor unit. It can provide you the nearest voltage rating of the capacitor bank in volts and the number of series connected capacitors (Ns) to form a string, and number of strings in parallel (Np) to form a series-parallel capacitor bank.
+ It can also search time values corresponding to voltage, current, energy (REVERSE Search).
+ It also generates a basic plot for both charging and discharging conditions, voltage and current both. [DO NOT EDIT ANY CELL OTHER THAN BLUE_UNDERLINED CELLS.]
+ There is also a value search for capacitors connected to regulators in standalone configuration, but that is not accurate and fails to work correctly | use at your own risk.
+ Oh! and it also calculates ESR power loss for multiple current values
Have fun, designing capacitor banks
