# susan_description

## 1. Installation
```sh
cd <your_ws>/src
git clone https://github.com/0nhc/susan_description
cd ..
rosdep install --from-path src --ignore-src -r -y
catkin_make
```

## 2. Model Visualization
```sh
cd <your_ws>
source devel/setup.bash
roslaunch susan_description display.launch
```
