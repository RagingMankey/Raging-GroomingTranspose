# Raging-GroomingTranspose
Groom Data that is in a single column to a nicer view that suits your methods.  

#Why? 
Have you ever been annoyed that a website does not have a text export option but you need to read and filter data and would like to better filter or read the data?
Then boy oh boy this simple script may be for you. This script will be used to create a Macro in Google Sheets to easily transpose a single column range.  

#Example
You have a chat log with a facebook scammer. But you want to reference certain parts of the chat for a YouTube Video or to have a laugh with buddies on Discord.....Strange? Yes I know
So Now we have our Scenario. We now have the chat log Copy and pasted into a Gsheet. In the Gsheet We sigh as the data pasted in a single column(oh how I wish it would've just pasted as a table xD) Here's how the data looks after removing all that other text crap not needed. 

(All Lines are rows, the contents of each row is a single cell)
Rage
OMG WHY you try to scam me!
A god on Facebook you dare impsoe me
12/10/22 10:44PM
Scammer
I am not a scammer you are mistaken
12/10/22 10:45PM
Rage
You litterlay are tying to make me a money Mule!
Scammer
No
12/10/22 10:47PM
please let me explain on a video chat
Please I need an employee and can't wast my time on people who don't want to work
12/10/22 10:49PM
Fine please forget this job offer
12/11/22 11:00AM

(Commas would be the end of the cell, weird number string is just the date in a value form, can easily be changed by changing format to "Date and Time", or if not needed then groomed out before macro etc..)
Rage,	OMG WHY you try to scam me!	A god on Facebook you dare impsoe me,	44905.94722											
Scammer,	I am not a scammer you are mistaken,	44905.94792												
Rage,	You litterlay are tying to make me a money Mule!						
Scammer,	No,	44905.94931,	please let me explain on a video chat,	Please I need an employee and can't wast my time on people who don't want to work,	44905.95069,	Fine please forget this job offer,	44906.45833

From this stage this makes the chat a bit more readable. Each row essentially becomes what person A says then the reply of person B and so on.

#Setup
Will update section at Version 1.0, but a keen eye should be able to laugh at this spaghetti code and be able to use it xD 

#Future State
If I end up using this macro again then I'll update it to be more functional and user friendly. 
For now this seems to be a one off solution to a very niceh scenario for myself. But I've used a funtion in the past to accomplish somethign similar. 
TLDR; Might not ever use again, keeping safe in the event I see a usecase again. Expect this to be DOA.

#What I learned 
I learned that I should not be using Facebook to look for reliable work. 

#Version 0.5
