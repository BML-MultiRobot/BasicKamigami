Basic Kamagami

This directory is for the simplest robot and controller to make it easy to get
started V-Rep simulation.

Steps
1) Load Pusuit.ttt into V-Rep
2) use right pointing triangle in V-rep to start simulation running
3) run python Pursuit.python

robot should start ambling across plane

4) Stop simulation on v-rep should terminate python, but python might give an error instead.

(Note: Modified March 25, 2021 to use external main.lua, rather than internal lua script to specify robot motion. Now script can be version controlled.)
Bug fixed with cyclePhase in for loop with indixes now 1..3 and 4..6.

