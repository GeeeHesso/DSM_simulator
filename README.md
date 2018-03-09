# DSM_simulator

Demand side management simulator to flatten the aggregated load of an ensamble of consumers.
Central controller performs "peak shaving/valley filling" on the overall load curve by commanding
thermostatically controllable loads and batteries. The non flexible loads/productions considered are
domestic household appliances (timeseries generated using BehavSim) and PV production.
For the electic power consumption profiles generated, it is possibile to run a Power Flow simulation 
for radial network topologies and monitor voltage levels.


Compile the c++ executables:

- navigate into to /src
- compile using make -f Makefile

To run the code: "python DSM_simulator.py"

Runs on: Python 2.7 with modules numpy = 1.11.0, scipy = 0.17.0, matplotlib = 1.5.1, pandas = 0.17.0, Tkinter, PIL


**** CAREFUL **** The code overwrites the results directory "/Results_CITY" if it already exists!

