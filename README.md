# pushkarraunak_print_squares
Assignment 1
Problem statement:

Create a catkin package <github-username>_print_squares which contains three nodes:

    <username>_numbers - This node will publish integers (starting from 1) to a ROS topic named topic_numbers at the rate of 1 Hz.
    <username>_squares - This node will subscribe to topic_numbers and print the squares of the published numbers to another topic, topic_squares.
    <username>_print - This node will subscribe to both topic_numbers and topic_squares and output them using ROS_INFO. The output will indicate the name of the topic that the output has come from.

IMPORTANT Catkin does not allow two nodes to have the same executable name (CMP0002), so you MUST always ensure that the name of your node is unique.
Instructions: The development process

    The programs must use the C++ API of ROS.
    If the code is copied from the ROS website, You must not copy any documentation present in it.
    The code MUST be documented. You must write this documentation yourself. This documentation may be written in any form that you think is appropriate for your code. (Line-wise, Block-wise etc.)
