# CS-350
Emerging Sys Arch &amp; Tech
Summarize the project and what problem it was solving?
The first project with the led was just to get the light to blink and then moved on to more complex ideas. The final project consisted of creating a thermostat which allowed user input via UART to accept an initial set point. After initialization, the TI board would then activate a sensor to read the current temp within the room. If the temperature was greater or lower than the setpoint, the value would increment or decrement in order to reach the user specified set point. If the temp needed to increase, the TI board would have an LED turn on using GPIO to signify the temp was heating up, and would shut off when the temperature reached the setpoint.

What did you do particularly well?
I think that my approach to breaking apart pieces of the code to increase readability was my strong point. My primary experience in development comes from courses taken in this degree and not much else. But I attempted to keep things organized, and follow best practices.

Where could you improve?
I think I could improve upon my in line comments, I have not received feedback that i need more but maybe my work could use more explanation of the functions in place.

What tools and/or resources are you adding to your support network?
I've never worked with Code Composer Studio before so that is a new for me. And the resources from TI were a new experience for me.

What skills from this project will be particularly transferable to other projects and/or course work?
Reading the TI board's documentation and the online tutorials helped me through most problems. And GitHub is a great resource for when I got stuck.

How did you make this project maintainable, readable, and adaptable?
In general I have tried to breaking projects into smaller chunks and saving and building often helps in the long run with maintainability. Doing this allowed me to quickly find the code and isolate problems when working through the project and resetting the board often was a crucial toward completion of the debugging.
