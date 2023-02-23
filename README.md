# Ramon Torres
# streaming-05-smart-smoker app
# February 23, 2023
# Github repository:
# The Problem / Challenge To Solve
•	Please read about the Smart Smoker system here: Smart Smoker
•	Access the smoker data file here Download smoker data file here.
We want to stream information from a smart smoker. Read one value every half minute. (sleep_secs = 30)
smoker-temps.csv has 4 columns:

•	  [0] Time = Date-time stamp for the sensor reading
•	  [1] Channel1 = Smoker Temp --> send to message queue "01-smoker"
•	  [2] Channel2 = Food A Temp --> send to message queue "02-food-A"
• 	[3] Channel3 = Food B Temp --> send to message queue "03-food-B"

# Requirements
•	RabbitMQ server running
•	pika installed in your active environment
# RabbitMQ Admin
•	See http://localhost:15672/Links to an external site.
# General Instructions:
# Task 1. Create a Place to Work
1.	In GitHub, create a new repo for your project - name it streaming-05-smart-smoker
2.	Add a README.md during the creation process. (If not, you can always add it later.)
3.	Clone your repo down to your machine. 
4.	In VS Code, add a .gitignore (use one from an earlier module), start working on the README.md. Create it if you didn't earlier.
5.	Add the csv data file to your repo. 
6.	Create a file for your bbq producer.
________________________________________
# Task 2. Design and Implement Your Producer
1.	Implement your bbq producer. More detailed help provided in links below. 
2.	Use the logic, approach, and structure from Module 4, version 2 and version 3.
3.	These provide a current and solid foundation for streaming analytics - modifying them to serve your purpose IS part of the assignment.
4.	Do not start from scratch - do not search for code - do not use a notebook.
5.	Use comments in the code and repo to explain your work. 
6.	Use docstring comments and add your name and date to your README and your code files. 
7.	Explain your project in the README. Include prerequisites and how to run your code. 
8.	Document your project works - display screenshots of your console and maybe the RabbitMQ console. 
9.	If you only have a producer, you won't have a consumer showing messages yet, so you'll need to be creative. We'll build the consumers next.
# General Instructions are illustrated within the code.
# Data source:  Temperature readings from a BBQ Smoker for Food A and Food B. Data is organized by time stamp and headers.
# Deliverables: Code that will retrieve the data from a csv file, convert into messages and generates messages.  The output is shown as a string with time and temperature readings.
# General Instructions are illustrated within the code.
# Part 1 - Project 
1.	Clickable link to your public GitHub repo with custom README and displayed screenshot: 
2.	About how long did you spend this module:  about five hours
3.	Could you develop custom data pipelines for analytics using RabbitMQ and the resources available to you (y/n, why): Yes, still having configuration issues with my laptop, some slow internet connection, cut off the connection.  I was running a duplicate Python scenarios creatin some issues in VS Code Editor.
4.	What streaming analytics topics / techniques / skills do you think will be most helpful for the work you want to do: I will be applicable to any of the logistics and distribution scenarios presented in my graduate level courses.
5.	Describe an idea for a (relatively simple) custom analytics pipeline you might want to implement in Module 7:  I selected Option 2 for Module 7, as I must first solve the configuration issues on my laptop for the next academic period and time is of the essence on this one.  For Option 2, I decided to go with Amazon Kinesis and compare to Apache Kafka and RabbitMQ.  
6.	What was most difficult about this module:  Certainly, some of the coding was tricky and the configuration issues mentioned before. 
7.	What was most interesting: The approaches to manage queuing scenarios and its application to web streaming. 
# Part 2 - Self Assessment
From the Module 5: Overview, paste the numbered list of objectives and assess your ability on each as "Highly proficient", "Proficient", or "Not Proficient":
At the end of this module students will be able to:
1.	Implement a simple streaming data producer. (L06) Proficient
2.	Describe how data producers could be extended to transform data and extract information. (L07)   Proficient
# Screenshot:
