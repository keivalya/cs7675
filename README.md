# CS7675: Master's Research


## Stretch3 - Hello Robot Inc.

> Prerequisites: Hello Robot’s Stretch3, and GPU Computer

Quick Start:
SSH onto the robot (using its IP address), and command

```sh
stretch_robot_home.py
cd ~/stretch_ai && ./scripts/run_stretch_ai_ros2_bridge_server.sh
```

On the GPU,

```sh
mamba deactivate
cd ~/stretch_ai
./scripts/run_stretch_ai_gpu_client.sh 
./scripts/set_robot_ip.sh 192.168.1.243
python -m stretch.app.ai_pickup
```

Stretch will attempt to pick up an object from the floor and place it inside a nearby receptacle on the floor. You will use words to describe the object and the receptacle that you'd like Stretch to use. Eg,

```
Enter the target object: red and white can
Enter the target receptacle: blue chair 
```
