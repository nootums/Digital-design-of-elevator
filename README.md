# Digital-design-of-elevator
Design for a 6 storey elevator

This design takes the following inputs:

    1.) 0-6 floors' buttons
  
    2.) Emergency button to stop the elevator
  
    3.) Door open and door close buttons
  
    4.) Fan
  
    5.) Floor sensor(gives a spike when a new floor is reached)
  
    6.) Overload sensor
  
    7.) Warning sensor
  
    8.) Motor overheat sensor
  
    9.) Door IR sensor(keeps the door open when there is an obstacle in between)
  

This design gives the following outputs:

    1.) Motor up
  
    2.) Motor down
  
    3.) Door open
  
    4.) Fan
  
    5.) Overload warning
  
    6.) LED for the floors
  
    7.) 7 segment display
  
  
The MUX in the top right corner is for switching between automatic simulation of the circuit and the manual floor sensor input.
When input to the MUX is 0, the floor is incremented automatically, and when the input to the MUX is 1, thr floor counter depends on the floor sensor.



Additional Functionalities:


    1.) Sensor inputs for fault conditions added in the circuit for situations under which the elevator might fail to run, or come to a halt for emergency evacuation of people. The normal/warning state of these is visible in the circuit by the respective LED. These sensors are:
      
          ○ Lift Overload - gives a warning when there is a weight overload
        
          ○ Door IR - responsible for opening the elevator door in case any
          obstacle blocks it and prevents it from closing.
          
          ○ Motor Overheat - gives a warning depicting motor overheat
        
          ○ Warning sensor - for activating a warning alarm in the elevator
        
    2.) Emergency Stop button for stopping the elevator immediately in case of emergency.

    3.) Fan button to switch on/off fan in the elevator.
  
    4.) Door opening and closing buttons for controlling the door.
  
    5.) Door opens when the button of the present floor is pressed
  
