# Pandemic-Flu-Simulation
Simulation of a virus spread in a city with a population of half a million
The virus spread starts in a city with the entry of 10 infectious people. 
The infectious person spread the disease to others whom they come in contact during their period of illness which is 7 days. The number of contact each resident make is determined randomly using normal distribution with mean 5 and standard deviation 1.5.
It is assumed that 15% of the population already has a natural immunity to fight the virus and hence, even if they come in contact with the infected person, they do not get sick. Rest of the citizens fall sick if they come in contact with the infectious person. 
The infected person gets recovered in 7 days and after that, he/she also develops an immunity to fight the virus. Moratality rate of this virus spread is zero. Luckily, no one dies!
City authority try to stop this pandemic from spreading. They try different startegy and we have simulated the outcome under each of the below mentioned strategies.
1. No mask and No Lockdown
2. Only mask enforcement but no lockdown
3. Mask enforcement and lockdown
4. Mask enforcement with one dose of vaccine
5. Mask enforcement, lockdown and two doses of vaccine

The effect of these various startegies are listed below:
1. Using masks reduces contagiousness of the disease from an infected person by 50%
2. Enforcing lockdown reduces number of friends an infected person is likely to meet by 70%
3. 1st dose of vaccine reduces disease contagiousness to 20%
4. 2nd dose of vaccine reduces disease contagiousness to 50%

Simulation conducted for all 5 scenarios and for 100 days and a very intuitive result is obtained that startegy-5 of enforcing mask usage, lockdown and two doses of vaccines is the most effective startegy 
in which pandemic reached to a peak of 152114 cases on 40th day and pandemic stops on 49th day.  

Grpah is plotted in the report for comparison of disease spread under all 5 strategies. Implementation of strategies are also discussed in detail in the report. 

Python code for the simulation is also attached.  

Excel file has day-wise disease spread data under all 5 strategies. 
