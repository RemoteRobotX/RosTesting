# ROS Sandbox

Repo struct(from root):

```
.
├── deploy
│   ├── build.sh
│   └── run.sh
├── README.md
└── ros2_ws
    └── src
        └── pkg_name (example)
            ├── DEFAULT ROS files, such as setup.py

```

About deploy dir:

* `build.sh` - script to build all packages (default: `colcon build`)
* `run.sh`   - script to run nodes (you can call ros2 run, or launch)


