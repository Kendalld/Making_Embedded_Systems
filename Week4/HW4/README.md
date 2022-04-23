
The assignment for Week 4 was to make an early state machine for your final project
My final project is a single button interval timer to control a stopwatch
We were given the choice of a flowchart or a spreadsheet
I tried the spreadsheet, but could not figure out how to correctly label intervals eg. if the state machine receives 2 short button presses in a 0.5 second window, I would like the wiper to act as quickly as possible

[Spreadsheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vR33M2Vl9SorstKrM8Pg2T9E52zRZcc4QYLHQ2VaE9nz2LGbmsoFsAXsLohDkFI9-iAtTYiAQ1U1FmG/pubhtml)

	• Two button quickly fastest setting
	• Single short button press should send only a single wipe
	• Immediately after a short press timeout it is assumed that a wipe is desired to start
	• Start has to be short press
	• Long press has to trigger start count on falling edge and stop at rising edge
	• I need to distinguish 
		○ Press length
			Short Press
			Long press
		○ Press Interval 
			Short Gap 
			Long Gap
			
			
		
	
