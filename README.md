
![ER_LOGO](/docs/github.png)
>Electronic Realization L.L.C.								   
>Design: 9 axis inertial sensor with bluetooth communication		   
>Engineer: Cy Drollinger								   
>Date: 2/19												           
>Email: cy@elec-real.com								   
>Address: 2023 Stadium Dr Suite 2B #210 Bozeman, MT 59715				   
>Phone: 406-539-8117	

**NOTE:**
 This design has been tested and functions as specified. The design is provided gratis, so, please 
 think critically while utilizing and or redesigning. Open electronic circuitry can be dangerous due 
 to easily shorting circuits generating immediate and intense heat resulting in fire. Conversation is
 welcome to improve this design and repository, but, be advised ER is a professional design house and
 monetary compensation is required for additional work toward this design enabling your success.			   
	 
![Inertial Sensor](/hardware/eagleUp/Earple/pucknbox.png)

**PURPOSE:**
This electronic system is capable of sampling inertial data from the mpu9250 at 1 kHz and storing to 
a uSD card for GB storage, fatfs. The design files were created with Eagle Cadsoft v7.7 as a 
two layer board. Free Eagle version would be capable of viewing, and editing these files for redesign. 

>**File Arcitecture with a terse description**


* FOLDERS:
	* docs		: datasheets charging IC and battery holder
	* hardware	: eagle cadsoft(v7.7) hardware design files 	
		* eagleup		: 3D files 
		* library		: eagle part files 
		* manufacturing	: files required to produce the design
			* bom	: files created to order the parts
					* batteryCharger.txt	: 
					* batteryv1.1.csv	: digikey order
					* hundredUnits.txt	
			* gerber	: files generated to manufacture the board
			* https://oshpark.com/shared_projects/4os8OxLZ
	*firmware
	*software

	* readme.md	: this file
	
