## $5 Tech Unlocked 2021!
[Buy and download this product for only $5 on PacktPub.com](https://www.packtpub.com/)
-----
*The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

# ROS Robotics Projects
This is the code repository for [ROS Robotics Projects](https://www.packtpub.com/hardware-and-creative/ros-robotics-projects?utm_source=github&utm_medium=repository&utm_campaign=9781783554713), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.

## About the Book
Robot Operating System is one of the most widely used software frameworks for robotic research and for companies to model, simulate, and prototype robots. Applying your knowledge of ROS to actual robotics is much more difficult than people realize, but this title will give you what you need to create your own robotics in no time!

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

The code will look like the following:
```
[default]
ros::init(argc, argv,"face_tracker_controller");
ros::NodeHandle node_obj;
ros::Subscriber number_subscriber = node_obj.subscribe("/face_centroid",10,face_callback);
dynamixel_control = node_obj.advertise<std_msgs::Float64>("/pan_controller/command",10);
```
Chapter 1 does not have any codes.



## Related Products
* [Effective Robotics Programming with ROS - Third Edition](https://www.packtpub.com/hardware-and-creative/effective-robotics-programming-ros-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786463654)

* [ROS Robotics By Example](https://www.packtpub.com/hardware-and-creative/ros-robotics-example?utm_source=github&utm_medium=repository&utm_campaign=9781782175193)

* [Mastering ROS for Robotics Programming](https://www.packtpub.com/hardware-and-creative/mastering-ros-robotics-programming?utm_source=github&utm_medium=repository&utm_campaign=9781783551798)


### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
