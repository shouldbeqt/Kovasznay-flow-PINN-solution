**This repositories show how PINN can find solution of Kovasnay flow**

I consider two models: first predict solution in range x = [0,1], y = [0,1], second: x = [-0.5,1], y = [-0.5,1.5]
I compare solution with analytics soltuion, which you can find in another repositories

**All models, solution, metrics can find in folder**

Example first model:
PINN:

![image](https://github.com/user-attachments/assets/fa0e6f3c-289b-40ae-aca0-c9ef1f03f9d2)

Analytics:

![image](https://github.com/user-attachments/assets/b8269b4c-4172-415a-9d0c-5709d7fdd5ed)

Or metric compare:
1) Model with periodic condition
2) Model without periodic condition
3) Model which has learining on range x = [-0.5,1], y = [-0.5,1.5] with pressure in inflow condition
4) Model which has learining on range x = [-0.5,1], y = [-0.5,1.5] with increase lerning on initial condition
5) Default model (model without pressure in inflow condition)
6) Model with more collaction point

![image](https://github.com/user-attachments/assets/f8e8e122-7fc6-4f28-9ab9-7fa718756bba)

Example second model:

PINN:

![image](https://github.com/user-attachments/assets/93759543-1ca2-4626-8ce4-1cb83b466106)

Analytics:

![image](https://github.com/user-attachments/assets/601e7045-e41d-4583-998f-e3475d19b262)

Or metric compare:
1) Model which has learining on range x = [-0.5,1], y = [-0.5,1.5] with pressure in inflow condition
2) Model which has learining on range x = [-0.5,1], y = [-0.5,1.5] with increase lerning on initial condition
3) Default model (model without pressure in inflow condition)
4) Model with more collaction point

![image](https://github.com/user-attachments/assets/cab24057-379f-4c51-a683-6fa9a36a363b)
