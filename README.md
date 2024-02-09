# UBC-Elective-Finder

Every year, my friends and I are always on the hunt for high-average courses to take that can count for elective credits. I made this application to help my fellow students find the best electives to take given a department/subject they want to study and a certain course average threshold!

Technologies I used:
* I used Typescript to effectively convert a zip file with UBC course data to a more manageable local data structure as well as save it on disk to mitigate crashes.
* I then implemented an API to query this data structure for the averages of a specific course given by the user.
* I used React to implement a seamless and easy to use UI for potential users to quickly pick from the list of availbe courses and choose an average threshold.
* I implemented a Rest Api.

Unfortunately due to UBC restrictions, I am unable to share the full implementation that queries the UBC course data, but I have provided copies of the Front-End implementation and REST API calls.

Here is a demo: 

<img src="./Demo.gif" alt="screen-gif" width="714" height="524">

