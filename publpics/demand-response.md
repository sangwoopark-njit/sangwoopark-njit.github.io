---
layout: page
title: ""
description: Grid Flexibility
---


### <a name="demand-response"></a>Grid Flexibility: Learning Heterogeneous Elasticity and Dynamic Pricing of Rewards for Demand Response

<table class="wide">
<tr>
  <td class="figure">	
    <img src="demand-response-figure.png" alt="" title="demand-response-figure"/>
  </td>
</tr>
</table>

The increasing frequency of extreme weather events are presenting profound difficulties
in safely operating electric power systems around the world. For instance, in 2022,
the California Independent System Operator (ISO) noted that record-breaking temperatures
during summer heat waves are leading to historic high demands for power, putting
greater strain on the electrical grid and significantly increasing the likelihood of rotating
outages unless consumers can reduce their energy use even more than they have so far. 
Various researches have also noted that the heightened uncertainty in electricity
generation coming from renewable energy resources can destabilize the system unless
more demand-side management are set into place.

Demand response (DR), defined as “the changes of end-consumers’ electricity consumption
in peak hours from their normal patterns,” has gained popularity as a means
(and a resource) to solve the reliability and efficiency issues of the power grid. As
more residential real estate (RRE) and commercial real estate (CRE) owners
explore innovative ways to cut cost and conserve energy, DR offers a powerful
alternative for achieving these goals, and at the same time, contributing to
the overall grid stability. In addition to benefiting the overall stability of the power
grid, DR can financially benefit load aggregators (LA), entities that purchase electricity
at real-time wholesale prices and supply them at a flat rate to end-customers. During
time periods when the wholesale price of electricity exceeds the flat rate that LAs receive
from the customers, it is actually financially beneficial for them to encourage the
customers to reduce consumption by offering monetized rewards.

Many ISOs and LAs in the U.S. in fact already have several DR programs in their
operating areas. However, most of them are reporting lower than expected participation,
due to reasons such as non-flexibility of demand and information asymmetries.
According to the U.S. Department of Energy, residential electricity consumption constitutes
over 38% of the total U.S. electricity consumption, forming a large pool of
flexibility that we can exploit. One of the reasons why demand response has been
largely unsuccessful in the residential sector is because there is a lack of understanding
of consumer-specific behavior patterns. In this research, we establish a framework
for understanding the heterogeneous elasticity of electricity consumption in the face of
monetary rewards, and utilize that information for the dynamic pricing of such rewards.
We aim to predict the elasticity of electricity demand specific to each consumer and appliance
(e.g., HVAC, lighting, laundry, EV charging) given external factors such as day
of week, time of day, temperature/humidity, lifestyle, building characteristics. Then,
those elasticity information will be used to design a reward pricing mechanism that will
dynamically change the amount of reward based on the current state of the system. The
project will leverage optimization/machine-learning tools and financial models through
the collaboration among experts in Management Science and Engineering.


<style>
  .figure {
    flex: 1;
    margin-bottom: 20px; /* Adjust the margin as needed */
	height: 235px; /* Set a fixed height for the figures */
    overflow: hidden; /* Hide any overflowing content */
  }
   
  .figure img {
    width: 100%;
    height: 100%;
	object-fit: cover; /* Crop the image to fit the fixed height */
  }
</style>