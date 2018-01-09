# P-RANS
Parabolic RANS model for wind turbine wake simulations. 
This application is being made available for users in wind energy that would like to simulate the wake field in a wind turbine column with an axisymmetric flow. The details and applications of the code are available for citation in Iungo et. al. Wind Energy, 2017, and Santhanagopalan et. al. Renewable Energy 2017. In its current form, Windows users can download and install the standalone application which additionaly requires Matlab runtime to be installed if not available already.

Summary: 
The solver facilitates fast simulations of wakes and its effect on the performance of wind turbines in a column aligned with the wind direction. 
The Reynolds-averaged Navier-Stokes (RANS) equations in axisymmetric form are solved with parabolic approximation. The turbulence closure is achieved through a mixing length and one-equation model. The mixing length was calibrated and modeled using large eddy simulations. The aerodynamics of the 5-MW NREL research turbine (Jonkman et. al. NREL 2009) is considered in the blade elements momentum theory with a modified actuator disc method for modeling the turbine. 

This solver facilitates the user to simulate up to 10 turbines. Control is provided to change the atmospheric turbulence level and the turbines' tip speed ratios and diameters can be varied by the user. Furthermore, the spacing between turbines can also be modified.
The simulation estimates the power production of the turbines and saves all the parameters in an excel file. The streamwise velocity profile is displayed in the application for visualization as well as saved in the excel sheet. The corresponding grid in streamwise direction (X grid) and radial direction (R grid) are available in the excel file. 
