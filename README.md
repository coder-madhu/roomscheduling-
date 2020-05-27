# Conference room scheduling code

* **Step1:** Load given input into the array 

* **Step2:** Read input from command prompt.

* **Step3:** Parse meeting rooms information/[ Makeing list of available rooms].
             -  Get room capacity for each room.
             -  Build available slots info , by converting time to int
             -  Sort available slots with start time and endtime

* **Step4:** Parse the input and get the information

* **Step5:** Compare the input data against the available sorted slots information
	        Order: capacity -> start time and end time
	       Check  if it can fit in single room other wise try to fit in multi room based the flag

* **Step6:** If single room found
	       Check for the closest meeting room by distance and display
	       Other wise print multi rooms that are available for the given input
	       Even there is case also based on the data- No single or multi meeting room found
