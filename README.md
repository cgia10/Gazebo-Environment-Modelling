# Gazebo Environment Modelling
Using SDF to model a university campus environment in Gazebo simulator.

## Campus Section
Currently the following portion of campus has been modelled:
![Image of Campus Section](campus.jpg)

## Testing:
**1.** Clone this repo: https://github.com/cgia10/Gazebo-Environment-Modelling.git
**2.** Add the /Models/ directory in this repo to your GAZEBO_MODEL_PATH environment variable
    1. In terminal: source "your gazebo install path"/share/gazebo/setup.sh
    2. In terminal: sudo nano "your gazebo install path"/share/gazebo/setup.sh
    3. Add the path to this repo's /Models/ directory. Enter the path in the line with the GAZEBO_MODEL_PATH variable, after the colon. Finish the path with a colon. Save.
**3.** cd into the root of this repo
**4.** In terminal: gazebo campus_menzies_lawbry.world
