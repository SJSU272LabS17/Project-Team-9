# Project-Team-9
**********************NOTE : WE ARE TEAM 9 ON GITHUB AND TEAM 15 ON CANVAS, SO, FOR THIS PROJECT, PLEASE GIVE THE SURVEY ON TEAM 15 IN CANVAS(KAMESH GANGWANI, AKANSHA MEHTA, RAKSHA KASHYAP, NIVEDITA NADKARNI)*******************

### Project Idea 3 Title: IOT Sensor Weather Chatbot - APPROVED

Abstract :-

With everyday changes in the technology today, people need more comfort and easy to use devices. In this project, we have created a weather bot which fulfills a user’s need to know the room temperature, humidity, and intensity of light for
various purposes including Air Condition mode, conducting a laboratory experiment and maintaining a proper environment
for the workers in the manual labor industry. It also sends an alert message when the room environment is above or below your
comfort or desired level. 

Follow this link in order to chat with our Weather Bot : https://iot-sensor-chatbot.mybluemix.net/bot

Summary:

- Using IBM Bluemix services (Node-RED, Watson IoT Platform, dashDB and Watson Conversation), we have created a chatbot allowing us to ask questions like: What was the average temperature value you recorded ?, What is the maximum intensity of light today ?, How humid it is today? 

- Apart from this, it also sends email notifications as alerts to the user!

- Used Texas Instrument TI CC2650 IOT sensor which senses Temperature/Humidity/Light and other weather related values.

![alt text](https://raw.github.com/SJSU272LabS17/Project-Team-9/master/Sensor.jpg)

- Used the above sensor to push real time Temperature/Light/Humidity values to Watson IoT Platform.

![alt text](https://raw.github.com/SJSU272LabS17/Project-Team-9/master/IoT.png)

- Used Watson Conversation service as machine learning tool to train the chatbot to analyze the user input and provide appropriate responses.
  
![alt text](https://raw.github.com/SJSU272LabS17/Project-Team-9/master/Watson_Dialog.png)

- Created Node-Red flow that glues everything together:
  
  (i) Wired Watson IOT Platform node with Dash DB node in order to populate DB with real-time values of the surrounding weather captured by the sensor.
  
  (ii) Used Javascript in order to set up Client/Server page and AJAX to invoke Server using REST API calls.
  
  (iii) Captured the Conversation’s input and output.
  
  (iv) Refined the chatbot answers by SQLs queries where max/min/avg/latest Temp/Humidity/Light values are the user input.
  
  (v) Sending the responses to the client

  ![ScreenShot](https://raw.github.com/SJSU272LabS17/Project-Team-9/master/node-red.png)

  (vi) The bot also sends Email alerts to the user when the temperature or humidity value increases or decreases beyond a comfortable range! This range of values is customizable according to the user's needs.

 ![alt text](https://raw.github.com/SJSU272LabS17/Project-Team-9/master/Alert.png)

- Our app: Weather Chatbot! 

 ![ScreenShot](https://raw.github.com/SJSU272LabS17/Project-Team-9/master/chatbot.png)


Use Cases :

- At home: ask what the average temperature in a room was during a given day, then adjust the start/end time of your heating or air-co depending on that. This could save costs …

- Monitoring temperature in places Like laboratory where environment temperature is very important for experiments.

- In any industrial environment (e.g. Mining) where Workers Health & Safety is key: what if in the case of a crisis situation, every member of an Operations Centre had the ability to ask in plain English: ‘What is MAXIMUM, MIN temperature, Light intensity, & Humidity’ ? This could save lives … 

- Let's say you are in office and want to monitor temperature of house.

-------------------------------------------------------------------------------------------------------------------------------
Old project ideas:

Project Idea 1 :

Title: Notification application for Stock Exchange shares. 

Abstract: With growing investments in the stock market by working class people, a high number of people are unable to frequently track the stock prices of the companies they have invested in, due to lack of time. This situation might lead to a loss of an excessive amount of money if the stock prices of the companies go down. At the same time if there is a rise in stock prices, the stock holder might miss a good opportunity of selling it. In this project, we will be designing web application which will be responsible for notification of stock price fluctuation. The user will set a range of minimum and maximum stock prices, which will act as threshold for selling the shares. The web application will alert the user when the stock price reaches the threshold value, so that the user get a chance to sell it at the right time to gain the maximum profit or save his/her money with minimum loss. With this application, the user need not keep a regular check on the share prices. To perform this, our system will be connected to Stock exchange to monitor the prices, which will be constantly updates in a database, and send an alert via E-mail to the user when the price reach near the threshold value.
Following API is planned to be used for this project - http://dev.markitondemand.com/MODApis/

Project Idea 2 :

Title: Freelancer platform for charitable electronic work

Abstract: People willing to volunteer for a cause, often faces hurdle of finding options of the organizations who conduct such volunteer program or work. This leads to the volunteers signing up on the first website they find on a google search or an organization which is nearby. In this project, we are planning to create a platform for multiple organization with multiple causes and events to post their volunteer work/program. A person, who is willing to volunteer, will have ample options to select the volunteer work he/she wants to pursue, based on his/her talent and interest. The volunteer programs will have a wide range of work including creating a database, spreadsheet, grading papers, volunteering to organize community events etc. The work which is already assigned will no longer be visible on the available work forum. A person can volunteer for multiple work with a maximum limit of four work at a time. The work will be assigned to the next available person on the wait list if the volunteer responsible does not finish the given job. Badges will be awarded to the volunteers on social media website such as Facebook and employment oriented social media website LinkedIn, after completion of their work. 
