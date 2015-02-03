#Artsec SDR Meetup


##Getting Started


###What are Software Defined Radios?

Currently most radios you can buy off-the-shelf are designed to do one thing. Like Bluetooth, or Wi-Fi or GSM. However Software Defined Radios allow you to use the same hardware to "program different radio architectures". The analogy I like to use is that current radi chipsets are like calculators and software defined radios are computers.

*"Radio components such as modulators, demodulators and amplifiers are traditionally implemented in hardware components. The advent of modern computing allows these traditionally hardware based components to be implemented into software instead. Hence, the software defined radio. This enables easy signal processing and thus cheap wide band scanner radios to be produced.""*




###What makes them special?

In case you're wondering what makes this possible, its the falling price of hardware. 

With the advent of USB 3.0 it is possible to get really high sampling rates that are usually needed to decode signals at high frequencies.

Powerful microcontrollers that run the board and program the FPGAs are pretty cheap.

Chips known as [FPGA](https://en.wikipedia.org/wiki/Field-programmable_gate_array)s and [CPLDs](https://en.wikipedia.org/wiki/Complex_programmable_logic_device) are basically integrated circuit breadboards that you can program to be whatever you want. These are the boards hardware manufactures use when they are desinging new integrated circuits and have traditionally been frightfully expensive. 


###What are the different boards out there?

 Specs         |RTL SDR        		| Hack RF      		| Blade RF     			|USRP (B100) 		|    
:-----------   |:-----------   		| :----------- 		| :----------- 			| :-----------
Price		   | 20$        		| 320$		  		| 420$		 			|~ 600$		 		|
Open Source	   | Center        		| Right		  		|						| dfds		  		|
Radio Spectrum | ~ 50Mhz - 1.5 Ghz 	| 30 MHz – 6 Ghz 	| 300 MHz – 3.8 GHz 	| 50 MHz –2.2 GHz 	|
Bandwidth      | 2.8 Mhz(max stable)| 20 MHZ		  	| 28 MHZ 		 		| 16 MHz 			|
Duplex	       | Half (Rx only)     | Half		  		| Full	 		 		| Full				|
Sample Size	   | 8 - bit        	| 8-bit		  		| 12-bit 		 		| 12/14 12-bit 		|
Sample Rate	   | 2.4 MS/s        	| 20Ms/s		  	| 40 Msps 		 		| 64/128 Msps		|
Interface	   | USB 2.0        	| USB 2.0		  	| USB 3.0 		 		| USB 2.0 			|
	|

##Resources
[Towers Of Power materials](https://itp.nyu.edu/classes/towers-spring2014/readings-resources/)

Towers of Powers is a course taught at ITP by the amazing [Benedetta Piantella](http://www.benedetta.cc/bio.html) that aims to teach students about GSM networks. How they work, their politics and how to use them in their projects. The link above has a lot of good material for anyone more interested in GSM.


[Setting up Blade RF with Yates BTS](https://github.com/samatt/ArtSec-SDR/blob/master/running_yate_bts_with_bladerf_on_ubuntu_14.04.md)

[Setting up USRP1 with Osmobts](https://github.com/samatt/ArtSec-SDR/blob/master/running_osmobts_with_usrp1_ubuntu_12.04.md)