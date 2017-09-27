Name: Dylan Peters
NetID: dlp22
Hours Spent: 6.5
Consulted With: TAs (Paul)
Resources Used: TAs (Paul) 
Impressions: This was a difficult assignment to start out with, but it was satisfying when it finally worked.

Question 1: What is the final position of the planets after 1,000,000
seconds with a timestep of 25,000?
for 3body.txt:
3.8521264572234327E8 2.0743645559891003E8 
2.8262893940514652E10 3.697453627727204E10 
-2.8262893595748608E10 -3.697453690031148E10

Question 2: For what values of timeStep, does the simulation no longer behave correctly? 
Large values. The larger the timeStep, the less accurate the simulation.
For example, in the 8-star rotation, a timeStep of 85000 causes the stars to eventually stop rotating and fly off on tangents
For my computer, a small timeStep of 2500 causes the simulation to experience significant lag.