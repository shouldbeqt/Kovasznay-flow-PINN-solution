**This repositories show how PINN can find solution of Kovasnay flow**

I consider two models: first predict solution in range x = [0,1], y = [0,1], second: x = [-0.5,1], y = [-0.5,1.5]
I compare solution with analytics soltuion, which you can find in another repositories

Example first model:
PINN:
https://github.com/shouldbeqt/Kovasznay-flow-PINN-solution/blob/main/Model%20with%20periodic%20condition/Vx_0_1_model.png
Analytics:
https://github.com/shouldbeqt/Kovasznay-flow-PINN-solution/blob/main/Analytics%200_1/0_1_Vx.png
Or metric compare:
1) Model with periodic condition
2) Model without periodic condition
3) Model which has learining on range x = [-0.5,1], y = [-0.5,1.5] with pressure in inflow condition
4) Model which has learining on range x = [-0.5,1], y = [-0.5,1.5] with increase lerning on initial condition
5) Default model (model without pressure in inflow condition)
6) Model with more collaction point
Table_0_1_eng.png
