# Stress-concentration---3D
Stress concentration around wellbore in 3D view

In the notebook Stress contration and wellbore breakout, we showed how does the effective hoop stress (EHS) change as a function of the angle around a wellbore, for different mud weight conditions. We know that higher stress concentration arise when there is a significant difference between the max horizontal stress (Shmax) and the min horizontal stress (Shmin). To better view the Effective Hoop Stress (EHS) around a wellbore for different stress conditions, we could also display the EHS as an contour map or image map in 3D. This notebook will do that.

The figure below displays the EHS as a mapview around a wellbore as a contour plot (on the left) and a image plot (on the right). We can see that higher EHS occurs at the Shmin direction (up and down), and lower EHS occurs at the Shmax direction (left and right). In this case, Shmax = 13000 psi, Shmin = 7000 psi, mud weight = pore pressure = 4000 psi, so a balanced condition. And we can see that the max EHS = 4 * (Shmx - Shmin) = 4 * 6000 = 24000 psi. 
![image](https://github.com/user-attachments/assets/97f90e2d-10d2-4bff-9f48-296fc5762415)

If the wellbore wall's rock strength C0 is around 20000 psi, the figure below shows the area that the wellbore will breakout.
![image](https://github.com/user-attachments/assets/1fc9f29b-3ee1-43a1-add3-86db6f530bed)

We can see a few more senarios of stress condition and mud weight condition as below.

1. Shmax = 13000, Shmin = 10000, so less horizontal stress difference than previous case. Mud weight still balance pore pressure. We can see that max EHS becomes smaller than previous case
![image](https://github.com/user-attachments/assets/539dc41a-6095-46e0-941c-32552d7fec6b)
![image](https://github.com/user-attachments/assets/2d53bbcf-ef69-4b62-998d-23b1d6b2fdf1)

