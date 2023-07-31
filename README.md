# Crypto-Coin-Tracker Production
This was an assignment given to me by SAPCONET as vacation work. It scrapes the latest data from the Coin Market website and sends an email with the top 10 coins.
It solves the problem of having to go to the website everyday and looking for the information yourself.

I solved the problem by first making the dispatcher. I used an Object Explorer in UiPath Studio to define the table.
I scraped the first 10 items and created a new queue item for each.
Then I made the performer. I used the Robotic Enterprise Framework to build an Excel workbook and attach it to an email.
I also used the a free API endpoint to convert the USD to ZAR for price.

I solved the problem by doing as much research as possible, I watched a lot of videos and read the documentation on UiPath.
Me and my friend who did the vacation work with me also helped each other when struggled with something.
