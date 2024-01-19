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


