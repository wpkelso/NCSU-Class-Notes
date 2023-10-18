---
aliases: [FET]
tags: [electronics, circuits, microelectronics]
---

# Field Effect Transistor

## MOSFET

![[Pasted image 20231015162527.png]]

The MOSFET is one of the most common types of FETs, often acting as an electronically controlled switch. The MOS in MOSFET stands for  Metal Oxide [[Semiconductor]], usually using Silicon Oxide as the semiconductor material.

## Operation Regions

### Cutoff

Occurs when $V_{GS} < V_{T}$. In this region, no inversion layer is formed, and drain and source are separated by a depleted channel. This results in $I_{DS} \approx 0$

### Linear (Triode/Ohmic)

### Saturation

## Biasing 

### Substrate Conditions

#### Accumulation

![[Pasted image 20231018110448.png]]

#### Depletion

![[Pasted image 20231018110554.png]]

#### Inversion (Channel formation)

![[Pasted image 20231018110628.png]]

### Bias Analysis

1. Assume an operation region (usually saturation)
2. Use circuit analysis to find $V_{GS}$ 
3. Use $V_{GS}$ to calculate $I_{D}$, and $I_{D}$ to calculate $V_{DS}$
4. Check validity of operation region assumptions

### Finding the Q-Point

The [[Quiescent Point]] for a FET is found in a similar way to BJTs, but the Q-Point for a FET is found as ($I_{D}, V_{DS}, V_{GS}$).

### Four-Resistor Bias Network

A four-resistor bias network is used for biasing [[Transistor|transistors]] in discrete circuits, as it stabilizes the bias point with respect to device parameter and temperature variations using negative feedback. Generally, it is used to bias transistors in saturation region.