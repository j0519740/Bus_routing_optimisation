# Bus Routing Optimisation in Punggol
An efficient network of public transport is helpful to improve the quality of public transport services and
save time for travelers. One of the important aspects of urban transportation is the continuous
optimization of the bus network.
In this project, we aim to find the solutions that minimize the total number of buses required to serve all the bus stops in Singapore's Punggol area. The problem is modelled around the well-known multiple travelling salesman problem (mTSP) which is a Mixed Integer Problem (MIP) and utilizes Gurobi Optimizer and other libraries to solve this problem.
![image](https://github.com/j0519740/Bus_routing_optimisation/assets/99134168/4c9e08c2-e081-43e7-942f-818a80e619eb)

## Example of an optimised route for 3 buses:
![image](https://github.com/j0519740/Bus_routing_optimisation/assets/99134168/9b07ab7f-47d4-444c-a292-5ea8df471bc1)


## Cost and maximum duration of each bus for the optimised routes for different buses scenarios:

![image](https://github.com/j0519740/Bus_routing_optimisation/assets/99134168/d0287277-f17e-432e-b0e3-c2e1d2bebc15)

![image](https://github.com/j0519740/Bus_routing_optimisation/assets/99134168/acb0340e-85d2-4c96-a7a5-4ca02ca0cb8b)

## Conclusion

Based on the solutions depicted in the above section for the various ‘m’ buses scenarios, the transport
company will now have the necessary information to choose the best option based on their budget and
meeting their customer satisfaction (maximum duration per bus route) for the feeder bus service in the Punggol Neighborhood. There is a trade-off between the maximum duration of the bus routes and the costs associated with each scenario. If the transport company wants to have a much faster turnaround
time for each bus route, they will need to invest in more buses to achieve a faster turnaround of the bus
routes.
In addition, there is also a limitation in this model as the demand of the customers who will be using this
service is not considered. To better model to consider the demand at each bus-stop, we can better model the bus capacity needed for each route. This will result in better estimation of the size of buses needed
for each route and better projection of the costs involved. The demand estimation may also result in
reducing the number of bus stops used for the feeder bus-service, further optimizing the costs.
We have also obtained feasible solutions within relative computing time (optimal solutions found within
1 hour) for this project. There is a trade-off between deducing the best optimal solution and the computing time needed to deduce the solution. Therefore, there is scope to explore other heuristic
algorithms like ant-colony algorithms and genetic algorithms if they can obtain better optimal solutions
at a faster computing time.


