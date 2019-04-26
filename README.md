<a href="https://elec-real.com"><img src="/docs/github.png" ></img></a>

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
 to easily shorting circuits which can generate immediate and intense heat resulting in fire. Conversation is
 welcome to improve this design and repository, but, be advised ER is a professional design house and
 monetary compensation is required for additional work toward this design enabling your success.			   
	 
![Inertial Sensor](/hardware/eagleUp/Earple/pucknbox.jpg)

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
			* <a href="https://oshpark.com/shared_projects/Yydb06ED"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>
	* firmware
	* software

	* readme.md	: this file
	
