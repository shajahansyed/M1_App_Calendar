# REPORT
# 1. Requirements
## Intoduction
A calendar is a system of organizing days. This is done by giving names to periods of time, typically days, weeks, months and years. A date is the designation of a single, specific day within such a system. A calendar application can find what's the day is or can fetch whole month. It can also add note to a particular day in a particular month of a particular year.
## Objective
In this application user can choose from one of the following options appeared in homepage.
1.  Find out the day
2.  Print all the day of month
3.  Add Note
4.  EXIT
## State of art
![SA](https://user-images.githubusercontent.com/94296103/143249653-f4061ee4-5c8d-49ab-a250-1d1b69511ace.jpg)
## Research
Calendars are useful tools for keeping track of upcoming meetings, deadlines, and milestones. They can help you visualize your schedule and remind you of important events, such as holidays and vacation time.

It’s no wonder that people often have a variety of calendar tools to choose from, including everything from a paper calendar on their office wall to a calendar management tool, such as Calendly. 

The problem is that people too often manage multiple calendars at once. When these calendars aren’t integrated with your work and synchronized with each other, this can lead to mass confusion, headaches, and missed deadlines.
## SWOT Analysis
### Strength
-   This application can find the day of particular date.
-   Shows weeks and days of a month.
-   Can add note to a day.
### Weakness
Not a fully funtional calendar application like cannot set reminders for events.
### Oppurtunities
Online calendars can be used as a way to increase your productivity. One example of this is through time blocks. You can schedule time to work on important projects allowing you to complete those that are a priority or have deadlines.
### Threats
-   Data corruption is possible, altering or even deleing events.
-   Too many options can make simple event scheduling complicated.
-   Need physical access to your computer or PDA/smartphone to see schedule.
-   On PDAs: batteries can fail, leaving you calendar-less.
-   Steeper learning curve than paper.
-   Dependent on technology.
## 4W's and 1H
### Who
The primary practical use of a calendar is to identify days: to be informed about or to agree on a future event and to record an event that has happened. Days may be significant for agricultural, civil, religious, or social reasons.
### What
A calendar is a chart or device which displays the date and the day of the week, and often the whole of a particular year divided up into months, weeks, and days. A calendar is a particular system for dividing time into periods such as years, months, and weeks, often starting from a particular point in history.
### When
Calendars are useful tools for keeping track of upcoming meetings, deadlines, and milestones. They can help you visualize your schedule and remind you of important events, such as holidays and vacation time.
### Why
Calendars play an important role in our daily work to help us stay on task as well as be productive and prioritize. By using them to schedule our daily work we can avoid distractions and get back on track when interrupted.
### How
A year is defined as the amount of time it takes for the Earth to orbit the sun one time. It takes about 365 days to do that.
## Detail Requirements
### High Level Requiremnets
ID|Option|Description
---|---|---
`HHR_1`|Find out the day|Shows the day for particular date
`HHR_2`|Print all the days of month|Fetches the month of a year
`HHR_3`|Add Note|Adds note to a day
`HHR_4`|EXIT| Quits the application
### Low Level Requiremnets
ID|Request|Description
---|---|---
`LLR_1`|List of operations|List of operations
`LLR_2`|Input from the user|Select an operations
`LLR_3`|Exit the program|Quits the operation
# 2. Design
#### Main page shows user to choose the operation

`1. Find out the day`

`2. Print all the day of month`

`3. Add Note`

`4. EXIT`
## Low Level Design
### UML Flowchart
![FLOW](https://user-images.githubusercontent.com/94296103/143031379-93d127ec-ae9f-4a01-b3f0-bcdc3054699d.jpg)
## High Level Design
### UML Usecase Diagram
![USE](https://user-images.githubusercontent.com/94296103/143037289-8101a897-6ac1-46e2-b00c-e5a41fca946a.jpg)
### UML Class Diagram
![CLASS](https://user-images.githubusercontent.com/94296103/143038384-3092e51b-432b-4bd2-b637-ea83e2874c94.jpg)
# 4. Implementation
## Folder Structure
Folder        | description
--------------| ----------------------------------------------
`cov`         | .gcno and .c.gcov files for testing c program 
`doc`         | Doxygen configuration file which can generate documentation in html
`inc`         | All header files
`src`         | Main source code for calendar
`test`        | All source code and data for testing purposes
`build`       | Build output (Not included in git)
# 5. TestPlan
## High Level Test Plan
ID|Option|Input|Output
---|---|---|---
`H_1`|Find out the day|Day(int)/Month(int)/Year(int)|Day(string)
`H_2`|Print all the days of month|Month(int)/Year(int)|Days(int)/Month(string)/Year(int)
`H_3`|Add Note|Day(int)/Month(int)/Year(int)|Note(string)
`H_4`|EXIT|integer|Quits the application
## Low Level Test Plan
ID|Request|Description
---|---|---
`L_1`|List of operations|List of operations
`L_2`|Input from the user|Select an operations
`L_3`|Exit the program|Quits the operation
# 6. Images and Videos
## Home Page
![image](https://user-images.githubusercontent.com/94296103/142887298-aee40bcc-8a25-4630-9eab-c92f3fc75c82.png)
## Find out the day
![image](https://user-images.githubusercontent.com/94296103/142890011-27c64fa6-8050-402b-ab4d-51a582be614a.png)
## Print all the days of month
![image](https://user-images.githubusercontent.com/94296103/142890156-fb45dc72-aeda-45de-8356-8f149bd5a92d.png)
## Add note
![image](https://user-images.githubusercontent.com/94296103/142890374-d2b6e91d-d9c5-4dce-bf34-7994852dc8f5.png)
## Exit
