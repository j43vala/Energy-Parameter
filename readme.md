# Energy Meter System (ENMS)

The Energy Meter System (ENMS) is a comprehensive solution for monitoring and managing energy consumption in various applications. This README provides an overview of the key functionalities and features of the ENMS project.

# PARAMETERS

# Current(I) -

- Defination - the flow of electric charge in a conductor

- unit - Ampere (A)

- Equation - I = Voltage  / Resistance

# Voltage(V) -

- Defination - the electric potential difference between two points in a circuit

- Unit - Volt (V)

- Equation - V = I (current) * R (resistance)

# Resistance(R) -

- Defination - Opposition to the flow of electric current.

Unit - Ohm

Equation - r = Voltage  / I (current)

# Frequency(f) -

- Defination - the number of cycles per second of an alternative current.

- unit - Hz

- relation with period - f = 1 / T

----------

# power

p = VI

product of voltage and current
-------

# Apparent Power(S)

defination - the total power flowing

AP = voltage * current

unit - VA (volt-Amps)

--------

# Reactive power(Q)

Q = VI sin (θ)  OR  Q = S sin(θ)

 where, θ = phase angle between voltage and current in an AC circuit.

 it is the non-working power in an AC circuit that is responsible for creating the magnetic field.

# Impedance (Z)

z = V / I

- the overall opposition that a circuit presents to the flow of alternating current.

# R phase

- represent as a red color
- carried AC current
- r phase is measured in watts(W)

----------------------

# Y phase

- represent as a yellow color
- carried AC current
- measered in watts(W)
- electrically displaced by 120 deg from the other phases.
- create balancing system that provides a more constant and efficient power supply.

---------------------------

# B phase

- represent as a blue color
- carried AC current
- measered in watts(W)

# Watts

**defination** - A measurment of the rate of energy transfer over a unit of time.

**unit** -  
watts is a unit of power.
1 joule of work / second **OR** 1/746 horsepower.

**equation** -

Watts = Amps x Volts

eg. 10 Amps x 120 Volts = 1200 Watts.

**Relation** -

- ***Power and Energy***:
Power is the rate at which energy is used or produced.

The relationship between power (P), energy (E), and time (t) is given by the equation:

E=P×t, where E is energy in joules, P is power in watts, and t is time in seconds.

- ***Voltage, Current, and Resistance*** (in electrical context):

In electrical systems, power (P) can be calculated using the formula:

P=I×V, where I is the current in amperes and V is the voltage in volts,

according to Ohm's Law (V=I×R, where R is resistance).

- its related to energy, voltage, current and resistance in various contexts.

-------------------------------

# PF ave. (Instantaneous) - power factor

**defination** - power factor is an expression of energy efficiency.

- expressed as a percentage.

- lower percentage, the less efficient power usage.

- its a ration of working power

**unit** -

 PF measured in **kilowatts(KW)**

Instantaneous POWER unit - watt

**Equation** -

PF = KW / KVA

Instantaneous Power Factor: = cos(θ)

![Alt text](image.png)

**Relation** -

### active power -

known as real power, is the product of the voltage, current and powerfctor in an AC circuit.

- equation -

p = VI cos(θ)

where,
p = active power , v = voltage, I = current , cos(θ) is the power factor

### Reactive power -

- arises due to phase difference between voltage and current in an AC circuit.

- equation -

Q = VI sin (θ)

where,
Q = reactive power , v = voltage, I = current , sin(θ) = sine of the phase angle.

- lagging and leading

-----![Alt text](image-20.png)

# POWER FACTOR  for R, Y and B phase

- each phase has its power factor. however, these PFs are generally assumed to be the same for balanced systems. where the loads and impedances in each phase are equal.
- the power factor for each phase is given by the cosine of the phase angle between the voltage and current waveforms in that phase.

1) PF for R phase -

        PFr = cos(θr)

2) PF for Y phase -

        PFy = cos(θy)

3) PF for B phase -

        PFb = cos(θb)

where,

- R,PF Y, and PF B are the power factors for the R, Y, and B phases, respectively.
- θ R, θ Y and θ B are the phase angles between voltage and current waveforms for the R, Y, and B phases, respectively.

