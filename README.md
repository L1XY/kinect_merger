```bash
cd <catkin_ws>/src
rosdep install -i --from-paths src
catkin_make
```

## launch
## 启动多个kinect2并发布tf坐标变换(基于base_link)

```bash
roslaunch kinect_merger kinect_merger.launch
```

