# ABM_non OOP

This agent-based model is represented using a 2D numeric array with confined board space of 50 X 50, with the randomization of agent placement (~50% placement). A more neighborhood is utilized while the application for von Neumann neighborhood it's certainly possible. 
For this model the general rules for advancement are: 

1.	At the end of each step (time = 1 day) each cell with the current state alive has a 50% chance of survival to the next day. 
2.	Cells that survive will then have the instance to attempt reproduction depending on available spacing within their surrounding neighborhood. 
3.	For this model, newly formed cells of the reproduction method are prohibited from attempting to reproduce themselves as they have not passed the appropriate survival method. 

A visual graph with line of best fit is returned at the conclusion of running, as well as descriptive statistics. 

 Ari Barnett (Roldan) St. Petersburg College 2021
