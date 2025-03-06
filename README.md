# livox_ws
A repo. which used to simply manage ROS SDK about livox sensors.

## SDK

```bash
git clone git@github.com:zhan994/livox_ws.git

cd sdk/Livox-SDK
mkdir build && cd build
cmake ..
make -j
sudo make install

cd ../../Livox-SDK2
mkdir build && cd build
cmake ..
make -j
sudo make install

cd ../../../src/livox_ros_driver2
./build.sh ROS1
```

