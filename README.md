# Build-My-World
Opens a gazebo world with a short welcome message.

### Clone the repository in /home/workspace/
```sh
$ cd /home/workspace/
$ git clone https://github.com/arjunvenugopal07/Build-My-World myrobot
```
### Create a build directory and compile code
```sh
$ cd myrobot
$ mkdir build
$ cd build/
$ cmake ../
$ make
```
### Export path to gazebo plugin path
```sh
$ export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/workspace/myrobot/build
```
### Run the gazebo world file
```sh
$ cd /home/workspace/myrobot/world/
$ gazebo myoffice
```
