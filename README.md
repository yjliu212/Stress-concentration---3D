# Stress-concentration---3D
Stress concentration around wellbore in 3D view

In the notebook Stress contration and wellbore breakout, we showed how does the effective hoop stress (EHS) change as a function of the angle around a wellbore, for different mud weight conditions. We know that higher stress concentration arise when there is a significant difference between the max horizontal stress (Shmax) and the min horizontal stress (Shmin). To better view the Effective Hoop Stress (EHS) around a wellbore for different stress conditions, we could also display the EHS as an contour map or image map in 3D. This notebook will do that.

The figure below displays the EHS as a mapview around a wellbore as a contour plot (on the left) and a image plot (on the right). We can see that higher EHS occurs at the Shmin direction (up and down), and lower EHS occurs at the Shmax direction (left and right). In this case, Shmax = 13000 psi, Shmin = 7000 psi, mud weight = pore pressure = 4000 psi, so a balanced condition. And we can see that the difference between max EHS and min EHS is 24000 psi, which equals to 4 * (Shmx - Shmin) = 4 * 6000 = 24000 psi. This means as a result of stress concentration, the difference between max and min stress around wellbore has been magnified by four times.

![image](https://github.com/user-attachments/assets/7c89ca07-d31a-43a7-80c0-a23bb438a2f8)

If the wellbore wall's rock strength C0 is around 20000 psi, the figure below shows the area that the wellbore will breakout.

![image](https://github.com/user-attachments/assets/49c601c1-2d65-482b-a24f-7d3dd608df5d)

We can see a few more senarios of stress condition and mud weight condition as below.

1. Shmax = 13000, Shmin = 10000, so less horizontal stress difference than previous case. Mud weight still balance pore pressure. We can see that max EHS becomes smaller and min EHS becomes larger than before, however, the difference between the max EHS and min EHS = 22000 - 6000 = 12000, which is still 4 * (Shmax - Shmin) = 4 * 3000 = 12000 psi.

![image](https://github.com/user-attachments/assets/ea0ab386-1124-47ea-a4d6-201ba2cc9f63)
And if the wellbore wall's rock strength C0 is around 2000 psi, then the breakout width will be smaller than previous case, as shown below.
![image](https://github.com/user-attachments/assets/a55ef46a-af45-40a2-aece-a7646c49f366)

Play with the following conditions yourself.

2. Shmax = 13000, Shmin = 13000
3. Shmax = 13000, Shmin = 6000
3. Shmax = 13000, Shmin = 7000, pore pressure = 4000, mud weight = 5000 (over-balanced)

See what happends when mud weight is higher than pore pressure. When will tensile failure starts to occur.
