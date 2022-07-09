# Fundametal of robotics

<p align="center">
  <a href="">
    <img src="https://github.com/MattiasTrettel/Progetto-Robotica/blob/main/img/marchio_unitrento_colore_it_250.jpg">
  </a>
  <h2 align="center">Fundamental of Robotics</h2>

  <p align="center">
  Exam project for Fundamental of robotics 
  <br>University of Trento - Prof. PALOPOLI LUIGI, Prof. SEBE NICULAE
  </p>
</p>
<br>
A number of objects (e.g., mega-blocks) are stored without any specific order on a stand (initial stand) located within the workspace of a robotic manipulator. The manipulator is an anthropomorphic arm, with a spherical wrist and a three-fingered gripper as end-effector.
The objects can belong to different classes but have a known geometry. The objective of the project is to use the manipulator to pick the objects in sequence and to position them on a different stand according to a specified order (final stand). A calibrated 3D sensor is used to locate the different objects and to detect their mutual position in the initial stand.


```
  git clone https://github.com/MattiasTrettel/Progetto-Robotica
  cd Progetto-Robotica
 
  source /opt/ros/noetic/setup.bash
  catkin build
  source devel/setup.bash
  #or source devel/setup.zsh
  
  #in order to launch the world after Gazebo's start unpause the simulation
  roslaunch ultimate_robot robot.launch
  
  #first assignment
  ./spawner_singolo.py
  
  #kinematics
  rosrun robot_movement point_2_node
  #vision
  rosrun ultimate_vision ultimate_position.py
```


## Kinematics 🦾
[@AndreaMangrella](https://github.com/kativenOG)

[@MattiasTrettel](https://github.com/MattiasTrettel)



## Vision 👓
[@LorenzoCanciani](https://github.com/cancianilorenzo)

[@CarloBottaro](https://github.com/bottarocarlo)

In order to conplete the assignment we made a dataset on roboflow to recognize the block 


