# service_example
This is a package for examples for ROS services.

Very important!

Compile the package them uncomment the bottom lines for the codes!

This package is for example of ros nodes publishers and subscribers in python and C++.

Instructions to run the C++ nodes, python nodes don't need compilation.

```
$ cd 
$ cd catkin_ws
$ catkin_make --only-pkg-with-deps service_example
```
Once the package is build, you can run the nodes written in C++.

```
$ rosrun subpub_example Publisher
$ rosrun subpub_example Subscriber
```
