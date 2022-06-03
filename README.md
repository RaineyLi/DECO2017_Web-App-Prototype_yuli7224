# STUDY SPACE FOR YOU:
> This is a study webstie for the students to manage their study. The users will be able to use four functions contained in the app: Music Player, Tasklist, Timer and Acronym Maker.

## HOMEPAGE:
The homepage of the webstie mainly uses all the design elements I made in my mock up. The main color theme of the website uses the collocation of low saturation green and beige, which can make the users feel very relaxed, can more easily let students into the state of learning. The cover image and the location of the music player haven't changed much. 

![Left: Mock up; Right: Prototype](doc/homepage.png)

The background of the interface and the background of the webstie has been switched because I want to create a strong color contrast between the text and the white background. This will make the lay out of the submain section clearer and easier to read.

## TASK LIST:
I have made some changes to the parts except the main page. To minimize the number of pages, I chose to use a floating window instead of a paging surface, which would reduce the wait time for users to switch pages. At the same time, it can make the picture more concise and hierarchical. In the part of filling in options, I use the select function to replace the part of intext, in order to make it more convenient for users to fill in task information, and also convenient for the system to classify and filter.

![Left: Mock up; Right: Prototype](doc/tasklist.jpg)
After the user submits the task information, they can see their tasklist displayed on the TaskList. They can see the Task Name,	Priority rating,	Estimated time to complete,	Completion status	and Due date. The localStorage function helps to save their data on the web enable to prevents the data from being flushed.

## TIMER:
There will be three variables for the users to set the timer. Two study timers and one break timer. When the first study timer is ended, it will automatically start the rest timer, and then start the second study timer. The timing will stop automatically when all the time is finished. The users can start and stop the timer through the buttons beside the timers. And they can also change the setting of the timers in the “ADD NEW TIMER” floating window. 
