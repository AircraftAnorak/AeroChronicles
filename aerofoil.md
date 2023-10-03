---
title: Aerofoils
layout: default
parent: Aerodynamics
nav_order: 1
---

{% include math.html %}

<h1>Aerofoils</h1>

An aerofoil is a streamlined body which is designed to generate significantly more lift than drag in air

<span style="color:HotPink">**Chord Line**</span>: Straight line connecting the Leading Edge to the Trailing Edge

<span style="color:HotPink">**Mean Camber**</span>: A series of points halfway between the upper and lower surface

<span style="color:HotPink">**Camber**</span>: Distance between the Mean Camber and Chord lines

<span style="color:HotPink">**Max Thickness**</span>: The max distance between the upper and lower surfaces

<span style="color:HotPink">**Angle of Incidence**</span>: The angle between the chord line and the relative airflow direction

![Clarke Y](assets/images/clarky-il.svg){:height="100%" width="100%"}

# Defining Aerofoil Profiles

An Aerofoil is usually defined by two variables: the camber and the thickness

<span style="color:Orange">**NACA**</span> aerofoils are standardised profiles which can be defined by a series of digits

{: .info }
NACA is the National Advisory Committee for Aeronautics

## Four Digit Series

Is the most simple NACA series, allowing for an aerofoil to be defined by only four digits

Each digit defines a different variable of the cross section

1. First Digit describes th maximum camber as a percentage of the chord
2. Second Digit defines the distance of the maximum camber from the leading edge in tenths of the chord
3. Third and Fourth Digits define the maximum thickness of the aerofoil as a percent of the chord

A very common aerofoil is the <span style="color:Orange">**NACA 2412**</span>, which has a **maximum camber of 2% located 40%** (0.4 chords) from the leading edge with a **maximum thickness of 12%** of the chord

![NACA 2412](assets/images/naca2412-il.svg){:height="100%" width="100%"}

{: .info }
A symetrical aerofoil in the NACA Four Digit series will always be in the form of NACA 00XX

More complicated NACA aerofoils can be defined by more digits in other series