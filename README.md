# CartPole
LQR Control for https://github.com/linZHank/invpend_experiment

<br>
Specify desired position of cart here <br>

`self.desired_state = np.matrix([[1],[0],[0],[0]])`

To execute `rosrun invpend_control lqr_controller.py`

## Plots
Setpoint: (pos, pos_dot, theta, theta_dot)

Setpoint: (-1,0,0,0)
![alt txt](plots/plot1.png "Plot 1")

Setpoint: (1,0,0,0)
![alt txt](plots/plot2.png "Plot 2")

## Video
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/8Yjk9IjhK5w/0.jpg)](https://youtu.be/8Yjk9IjhK5w)
