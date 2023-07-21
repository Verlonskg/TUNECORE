# Computer Science IA - TUNECORE a music streaming platform
This is a music streaming site that allows people to listen to indie artists and choose genres and countries to your liking.

![TUNECORE.png](TUNECORE.png)
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
| 1       | Write the Problem context          | We identified what kind of problem the client could have and how that is affecting his daily routine             | 10min | Nov 22 | A
| 2       | Write the Problem Defenition  | We wrote the problem defenition to have a clear understanding of what the client needs | 20min | Nov 22 | A
| 3       | Create a bill of materials  | We identified all the materials we need for the project and made a list | 20 min | Nov 22 | A
| 4       | Understand how Raspberry Pi work  | We reaserched about raspberry pi to have a deeper understanding of how the servers and SSH works | 40 min | Nov 24 | A
| 5       | Reaserch how DHT11 sensor work  | We got a basic understanding of how the breadboard and DHT11 sensor works, we also learnt how to connect them together | 30 min | Nov 24 | A
| 6       | Signing Scope of Work  | We got all the materials from Dr. Ruben that we listed up, and signed the Scope of work document | 5 min | Nov 25 | A
| 7       | Create a circuit that connects from Raspberry Pi to breadboard | We made a circuit to test run and check if the whole thing works by transmitting power, it tool multiple tries to get it right | 40 min | Nov 27 | B
| 8       | Create a CSV file for the sensors | We made a CSV file to store all the data that we collected | 20 min | Nov 30 | C
| 9       | Put all the data into a list format | We put all the data into a new file in a list format to have a better view of all the data | 30 min | Nov 30 | C
| 10      | Add timelines to our CSV files | We added a timestamp of when the data was collected to have a better understanding of the information we collect | 30 min | Nov 31 | C
| 11      | Make the graphs | We made the graphs to show the data that we collected easier and test if the room is suitable for violins | 60 min | Dec 4 | C
| 12      | Create all the graphs in criteria | We made the graphs that are required to complete the project using matplotlib. We had to make graphs that show the mean, standard deviation, minimum, maximum, and median for both remote and indoor sensors | 160 min | Dec 6 | C
| 13      | Make the non-linear graph model | We made the non-linear model for all of the graphs so that our customer will have a clear understanding of the pattern of the data | 60 min | Dec 6 | C
| 14      | Create the predictions | We made the predictions of what will happen in the next 12 hours based on the data we collected for 2 days | 60 min | Dec 8 | C
| 15      | Making the system diagram | We made the system diagram to see all the materials we used | 30 min | Dec 10 | C
| 16      | Update GitHub | We uploaded all of our work to GitHub that we completed until this point | 45 min | Dec 10 | B
| 17      | Make a user in the server | We made a user in the remote server | 50 min | Dec 12 | C
| 18      | Get the access token | We got the access token after we made the user to login and post the data | 10 min | Dec 12 | C
| 19      | Post the data to the server | We posted all of our readings to the remote server but we did it after we collected all the readings | 30 min | Dec 12 | C
| 20      | Reacerch about the correlation of temperature and violins | We researched more about the affect of temperature on violins and the favourable temperatures and humidity for the violin | 20 min | Dec 13 | D
| 21      | Make the presentation | We madew a presentation for the video required as a criteria | 20 min | Dec 13 | D
| 22      | Record the video | We did some rehearsals and recorded the video and uploaded it on google drive | 20 min | Dec 13 | D
| 23      | Making the poster | We made the poster with some of the data we collected and our process of the project and up loaded it on GitHub | 40 min | Dec 13 | D
| 24      | Finalize the GitHub | We went through all of the criteria in GitHub and added some tings that we missed | 30 min | Dec 13 | D
| 25      | Send a email to Dr Ruben | Sent email with the link to our unit 2 project repository for grading | 5 min | Dec 13 | A

## Test Plan

