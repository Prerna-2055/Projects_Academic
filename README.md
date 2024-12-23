# Project Title: Predicting Energy Efficiency (heating load and cooling load) of Building given the building characteristics 

The data is from a study on assessment of the heating load and cooling load requirements for buildings, given the building parameters.
- The energy analysis is performed using 12 different building shapes simulated in Ecotect. 
- The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. 
- Various settings are simulated as functions of the afore-mentioned characteristics to obtain 768 building shapes. 

The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses: heating load and cooling load. 


Variable_Name |	  Role	 |     Type	  |      Description	Units	
X1	            Feature	    Continuous	  Relative Compactness
X2	            Feature	    Continuous	  Surface Area
X3	            Feature	    Continuous	  Wall Area		
X4	            Feature	    Continuous	  Roof Area		
X5	            Feature	    Continuous	  Overall Height	
X6	            Feature	    Integer	      Orientation		
X7	            Feature	    Continuous	  Glazing Area		
X8	            Feature	    Integer	      Glazing Area Distribution		
Y1	            Target	    Continuous	  Heating Load		
Y2	            Target	    Continuous	  Cooling Load		
