# Gazebo Environment Modelling
Using SDF to model a university campus environment in Gazebo simulator.

## Aim
Aiming to model the following section of campus:

<p align="center">
    <img src="https://raw.github.com/cgia10/Gazebo-Environment-Modelling/master/Images/campus_top.JPG" width=378 height=324 hspace=40>
    <img src="https://raw.github.com/cgia10/Gazebo-Environment-Modelling/master/Images/campus.JPG" width=378 height=345>
</p>

## Results
Progress as at 22/4/20:

<table>
  <tr>
    <td align="center"><img src="Images/campus_top.JPG" width=420 height=360></td>
    <td align="center"><img src="Images/model_top.png" width=440 height=260></td>
  </tr>
  <tr>
    <td align="center"><img src="Images/campus_front.JPG" width=455 height=201></td>
    <td align="center"><img src="Images/model_front.png" width=536 height=260></td>
  </tr>
  <tr>
    <td align="center"><img src="Images/campus_closeup.JPG" width=440 height=204></td>
    <td align="center"><img src="Images/model_closeup.png" width=536 height=260></td>
  </tr>
 </table>

## Testing:
1. Terminal: git clone https://github.com/cgia10/Gazebo-Environment-Modelling.git
2. Add the /Models/ directory in this repo to the GAZEBO_MODEL_PATH environment variable
    1. Terminal: source "your gazebo install path"/setup.sh (usually usr/share/gazebo/setup.sh)
    2. Terminal: sudo nano "your gazebo install path"/setup.sh (usually usr/share/gazebo/setup.sh)
    3. Add the path to this repo's /Models/ directory. Enter the path in the line with the GAZEBO_MODEL_PATH variable, after the colon. Finish the path with another colon.
3. cd into the root of this repo
4. Terminal: gazebo campus.world
