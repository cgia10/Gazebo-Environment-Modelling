# Gazebo Environment Modelling
Using SDF to model a university campus environment in Gazebo simulator.

## Aim
Aiming to model the following section of campus:

<table>
  <tr>
    <td align="center">Top</td>
    <td align="center">Front</td>
    <td align="center">Closeup</td>
  </tr>
  <tr>
    <td><img src="https://raw.github.com/cgia10/Gazebo-Environment-Modelling/master/Images/campus_top.JPG" width=210 height=180></td>
    <td><img src="Images/campus_front.JPG" width=455 height=201></td>
    <td><img src="Images/campus_closeup.JPG" width=440 height=204></td>
  </tr>
 </table>

## Results
Progress as at 22/4/20:
![](https://raw.github.com/cgia10/Gazebo-Environment-Modelling/master/Images/model_top.png)
![](https://raw.github.com/cgia10/Gazebo-Environment-Modelling/master/Images/model_front.png)
![](https://raw.github.com/cgia10/Gazebo-Environment-Modelling/master/Images/model_closeup.png)

## Testing:
1. Terminal: git clone https://github.com/cgia10/Gazebo-Environment-Modelling.git
2. Add the /Models/ directory in this repo to the GAZEBO_MODEL_PATH environment variable
    1. Terminal: source "your gazebo install path"/share/gazebo/setup.sh
    2. Terminal: sudo nano "your gazebo install path"/share/gazebo/setup.sh
    3. Add the path to this repo's /Models/ directory. Enter the path in the line with the GAZEBO_MODEL_PATH variable, after the colon. Finish the path with another colon.
3. cd into the root of this repo
4. Terminal: gazebo campus_menzies_lawbry.world
