# Computer Science IA - TUNECORE a music streaming platform
This is a music streaming site that allows people to listen to indie artists and choose genres and countries to their liking.

![TUNECORE](https://github.com/Verlonskg/TUNECORE/assets/111814707/89ac97a9-9fdc-4fea-821a-e5b5dfcd0d70)
**Fig.1**

# Criteria A: Planning

## Problem Definition
The client is an owner of a private record label he is willing to make a music streaming platform that only features the songs from the artists that are signed with his label and to have exclusive access to unreleased albums or early access to live event tickets or merch with a monthly subscription of a VIP membership. He thinks that it will help grow the customers and people who will have an interest in the music that is produced by his label. He is also showing interest in recruiting many more artists to expand his business and hopefully marginalize his profits. He says he wants a whole different style to the service for the VIP members since he wants to increase the number of customers who will be willing to pay for the VIP membership. He thinks that there could be visible differences in the graphical user interface it will be more effective than only having an early access feature. He says he will be naming the company TUNECORE and it will hopefully revolutionise how the music service industry works right now.

## Proposed Solution
Based on the client's request I will be developing a web browser-based music streaming platform with two subscription options. This platform will have a similar feature as all of the other streaming platforms for the basic feature so there will be a user registration system where the customers can sign up for the service and make an account where they can use either email or phone number and set a password for extra security. There will also be a feature where they can link an account to make the account using other services such as Google or Twitter. Once you have an account you can search for artists, and songs and also make playlists just like a normal music streaming platform. 

Since the client is willing to only feature the artist from his record label with unreleased albums, there will be a subscription for regular customers. 

## Design statement

I will develop a music streaming platform, and there will be two distinctively different sections that will be split into regular subscribed customers and VIP subscribed customers. The regular one will have a while biased UI with only the basic functions and there is no access to the VIP page where you can preview incoming events, merch, and songs exclusively. There you also get discounts for live event tickets and more.

## Rationale for proposed solution

### Flask
For developing the website app, I will be using the Flask framework. Many developers use Flask to make websites that are easy to use and load fast, which is great for our users. Flask is also flexible, meaning if we need to add more features or make changes down the line, it won't be as difficult, and again this will be favourable for scalability as well.

### Python

I chose Python to program most of the website's functionality, so this will be the primary language that I will be using for this project. It's great for web development because it has many frameworks that make the job easier. Also, it's really handy when working with databases, which is perfect for setting up an inventory on the website. Python also has lots of libraries that simplify complex functions, making my coding work more efficient, and because it is a very common language that is used by many developers, it will be good for future scalability and expansion too.

### HTML
HTML is my choice for developing the website's layout and structure of the graphic user interface (GUI) of TUNECORE. By using HTML, I can organize content effectively, making sure that the website is not only functional but also easy for future developers to navigate. HTML is the backbone of any website, providing the basic framework that is very well organized so it is a reliable tool for web development, ensuring that the site will work well across different browsers and devices.

### CSS 
I will be using CSS to create the design for the webpage that will catch the user's attention and an easy-to-understand user interface. The project will have the best maintainability and scalability by keeping the structure using HTML and design with CSS. Its versatility and wide range of features, such as animations and adaptable design can help me to create an aesthetically pleasing and interesting user experience that appeals to both VIP and regular members.

### SQL
For managing the database, I will be using SQL. It's really fast, which means our web pages will be able to connect the media and data stored in the SQL database quickly when the website is accessed. Plus, our database will be quite complex with the user information and media used for posting the audio that will be streamed. So SQL is the best choice for handling that kind of complexity efficiently, allowing me to quickly add more to the database.

## Success Criteria

| No. | Success criteria	         | Issue tackled       |
|----------------------------|---------------------------------|----------------|
| 1 | The platform has a User system with a password and the ability to link with other social accounts such as Google and Twitter. | The client wanted a secure system since the service has two options of subscription | 
| 2 | The platform has different GUIs for different subscription types. | The client wanted a more attractive GUI for the VIP users to increase the VIP subscription | 
| 3 | The platform allows users to search for songs and artists, and also make a playlist which you can also share with people. | This function increases users' usability and also increases the artist's stream amount | 
| 4 | The platform has a VIP section which is only accessible to VIP users and it shows the new release of albums and merch, as well as the live concert information.  | This was a feature that was requested from the client | 
| 5 | The platform has a miles system where you get a certain amount of miles for every streaming length you reach.  | This was also a function that was requested to be added by the client | 
| 6 | The platform has a section called "create" where you can fill out a survey and request to book a meeting with the client to discuss about signing a contract with the label. | Since the client was saying that he wanted to expand his business by accepting more underground artists this was a function created accordingly for his issue | 

# Criteria B: Design

## System Diagram
![](https://github.com/Verlonskg/TUNECORE/blob/main/Pictures/System_Diagram.jpg)
**Fig.2** shows the system diagram for the proposed solution, I used Pycharm and Flask to develop the website.

## ER Diagram 
![](https://github.com/Verlonskg/TUNECORE/blob/main/Pictures/ER%20Diagram.png)
**Fig 3** ER diagram showing how the databases are connected

### Table
Test Users:
|id    |Username    | Passwords | 
|---|---|----|
|1     |   Daimei      |**********     | 

Test Artist:
|id | artist_id | artist_genre | artist_name | streaming_num |
|---|-----|----|-----|-----|
|1    | 1        | Dance  | Daimei  | 1,237,390  |

Test Song:
|id | artist| title   | genre | file | date | 
|---|-----|----|-----|-----|----|
|1   | Daimei     | Let the Beat Drop       | Dance  | 1 | 12/23/2023 |

Test Concert:

|id  | artist   | date  | location   | ticket number | 
|----|---------|-------|-------|-----|
|1   | Daimei       |4/13/2024    | Tokyo Central Dome | 5,000  |



## Wireframe Diagram 
![](https://github.com/Verlonskg/TUNECORE/blob/main/Pictures/Wireframe%20Diagram.png)
**Fig 4** This is the wireframe for the original design of TUNECORE 

## Flowchart

![](https://github.com/KaiFig/IA/blob/main/pictures/CS%20IA%20Flowchart%201.jpg)
**Fig 5** This showcases the flowchart for the calendar page 

![](https://github.com/KaiFig/IA/blob/main/pictures/CS%20IA%20Flowchart%202.jpg)
**Fig 6** This is the flowchart for the login page.

## Record of Tasks
| Task No | Planned Action                                                | Planned Outcome                                                                                                 | Time estimate | Target completion date | Criterion |
|---------|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------| 
| 1       | Have a meeting with my client Daimei | We talked a bit about making a music streaming service and as we discussed the details further it ended up being a quite long meeting | 3 h | June 14 | A
| 2       | Write the Problem Defenition | We wrote the problem definition to have a clear understanding of what the client needs | 20 min | June 16 | A
| 3       | Understand how streaming services work and how I will be able to emulate one | I researched about basic workflow of a music streaming service by watching videos | 40 min | June 20 | A
| 4       | Research the possible ways to make a music streaming website on Flask | Since I was not knowledgeable about how I would be able to make a streaming service using Flask and Python I had to do a long research to find a way to create it. | 1 hour 35 min | June 20 | A
| 5       | Write a Proposed Solution | After my client and I clarified the issues so I decided to create a solution and this time I wasn't able to meet with the client | 30 min | June 20 | A
| 6       | Write a Design Statement | I decided to create a design statement as well to have a clear vision of what I will be creating | 30 min | June 20 | A
| 7       | Make the 6 Success Criteria | I came up with the 6 success criteria to have a clear goal for the finished product that I could check off when completed, but this might be subject to change | 45 min | June 20 | A
| 8       | Make the title artwork for GitHub | I decided to make the title artwork and used AI art generation software, and I edited in some more details including the logo TUNECORE | 60 min | June 20 | A
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      |  |  |  |  |
| ??      | Make the presentation | We made a presentation for the video required as a criteria | 20 min | Dec 13 | D
| ??      | Record the video | We did some rehearsals and recorded the video and uploaded it on Google Drive | 20 min | Dec 13 | D
| ??      | Making the poster | We made the poster with some of the data we collected and our process of the project and uploaded it on GitHub | 40 min | Dec 13 | D
| ??      | Finalize the GitHub | We went through all of the criteria in GitHub and added some things that we missed | 30 min | Dec 13 | D
| ??      | Send an email to Dr Ruben | Sent email with the link to our unit 2 project repository for grading | 5 min | Dec 13 | A

## Test Plan

