# cplusplus2python
Auto convert c++ code to python 
使用pyplusplus, pygccxml, gccxml,boost.python
gccxml已经被castxml取代，但是目前pygccxml还不完善，这里使用老版本的pygccxml,pyplusplus
进行c++封装，为了能够支持c++11语法，做了一些特殊处理。从而使得gccxml可以处理c++11编写的头文件。
