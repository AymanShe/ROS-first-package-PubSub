# ROS-first-package-PubSub

## Platform
Ubuntu 18.04  
ROS Melodic Morenia

## Instrcutions

1. In your ROS workspace *src* folder, clone this repo into a local directory called *ayman_package*  
`$ git clone https://github.com/AymanShe/ROS-first-package-PubSub.git ayman_package`

1. Build the package using `catkin_make` or `catkin build ayman_package`

1. Run ROS core node  
    ```
     $ roscore
    ```

1. In two different terminals, run the nodes *publisher.py* and *subscriber*  
    ```
     $ source devel/setup.bash  
     $ rosrun ayman_package publisher.py
    ```
    ``` 
     $ source devel/setup.bash  
     $ rosrun ayman_package subscriber
    ```
    
    
    
## Resources

https://wiki.ros.org/melodic  
https://wiki.ros.org/ROS/Tutorials  
https://youtu.be/PowY8dV36DY
