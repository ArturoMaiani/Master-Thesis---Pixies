## - Master thesis about deep reinforcement learning

The benchmark contains some 10 by 10 meters maps, containing different distributions of litter.

Two learning curves are presented:

Map A: full square 4 by 4 meters wide at the center of the map.

<img width="502" alt="Schermata 2022-06-03 alle 16 53 44" src="https://user-images.githubusercontent.com/100837287/173919114-9bcbc3b3-2252-4807-80c8-fb1e018fedff.png">

![PPO_primo_tentativo_10^6_steps (2)](https://user-images.githubusercontent.com/100837287/173916654-da888148-d4dc-468c-ba77-88161e3f5d89.png)

Map B: two separate regions.
<img width="497" alt="Schermata 2022-06-03 alle 16 54 16" src="https://user-images.githubusercontent.com/100837287/173916946-a2e1988f-11bb-4f1f-a4b6-d8baad1b9250.png">

![PPO_primo_tentativo_10^6_steps_mappa3](https://user-images.githubusercontent.com/100837287/173916675-f5ad441b-1252-4eb1-8e8b-ef9d38507c8f.png)

The file named "Stable baselines PPO cortile pixies" contains the map corrsponding to the area nearby Pixies base:
![aurelia_residence_crop-2](https://user-images.githubusercontent.com/100837287/173916076-2c4f9489-44a3-44a7-86d0-5ac1990008ec.png)
<img width="550" alt="Schermata 2022-06-15 alle 22 15 56" src="https://user-images.githubusercontent.com/100837287/173919193-f411638c-04a8-447d-8795-14aa86fe4360.png">
For this one i have used:
mosse_max=1000
delta_t=0.7
flag_robot_su_griglia=-1
v_mid=0.4
omega_max=0.6
<img width="467" alt="Schermata 2022-06-15 alle 23 27 24" src="https://user-images.githubusercontent.com/100837287/173933006-3942b656-8416-4610-a608-044fba1e2672.png">
