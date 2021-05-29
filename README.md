# hoverboard-driver
ROS hardware driver for UART-controlled hoverboard. Can be used with [diff_drive_controller](http://wiki.ros.org/diff_drive_controller). Hoverboard is using [firmware by p-h-a-i-l and @btsimonh](https://github.com/bipropellant/bipropellant-hoverboard-firmware)

This driver is built for [Robaka](https://github.com/alex-makarov/robaka-ros), a prototyping robotic platform based on hoverboard, Jetson Nano and a bunch of sensors. There is a [Slack community](https://join.slack.com/t/robaka/shared_invite/zt-q52yfvnl-IP0h~JDOmgh3VmJ7Hh69Jw) for Robaka.


A. Firmware for hoverboard-driver:
https://github.com/quangvu16/hoverboard_driver/blob/master/Hoverboard_firmware_UART2.bin

How to make firmware: https://youtu.be/Q01NtnQYkZM

B. Port Config: hoverboard_driver/include/hoverboard_driver/


C. ROS package:

Step 1: git clone git@github.com:quangvu16/hoverboard_driver.git

Step 2: cd hoverboard-driver

Step 3: git submodule update --init --recursive
