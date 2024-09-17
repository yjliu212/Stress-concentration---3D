# Stress-concentration---3D

In the notebook "Stress Concentration and Wellbore Breakout," we demonstrated how the effective hoop stress (EHS) varies as a function of the angle around a wellbore under different mud weight conditions. Higher stress concentrations arise when there is a significant difference between the maximum horizontal stress (Shmax) and the minimum horizontal stress (Shmin). To better visualize the EHS around a wellbore under varying stress conditions, we can display the EHS as a contour map or an image map in 3D. This notebook provides such visualization.

The figure below shows the EHS as a map view around a wellbore using a contour plot (on the left) and an image plot (on the right). Higher EHS values occur in the Shmin direction (up and down), while lower EHS values are seen in the Shmax direction (left and right). In this example, Shmax = 13,000 psi, Shmin = 7,000 psi, and the mud weight equals the pore pressure at 4,000 psi, representing a balanced condition. The difference between the maximum and minimum EHS is 24,000 psi, which matches the theoretical value of 4 * (Shmx - Shmin) = 4 * 6,000 = 24,000 psi. This indicates that due to stress concentration, the difference between the maximum and minimum stress around the wellbore is magnified by a factor of four.

![image](https://github.com/user-attachments/assets/948b51b3-ed52-4e2d-af5e-9a1982c010f5)

If the rock strength C0 of the wellbore wall is approximately 20,000 psi, the figure below highlights the regions where wellbore breakout is likely to occur.

![image](https://github.com/user-attachments/assets/5d10eb67-01b6-4112-a8c4-d224f0c3baf2)

Let's explore a few more scenarios involving different stress and mud weight conditions:

1. Shmax = 13,000, Shmin = 10,000, resulting in a smaller horizontal stress difference compared to the previous case. The mud weight still balances the pore pressure. In this scenario, we observe that the maximum EHS decreases, while the minimum EHS increases relative to the earlier case. However, the difference between the maximum and minimum EHS is 22,000 - 6,000 = 12,000, which is still 4 * (Shmax - Shmin) = 4 * 3,000 = 12,000 psi.

![image](https://github.com/user-attachments/assets/4fc842e9-45d5-488f-ae31-0760e0941ca8)

If the wellbore wall's rock strength, C0, is around 2,000 psi, the breakout width will be narrower compared to the previous case, as shown in the figure below.

![image](https://github.com/user-attachments/assets/da9d0a3f-7b5e-4915-b3df-7214483121f1)

Try experimenting with the following conditions yourself.

2. Shmax = 13,000, Shmin = 6,000, pore pressure = 4,000, mud weight = 4,000 (balanced)
3. Shmax = 13,000, Shmin = 7,000, pore pressure = 4,000, mud weight = 5,000 (over-balanced)

Observe what happens when the mud weight is higher than the pore pressure. Identify the conditions under which tensile failure starts to occur.

Note that increasing the mud weight will reduce the breakout width but can introduce tensile fractures. Additionally, as the difference between Shmax and Shmin becomes larger, it can further increase breakout width and cause tensile fractures.



Results:

2. Shmax = 13,000, Shmin = 6,000, pore pressure = 4,000, mud weight = 4,000 (balanced)

In this stress condition, the increased difference between Shmax and Shmin results in a wider breakout and the introduction of tensile fractures.

![image](https://github.com/user-attachments/assets/cfe658fe-d676-455e-a109-f724c4725ebd)

![image](https://github.com/user-attachments/assets/74798016-fb00-421f-9b9d-9ff056dfca61)

3. Shmax = 13,000, Shmin = 7,000, pore pressure = 4,000, mud weight = 5,000 (over-balanced)

In this case, the mud weight exceeds the pore pressure, leading to the development of tensile fractures.

![image](https://github.com/user-attachments/assets/3f12a518-a490-4434-9fa7-47faddea399d)

![image](https://github.com/user-attachments/assets/c53b603e-495e-4bb3-b654-41a00d19b45f)


