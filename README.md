# agile-project-proposal
My proposal for the Agile Software Development project. 



# Title

Commuter Calculator 


# What and Why?
  A common problem many commuters living in NYC face daily is the unreliability of the MTA Subway system. With some trains boasting an average of over 50% unreliability in making it to a stop on time, commuters never have a good idea as to how early or late they can leave their house to get to their destination on schedule. The Commuter Calculator Web App, using the MTA Real-Time Data Feeds API and a MongoDB database, will continuously calculate the average time it takes a train to arrive after the stop displays that it is one minute away. In doing this, it will find the average delay in one's commute using the train. Furthermore, one can piece together their commute based on available transfers at each stop to add up average potential delays (e.g. if one has to take the Q to the F, with each being 2 minutes late on average, the user will know to allot 4 minutes in addition to whatever the commute time Google Maps/Citymapper displays). 
  
 # For whom?
   This technology will be useful for most commuters who have to get to a location at a specific time. This includes anyone from college students, to employees, to people who have to meet up with their friends. Most would find it important and worthwhile because, while Google Maps and other similar apps do an incredible job of estimating travel time, they do so on the assumption that trains arrive on the real-time schedule they are announced to arrive at. This app would bridge the gap between those estimates and the reality that is the MTA's lack of reliability. 
   
 # How?
 
  The trains would be displayed in a list (represented by each trains' respective symbol), and the user could choose specific trains to know their average lateness, or add them into a queue to represent combined travels and gauge lateness over a trip with many transfers. Ideally, trains can only be queued up together if transfers between all of them are available. 
  
 # Scope
   While the calculations seem very simple for a group of 4, the brunt of the tasks fall under getting the developer key for the MTA real time services, creating and regulating a database to continuously calculate the average, and adjusting for delays and changes to schedule at night and on weekends. These tasks seem like too much for a single person to calculate, but just enough to provide a challenge for a group of 4. 