# VA total

VA - it is a vector sum of real power (measured in watts)
**unit** - Volt-ampere (VA)
**Symbol** - VA

### Equation -

S (Apparent power)= V (voltage) * I (current)

**Note** - without power factor

S = V *I* COS(θ)

**Note** - with power factor

## relation with other terms -

**Real power (P)** -

- equation -

p = |S| (magnitude od apparent power) *cos(θ) (phase angle between voltage and current)

**Reactive power (Q)** -

- equation -

Q = |S|  (magnitude of apparent power) * sin(θ)  (θ is the phase angle between voltage and current.)
---------

# Wh (Watt-hour)

- represents the amount of energy consumed or produced by a device with a power rating of one watt over a period of one hour.

![Alt text](image-12.png)

**Equation**-

Energy (Wh) = Power (W) * Time (h)

**Defination** -

- a measure of electrical energy equivalent to a power consumption of one Watt for one hour.

**SI unit** -

3600 joules

**Relation** -

**Watt** - is a unit of power.

- one watt is equals to one joule per second.

- P (power) = I (current) * V (voltage)

**Joule** -

- unit of energy.
- one watt-hour is equal to 3600 joules.

equation,

Energy (in watt-hours) = power (in watts) * Time (in hours)

**Volt (V)** -

is the electric potential difference between two poins in an electrical circuit.

- the relationship between energy, power and voltage
 equation,

        Energy (in watt-hours) = Power (in Watts) * Time (in hours) = voltage (in volts) * Current (in amp) * Time (in hours).

**Ampere(A)** -

- unit of electric current.
- reprents the flow of electric charge in a cuircuit.

relation between energy, power and current and time.

Energy (in watt-hours) = power(in watts) *Time(in hours) = Voltage (in volts)* Current (in amperes) * Time (in hours).

# VAh (Volt-Ampere-Hour)

## equation

VA = Volts * Amperes

![Alt text](image-13.png)

## Ah (Ampere-Hour)

Ah = watt-hours / voltage

## Relation -

![Alt text](image-2.png)

# Load Hours -

- To derive load hours -

need information about the POWER consumed by the load over a certain period.

- Load hours are often expressed in kilowatt-hours(KWh) or megawatt-hours(MWh)

![Alt text][def]

# CO2

- carbon intensity factor = CO2 emmission.

CO2 Emission = Energy Consumption (KWh) * Carbon Intensity Factor (gCO2 / KWh)

- to find carbon intensity factor -

![Alt text](image-4.png)

![Alt text](image-5.png)

# Var (Volt-Ampere Reactive)

Var is a unit of measurment of reactive power.

## mathematical relation -

![Alt text](image-6.png)

## Derive

- equation

![Alt text](image-7.png)

![Alt text](image-8.png)

- to find a single phase of VA.
![Alt text](image-9.png)

---
![Alt text](image-10.png)

## Var Total

- sum of the reactive powers of individual phases (var R , var Y , var B).

- Reactive power is a vector quantity and when dealing with a three-phase system, is determined by the phasor sum of the reactive powers of the individual phases.

![Alt text](image-11.png)

# KVARh inductive

- ### kilovolt-Ampere Reactive-Hour is a unit of measurment for reactive power consumption or production in an electrical system

- ### reactive power is required to establish and maintain the magnetic fields in inductive devices such as motors and transformers

![Alt text](image-15.png)

## relations

1) Reactive power -

![Alt text](image-18.png)

sin(θ) - [the sine of the power factor angle.]

2) Apparent power -

![Alt text](image-16.png)

3) power factor -

![Alt text](image-17.png)

4) Real power -

![Alt text](image-19.png)

# KVARH inductive

## defination -

Measures the cumulative reactive power in an electrical system due to inductive loads like motors and transformers.

- it cause a lagging power factor. where the current lags behind the voltage.

![Alt text](image-21.png)

# KVARH capacitive

## defination -

Measures the cumulative reactive power in an electrical system due to capacitive loads.

- capacitive loads cause a leading power factor, where the current leads the voltage.

![Alt text](image-22.png)

