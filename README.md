# Work Day Scheduler

Create a 9-5 daily planner where you can save an event that the user inputs. The text inputted should be kept on the page even after refreshing. The time blocks should be color organized based on the time of day where it'll be green for present time blue for upcoming times and gray when the time is passed.

## The process

### What i did
* I duplicated the time cards and gave them their own ids 
* Added a click event to the save button that grabs the section that is selected and the text that is inputted in the description area to be set into local storage
* Added the current hour using dayjs and formatted to be the 24 hour clock
* Made a .each function for the time blocks to check to see if each one is equal to, greater than, or less than the current time to add colors for past, present or future
* Created a way to get from local storage using the id of each time block so the users text stays in that box
* Created a date displayer for the top of the page using dayjs

![A 9-5 Schedule that is blue green and gray and has text that says meeting in the 3pm slot](https://github.com/nathan26036/work-day-scheduler/blob/main/Develop/images/Schedule%20screen.PNG)
  
## Installation 
The final code deployed can be found at https://nathan26036.github.io/work-day-scheduler/ 


