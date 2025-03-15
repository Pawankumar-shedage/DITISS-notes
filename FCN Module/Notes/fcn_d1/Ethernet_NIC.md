#NIC:
	
   
#ETHERNET-Working:
	CS : Carrier Sense
	MA : Multiple Access
	CD : Collison Detection (
		-detected when multiple devices try to access the network (rise in voltage: other than +5-> 1, +2 -> 0, 0.5v -> base voltage 		 of the network.
		-now the "BACK-OFF Algorithm" gets executed: assigns timer (in nano-secs) for each device on the network.
		-When the timer of a device is finished then it can access the network!
			- here no matter how many devices are in queue to access the network
			- the device which will actually get network access depends on the "CHANCE"
		)

