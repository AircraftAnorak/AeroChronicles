---
title: Aircraft Speed
layout: default
parent: Aerodynamics
nav_order: 4
---

{% include math.html %}

<h1>Aircraft Speed</h1>


The atmosphere is dependant on many different factors such as:

Some terminology:

<span style="color:HotPink">**Static Presssure**</span> (P<sub>s</sub>): The pressure observed as if moving along with the flow

<span style="color:HotPink">**Dynamic Presssure**</span> (P<sub>d</sub>): The pressure due to the velocity of the flow

<span style="color:HotPink">**Total Presssure**</span> (P<sub>0</sub>): The pressure at a given point in the flow that would exist if the flow were slowed down isentopically to zero velocity

$$ P_{t} = P_{s} + P_{d} $$

{: .note }
Subscripts for Total Pressure may be used interchangeably between 0 and t

$$ P_{d} = q = \frac{1}{2}ρV^2 $$

# Pitot Static Tube

Is an instrument which measues the total and static pressures to calculate the dynamic pressure and subsequently the velocity (provided densisty, ρ, is known)

$$ P_{t} = P_{s} + P_{d} = constant $$

$$ P_{d} = P_{t} - P_{s} = \frac{1}{2}ρV^2 $$

From Bernoulli's Equation (incompressable flows):

$$ V = \sqrt{\frac{2(P_{t}-P_{s})}{ρ}} $$

<span style="color:HotPink">**TAS**</span> (True Airspeed): The actual speed through the air mass

$$ V_{TAS} = \sqrt{\frac{2(P_{t}-P_{s})}{ρ_{h}}} $$

Where ρ<sub>h</sub> is the density at flying altitude

{: .note }
For each airspeed calculation, ρ needs to be known otherwise velocity cannot be calculated

<span style="color:HotPink">**EAS**</span> (Equivilent Airspeed): The Calibrated Airspeed (CAS) corrected for the compressibility fof air

$$ V_{EAS} = \sqrt{\frac{2(P_{t}-P_{s})}{ρ_{0}}} $$

Where ρ<sub>0</sub> is the density at mean sea-level

V<sub>EAS</sub> (P<sub>t</sub> - P<sub>s</sub>) is usually measured by a differential pressure transducer

At low speeds and altitudes, IAS and CAS are close to EAS

# TAS and EAS

$$ V_{TAS} = \left({\frac{ρ_{0}}{ρ}}\right)^\frac{1}{2} V_{EAS} $$

{: .note }
V<sub>EAS</sub> is the velocity at which you would have to fly to match the dynamic pressure at standard sea level

# Compressability and Mach

The Mach number is a multiplier of your airspeed relative to the speed of sound

The expression for TAS and EAS are obtained only for incompressable flow, where ρ is constant and only valid for M < 0.3

Where M is the Mach number:

$$ M = \frac{V}{a} $$

And <i>a</i> is the Speed of Sound (for a perfect gas):

$$ a = \sqrt{γRT} $$

And γ is a ratio of the specific heat at a constant pressure and volume:

$$ γ = \frac{C_{p}}{C_{v}} $$