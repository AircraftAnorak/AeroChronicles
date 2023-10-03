---
title: Drag
layout: default
parent: Fluid Mechanics
nav_order: 2
---

{% include math.html %}

<h1>Drag</h1>

Drag is the force which opposes thrust - caused by the resistance of moving in a fluid

The two main types of drag are:
- Pressure Drag
- Friction Drag

{: .info }
Total Drag = Pressure Drag + Friction Drag

# Skin Friction Drag

This type of Drag is caused by the viscous friction between the surface and the fluid

It is associated with the boundary layer and the amount of drag produced is a product of how much surface area is exposed to the flow

# Pressure Drag

![Friction and Pressure Drag curves](assets/images/1280px-1915ca_abger_fluegel_(cropped_and_mirrored).jpg){:height="100%" width="100%"}

This type of drag is caused by the eddying motions and formations of wake an aerofoil or surface may create

Usually this is greatest for aerofoils at high AoA (Angle of Attack) where seperation between the skin and fluid occurs

{: .note }
For bluff bodies: Pressure Force = Pressure x Area

![Friction and Pressure Drag curves](assets/images/Drag_curves_for_aircraft_in_flight.svg){:height="150%" width="150%"}

{: .note }
Drag can be calculated for any object travelling through a fluid by using a coefficient for Drag, C<sub>D</sub>

$$ C_{D} = \frac{Drag Force}{\frac{1}{2}ρu_{m}^2 \times Area} $$

$$ Drag Force = C_{D} \times \frac{1}{2}ρu_{m}^2 \times Area $$