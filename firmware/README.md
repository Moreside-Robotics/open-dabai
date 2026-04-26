# 硬件抽象层 / 固件层 (Layer 1)

嵌入式实时控制系统，通过 micro-ROS 桥接至 ROS2 中间件层。

## 模块

- `motor_driver/` — 电机驱动 (STM32 / ESP32)
- `sensor_board/` — 力/光/热传感器板固件 (I2C / SPI)
- `micro_ros_agent/` — micro-ROS Agent 桥接配置
