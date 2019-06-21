# HealthCarrier

This project was made for the course: CAL. This program calculates the best paths for ambulances to get patients on health centers and deliver them to their specific hospital.
A number of patients are generated (with a specific disease) and are put into health centers across one of the maps used (wich are represented using graphs).
According to the capacity of the ambulances there will always be needed at least one or more ambulances and the best path for each one will be calculated, taking into account that specific diseases need specific treatments (only some hospitals can deliver that treatment) and there are some pations that are on a urgent state. This means that they have a time associated with them (that represents how much time they have untill they get their treatment). 
Therefore, the program tries to maximize the number of patients that can survive and then minimize the time and number of ambulances used to deliver those patients.
To build this program we used dynamic and greedy algorithms typically used to solve TSP (Travelling Salesman Problem) like problems, such as A*, Nearest Neighbor Heuristic, 2-opt, etc.
