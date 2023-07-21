# Computer Science IA - TUNECORE a music streaming platform
This is a music streaming site that allows people to listen to indie artists and choose genres and countries to your liking.

![TUNECORE](https://github.com/Verlonskg/TUNECORE/assets/111814707/89ac97a9-9fdc-4fea-821a-e5b5dfcd0d70)
**Fig.1**

# Criteria A: Planning

## Problem Definition
The client is a owner of a private record label he is willing to make a music streaming platform that only features the songs from the artists that are signed with his label and to have a exclucive access to unrealesed ablums or early access to live event tickets or merch with an monthly subsctiption of a VIP membership. He think that it will help grow the customers and people who will have interest in the music that are produced from his label. And He is also showing interest to recruit many more artists to expand his buisness and hopefuly merginalize his profits. He says he wants a whole different style to the service for the VIP members since he wants to increase the customers who will be willing to pay for the vip membership. He is thinking of there could be visible differences in the graphical user interface it will be more effective then only having a early access feature. He says he will be naming the company TUNECORE and it will hopefully revolutionalize how the music service industry works right now.

## Proposed Solution
Baised on the client's request I will be developing a web browser baised music streaming platform with two option for the subscription. This platform will have a similar feature as all of the other streming platforms for the basic feature so there will be a user registration system where the customers can sign up to the service and make an account where they can use either email or phone number and set a password for extra security. They will also be a feature where they can link an account to make the account using other services such as google or twitter. Once you have an acound you can search for artist, songs and also make playlists just like a normal music streaming platform. 

Since the client is willing to only feature the artist from his record label with unrelesed ablums, there will be a subsctiption for regular customers. 

## Design statement

I wil develop a music streaming platform, and there will be two distinctively different sections that will be slpit for the regular subsctibed customers and VIP subscribed customers. The regular one will have a while baised UI with only the basic functions and there is no access to the VIP page where you can preview uncoming events, merch, and songs exclusively.There you also get discounts for live event tickets and more.

## Success Criteria

| No. | Success critieria	         | Issue tackled       |
|----------------------------|---------------------------------|----------------|
| 1 | The platform has a User system with a password and ability to link with the other social accounts such as google and twitter. | The client wanted a secure system since the service has two options of subscription | 
| 2 | The platform has different GUIs for different subscription types. | The client wanted a more attractive GUI for the VIP users to increase the VIP subscription | 
| 3 | The platform allows users to search up songs and artists, also make a playlist which you can also share with people. | This finction increases users udability and the also increase the artists stream amaount | 
| 4 | The platform has a VIP section which is only accesible to the VIP users and it shows the new release of ablums and merch, also the live concert information.  | This was a feature that was requested from the client | 
| 5 | The platform has a miles system where you get a certain amout of miles for every streaming length you reach.  | This was also a function tht was requested to add by the client | 
| 6 | The platform has a section called "create" where you can fill out a survey and request to book a meeting with the client to discuss about signing a contract with the label. | Since the client was saying that he wanted to expand his buisness buy accepting more underground artists this was a function created accordingly for his issue | 

# Criteria B: Design

## System Diagram **HL**
![](System_Diagram.jpg)

**Fig.2** shows the system diagram for the proposed solution, I used pycharm and flask to develop the website.
## Data Transmission

We have collected the data of the humidity and temprature from the sensors and write it into the csv file that we have created. And from that file we made a program that reads each line from the csv file and sends those data to the server in the json format using while loop.

![CSV.png](csv_file1.png)

**Fig.3** Above is the csv file that we used to store the data.

## Record of Tasks
| Task No | Planned Action                                                | Planned Outcome                                                                                                 | Time estimate | Target completion date | Criterion |
|---------|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------| 
| 1       | Have a meeting with my client Daimei | We talked a bit about making a music streaming service and as we discussed the details further it ended up to be a quite long meeting | 3 h | June 14 | A
| 2       | Write the Problem Defenition | We wrote the problem defenition to have a clear understanding of what the client needs | 20 min | Jine 16 | A
| 3       | Understand how streamig services work and how I will be able to emulate one | I reaserched about basic work flow of a music streaming service by watching videos | 40 min | June 20 | A
| 4       | Reaserch the possible ways to make a music streaming website on flask | Since I was not knowledgable about how I will be able to make a streaming service using flask and python I was to have a long reaserch finding a way to create it. | 1 hour 35 min | June 20 | A
| 5       | Write a Proposed Solution | After my client and I clarified the issues so I decided to create a solution and this time I wasnt able to meet with the client | 30 min | June 20 | A
| 6       | Write a Design Staement | I decided to create a design statement as well to have a clear vision of what I will be createing | 30 min | June 20 | A
| 7       | Make the 6 Success Criterias | I came up with the 6 success criteria to have a clear goal for the finished product that I could check it off when completed, but this might be subject to change | 45 min | June 20 | A
| 8       | Make the title artwork for the github | I decided to make the title artwork and used AI art generation software, and I edited in some more details including the logo TUNECORE | 60 min | June 20 | A
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
| ??      | Make the presentation | We madew a presentation for the video required as a criteria | 20 min | Dec 13 | D
| ??      | Record the video | We did some rehearsals and recorded the video and uploaded it on google drive | 20 min | Dec 13 | D
| ??      | Making the poster | We made the poster with some of the data we collected and our process of the project and up loaded it on GitHub | 40 min | Dec 13 | D
| ??      | Finalize the GitHub | We went through all of the criteria in GitHub and added some tings that we missed | 30 min | Dec 13 | D
| ??      | Send a email to Dr Ruben | Sent email with the link to our unit 2 project repository for grading | 5 min | Dec 13 | A

## Test Plan

