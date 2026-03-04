# Characteristics and Parameters of Op-Amp (IC 741)

## AIM
To study and measure the characteristics and parameters of IC 741 operational amplifier such as input bias current, input offset current, input offset voltage and slew rate.

---

## COMPONENTS REQUIRED
- IC 741 Operational Amplifier
- Resistors
- Dual power supply
- Function generator
- CRO (Cathode Ray Oscilloscope)
- Breadboard / Trainer kit
- Connecting wires

---

## Introduction
An operational amplifier is a high gain direct coupled amplifier consisting of one or more differential amplifier stages followed by a level translator and an output stage. The output stage is generally a push-pull complementary amplifier.

Operational amplifiers are available as single integrated circuit packages and are used for amplifying DC and AC signals. They were originally designed to perform mathematical operations such as addition, subtraction, multiplication and integration.

With external feedback components, op-amps are used in many applications such as signal amplification, filters, oscillators, comparators and voltage regulators.

---

## Ideal Characteristics of an Op-Amp
An ideal operational amplifier has the following characteristics:

- Infinite voltage gain  
- Infinite input resistance  
- Zero output resistance  
- Infinite bandwidth  
- Infinite common mode rejection ratio (CMRR)  
- Infinite slew rate  

---

## Input Offset Voltage (Vio)

In an ideal op-amp, the output should be zero when both inputs are at the same voltage. However, in a practical op-amp like the IC 741, a small differential voltage is required between the inputs to make the output zero. This voltage is called **input offset voltage**.

Formula:

Vout = (1 + Rf/R1) × Vio  

Therefore,

Vio = Vout / (1 + Rf/R1)

---

## Input Offset Current (Iio)

In practical op-amps, small currents flow into the input terminals. These are called **input bias currents**. The difference between the two input bias currents is called **input offset current**.

Formula:

Vo = Iio × Rf  

Therefore,

Iio = Vo / Rf

---

## Inverting Bias Current (IB1)

The current flowing into the inverting terminal is called **inverting bias current**.

Formula:

Vo = IB1 × Rf  

Therefore,

IB1 = Vo / Rf

---

## Non-Inverting Bias Current (IB2)

The current flowing into the non-inverting terminal is called **non-inverting bias current**.

Formula:

IB2 = Vo / R1

---

## Slew Rate

Slew rate is defined as the maximum rate of change of output voltage with respect to time.

Slew Rate = dVout / dt

It is measured in **Volts per microsecond (V/µs)**.

The slew rate can be calculated using:

SR = 2π fmax Vm

where  
fmax = frequency at which distortion begins  
Vm = peak output voltage

---

## Important Points
- IC 741 requires dual power supply.
- Input offset voltage is typically in millivolts.
- Input bias current is usually in nanoamperes.
- Slew rate of IC 741 is approximately **0.5 V/µs**.
- Gain bandwidth product is about **1 MHz**.

---

## Conclusion
The characteristics and parameters of IC 741 operational amplifier were studied successfully. The input bias current, input offset current, input offset voltage and slew rate were observed and the practical values were close to the standard specifications of the IC 741 operational amplifier.
