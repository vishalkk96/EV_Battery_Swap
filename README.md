# EV_Battery_Swap
Note: For the python code, reach out to me at https://www.linkedin.com/in/vishalkannan/  
Recommending the optimal daily service capacity for EV battery swap facilities across various cities in the US

## Introduction:

One significant disadvantage for EV ownership from the consumer perspective is the amount of time taken for recharging the EV batteries.
The second disadvantage is that considering the work patterns of most people, most of the EVs owned will be charged at night or at the end of a work-day.
This requires conventional electricity sources to be used for charging the batteries as no solar energy is available at night.
EV battery swap facilities can eliminate both disadvantages.
It drastically reduces the time taken for a battery to go from zero charge to full.
It allows the batteries to be remotely charged at the battery swap facilities when renewable energy is available in abundance.

## Solution Approach:

The solution is to setup battery swap facilities in select cities depending on the annual budget allocated and serve the maximum number of customers possible.

## Parameters:

The optimization needs to be done with respect to the following factors:
* Setup cost, Labor cost, Charging cost
* Lower demand estimate, Upper demand estimate
* Annual Budget

## Cost estimates

Referred to online sources for estimation

![](Cost_Estimate.png)

## Demand estimates

Simulation based on the number of EVs owned in each city

![](Lower_Demand.png)

![](Upper_Demand.png)

## Mathematical Model

Variable Declaration

![](Variables_Decl.png)

![](Math_Formulation.png)

![](Constraints_Desc.png)
