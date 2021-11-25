# SRRA 2021

https://www.even3.com.br/srra/

* Ignition Fortress
* ROS Rolling
* SimSlides
* Dolly
* ros_ign from source

---

Commmands

`ros2 node list`

`ros2 topic list`

`ros2 topic echo /dolly/cmd_vel`

`ros2 topic info /dolly/laser_scan`

`ros2 topic info /dolly/laser_scan -v`

`ros2 topic info /dolly/cmd_vel -v`

`ros2 bag record /dolly/cmd_vel`


---

PDF to PNG params

`convert -density 500 -quality 100 -resize 1920x1080 slide.pdf slide.png`
