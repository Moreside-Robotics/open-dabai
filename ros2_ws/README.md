# ROS2 中间件层 (Layer 2)

基于 ROS2 (Humble/Iron) 的机器人中间件，负责感知、导航、运动控制与传感器融合。

## Packages

| Package | 功能 |
|---------|------|
| `dabai_bringup` | 启动配置与 launch 文件 |
| `dabai_perception` | 视觉感知 (OpenCV / YOLO) |
| `dabai_navigation` | SLAM + Nav2 导航 |
| `dabai_control` | 运动控制 |
| `dabai_sensors` | 传感器驱动与融合 (robot_localization) |
| `dabai_interfaces` | 自定义 msg / srv / action 定义 |
