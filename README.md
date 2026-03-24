# PHYS-375-Final-Project
# 03-15 Ben uploaded a starting point for the standard MS sample code
# 03-24 fixed small mistake in markdown file correct one is "375markdown"
# 03-24 Ben uploaded a 2nd version of the standard MS sample code which includes:
  - No changes to the code in V1
  - Adds a luminosity_surface_error function which calculates the shooting method error when compared to the target boundary condition
  - Adds a solve_star_for_Tc function which finds the right rho_c for a chosen T_c using the luminostiy_surface_error function
  - Adds a build_main_sequence function which constructs a collection of stellar models by solving for a star for each Tc in Tc_Values
  - Note: This follows the procedure described in the project description section 2.2
