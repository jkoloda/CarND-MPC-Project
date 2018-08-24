# CarND-MPC-Project

Self-Driving Car Engineer Nanodegree Program

---


## Model Predictive Controller (MPC)

The controller adjusts the speed and steering of a car so it can drive around the track. This adjustement is done by minimizing a cost function that takes into account the following aspects:

* Mminimize the cross-track error and keep the car speed and heading as close as possible to the reference values.
* Minimize the use of the actuators (i.e. acceleration and steering).
* Impose smooth use of the actuators by minimizing their first (temporal) derivative.

See `writeup-report` for more details.


## Dependencies

* cmake >= 3.5
* All other dependencies can be installed by running:
	* install_ubuntu.sh
	* install_ubuntu-MPC.sh
	* install_ipopt.sh
    

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./mpc`

**NOTE:** The MPC system is designed to be run against the [Udacity simulator](https://github.com/udacity/self-driving-car-sim/releases). Run MPC with the simulator already running.


## Examples

Two video examples are included in `videos` folder. The folder contains a `README` file with more information.
