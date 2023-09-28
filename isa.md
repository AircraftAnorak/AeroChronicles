---
title: ISA
layout: default
nav_order: 2
---

{% include math.html %}

<h1>International Standard Atmosphere (ISA)</h1>


The atmosphere is dependant on many different factors such as:
- Altitude
- Location
- Season
- Time
- Solar Activity



<u><b>Synoptic Weather: </b></u> 
{: .d-inline-block }

<b>LIVE</b>
{: .label .label-red .d-inline-block }

<iframe width="650" height="450" src="https://embed.windy.com/embed2.html?lat=54.085&lon=-3.560&detailLat=51.233&detailLon=-0.601&width=650&height=450&zoom=5&level=surface&overlay=wind&product=ecmwf&menu=&message=true&marker=&calendar=now&pressure=true&type=map&location=coordinates&detail=&metricWind=kt&metricTemp=%C2%B0C&radarRange=-1" frameborder="0"></iframe>

To combat the complexity, a standard for the atmosphere was created to replicate how properties change with altitude
- Temperature, T(h)
- Pressure, P(h)
- Density, ρ(h)

Most ISA models will be largely simillar for altitudes in the lower atmosphere (30km) - On this page, we will refer to the ARDC atmospheric model ( from the Air Force Research Laboratory, Anderson)

{: .info }
ρ<sub>0</sub> is the air density at sea level in the ISA (15 °C and 1013.25 hectopascals, corresponding to a density of 1.225 kg/m<sup>3</sup>)

## <u>Altitude Definitions</u>

<span style="color:HotPink">**Geometric Altitude**</span> (h<sub>G</sub>) - The distance from mean sea level


<span style="color:HotPink">**Absolute Altitude**</span> (h<sub>a</sub>) - The distance from the centre of the planet

<center>h<sub>a</sub> = h<sub>g</sub> + <i>r</i> </center>

Where _r_ is the radius of the planet

For spaceflight, h<sub>a</sub> is important as the local gravitational acceleration, _g_ varies with it

$$ g(h) = g_{0}{\left({\frac{r}{h_{a}}}\right)}^2 $$

Where <i>g<sub>0</sub></i> is the acceleration of gravity at sea level (<i>h<sub>g</sub></i> = 0)

<span style="color:HotPink">**Geopotential Altitude**</span> (h) - A ficticious altitude where <i>g(h) = constant = g<sub>0</sub></i>

{: .note }
Geopotential altitudes are used to construct ISA tables however <i>h<sub>G</sub></i> is more practical

## Troposphere

For altitudes where h < 11 km

$$ T = T_{a} - λh $$

$$ {\frac{ρ}{ρ_{1}}} = {\left({\frac{T}{T_{1}}}\right)}^{\frac{g}{λR}-1} $$

$$ {\frac{P}{P_{1}}} = {\left({\frac{T}{T_{1}}}\right)}^{\frac{g}{λR}} $$

## Lower Stratosphere

For altitudes where 11 km < h < 20 km

$$ T = constant $$

$$ {\frac{ρ}{ρ_{1}}} = e^{-{\frac{g}{λR}{(h-h_{1})}}} $$

$$ {\frac{P}{P_{1}}} = e^{-{\frac{g}{λR}{(h-h_{1})}}} $$

