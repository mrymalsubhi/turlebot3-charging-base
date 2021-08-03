# turtlebot3-charging-base
## task 3.

---

- this will work for ubuntu 18.04 and ROS melodic.

---

- in the terminal run this code: 

``` 
export TURTLEBOT3_MODEL=burger

roslaunch turtlebot3_gazebo turtlebot3_world.launch
```

---

![Screenshot (19)](https://user-images.githubusercontent.com/85639068/127950110-ca4c5593-8043-49fb-98c8-4b1b97ada00c.jpeg)


---

- open a new terminal from file - new tap, and run navigation node: 

```
export TURTLEBOT3_MODEL=burger

roslaunch turtlebot3_navigation turtlebot3_navigation.launch 
```

---

![Screenshot (20)](https://user-images.githubusercontent.com/85639068/127950135-2ea07cb5-130c-4d03-b4e0-cac08364c20f.jpeg)

---

- to control, open a new terminal and run this code: 

```
export TURTLEBOT3_MODEL=burger
roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
```

---

![Screenshot (21)](https://user-images.githubusercontent.com/85639068/127950157-bc6dff57-d5bf-451c-b03f-79869d4d5418.jpeg)


---
