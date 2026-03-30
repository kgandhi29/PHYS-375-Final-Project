# PHYS-375-Final-Project
# 03-15 Ben uploaded a starting point for the standard MS sample code
# 03-24 fixed small mistake in markdown file correct one is "375markdown"
# 03-24 Ben uploaded a 2nd version of the standard MS sample code which includes:
  - No changes to the code in V1
  - Adds a luminosity_surface_error function which calculates the shooting method error when compared to the target boundary condition
  - Adds a solve_star_for_Tc function which finds the right rho_c for a chosen T_c using the luminostiy_surface_error function
  - Adds a build_main_sequence function which constructs a collection of stellar models by solving for a star for each Tc in Tc_Values
  - Note: This follows the procedure described in the project description section 2.2

# 03-27 Ben uploaded a 3rd version (complete) of the standard MS code which includes:
  - No changes to the code from V2
  - Adds an effective_temperature_from_surface function to quickly compute Teff for the HR diagram
  - Adds a convective_from_dlogP_dlogT function to determine convective zones for the diagrams
  - Adds a load_reference_star_file function to load the low mass and high mass example stars' data and converts to SI units (works the load_example_stars_once function)
  - Adds a "Plotting Helpers" section which includes a bunch of plotting functions to create the following diagrams:
        - Model HR diagram
        - L-M Relation diagram
        - R-M Relation diagram
        A set for each high and Low mass star:
        - rho/rho_c, T,T_c, M/M_star, L/L_star vs. r/R_star plot
        - Opacity plot
        - Density profile plot
        - Pressure Components plot
        - Local Luminosity Production plot (plots total, PP, and CNO)
        - Enclosed Mass and Luminosity plot
  # 03-28 Rachel uploaded V4 of code
  -  fixed some plotting formatting issues (CPU maxed out so I can't finish the formatting until tomorrow)
# 03-29 Khushi updated DM changes
  - will add DM changes to new V3/4 of the code today with descriptions
# 03-29 Rachel finished plot formatting
  - plots are correctly formatted and ready for DM integration and presentation
# 03-29 Ben uploaded a V6
  - Addresses the incorrect MS from V3, adds the changes from V5 (Rachel) and also includes the DM heating (Khushi). 
  - Note: Issues include long runtime, weird R-M relation plot for MS, and odd behaviour for the DM heating models. Images of the plots generated from V6 have been provided here so you do not have to run the code.
