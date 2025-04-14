# ws_liv
A repo. which used to simply manage ROS SDK about LIV devices.

## SDK

```bash
git clone git@github.com:zhan994/liv_ws.git

cd sdk/Livox-SDK2
mkdir build && cd build
cmake ..
make -j
sudo make install

cd ../../src/livox_ros_driver2
./build.sh ROS1
```

