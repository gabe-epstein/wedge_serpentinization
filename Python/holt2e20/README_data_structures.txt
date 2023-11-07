
data_mat_norm=[3,5,118,500]
	[0]=slabtop, 5km, 10km files	# 
	[1]=X,Y,P_lith,P_tot,T 		# X&Y in km, P in GPa, T in C
	[2]=age step			#not actaul age
	[4]=evened X_spacing		#the age step read-in files were all different lengths, and had to be normalized

age=[118,500]
	[0]=age
	[1]=repeated age

array2=[4,101,118,1300]
	[0]=X,Y,P,T
	[1]=depth in slab		#0 to 10000m in 100m increments
	[2]=age step
	[3]=X-spacing			#in km from absolute min to absolute max, unfilled elements are assigned NaN

ppx_out=[7,101,118,1300]
	[0]=rho,rho_fluid,fluidwt%,meltwt%,rho_melt,KgH2O,KgH2O_liberated
	[1]=depth in slab
	[2]=age step
	[3]=X-spacing

map_fl_mass=[118,1300]
	[0]=cumulative fluid mass for each column
	[1]=X-Spacing

age2=[118,1300]
	[0]=age
	[1]=repeated age

map_fl_flux=[118,1300]
	[0]=age
	[1]=flux kg/m2column

Y_map=[118,1300]

map_fl_tot=[118,]

convergence=[118,1300]

dip_rad=[118,1300]

delta_depth=[118,1300]



app_sr=[118,1300]

S_rate=[118,]

h20_in=[118,]

efficiency=[118,]