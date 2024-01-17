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



# Criteria C: Development
## Existing Tools

| Software/Development Tools | Coding Structure Tools          | Libraries      |
|----------------------------|---------------------------------|----------------|
| PyCharm                    |Encryption                       | Flask          |
| Relational databases       | Objects, attributes and methods | sqlite3        |
| SQLite                     | If statements                   | passlib        |
| Python                     |                                 | Datetime       |
| Chat GPT                   |                                 | werkzeug.utils | 

## List of techniques used
1. Flask library/routes
2. For loops
3. If statements
4. Password hashing
5. Interacting with databases
6. Lists
7. Cookies
8. SQL queries



## Success Criteria 1 and 5
The first criterion was to have an inventory list of all the equipment that the tech crew has
```.py
if request.cookies.get('user_id'):
        user_id = request.cookies.get('user_id')
        db = database_worker("tech_web.db")
```
With the above code, I created an algorithm for the user so that they can upload new posts to the tech crew site. First, I make sure to validate the user as in all the other pages needs to be logged in to be able to access it preventing unauthorized access.
```.py
            if len(name) > 0 and len(amount) > 0 and len(notes)>0:
                new_inventory = f"INSERT into equipment (naame, location, amount, notes, user_id) values('{name}','{location}','{amount}', '{notes}', {user_id})"
                print(new_inventory)
                db.run_save(query=new_inventory)
                inventory = db.search("Select * FROM equipment")
                return redirect(url_for('inventory', inventory = inventory ))
            else:
                msg = "Please complete all fields"
                return render_template("new_inventory.html", message=msg)
        return render_template("new_inventory.html")

```
After getting user information, it is validated, and I use the database worker function to insert it into the inventory. If the values are not valid, the user is redirected and asked to fill out the form again. Then the user was redirected to the inventory page. 

```.py
inventory = db.search("Select * FROM equipment")
                return redirect(url_for('inventory', inventory = inventory ))

```

When the user was redirected to the inventory, I had to search the database again by using the database_worker function, then using the return redirect(url_for  ) tool to redirect them to the inventory that would display all of the equipment including the new one. 
```.py
        db = database_worker("tech_web.db")
        inventory = db.search("Select * FROM equipment")

```
Using the database worker function enables me to simplify my code as I need to connect to the database throughout the application. Additionally, this enables future developers to have an easier time of expanding my application as they can reuse this vital piece of code. 




## Success Criteria 2
Login and Registration page

```.py
@app.route('/signup', methods=["GET","POST"])
def signup():
    msg = ""
    if request.method == "POST":
```
For the signup page, I follow the same process as the new_posts page, checking if the method is posted to make sure that the user is trying to signup. 

```.py
        username = request.form['username']
        passwd=request.form['passwd']
        passwdconfirm=request.form['confirmpasswd'] #Get the information from the UI
        tech_web = request.form['tech_question']
```
Then I get the information from the UI

```.py
        if tech_web == "Smiley face emoji":
            if passwd==passwdconfirm:
                hash = encrpyt_password(passwd) #Encrypt the password for better security
                db = database_worker("tech_web.db")
                new_post = f"INSERT into users (username,password) values('{username}','{hash}')"  #Save in the database to call back later
                db.run_save(query=new_post)
                return redirect(url_for('login'))
            else:
                msg = "Passwords do not match"
        else:
            msg = "You are not a tech crew member and cannot create an account"
            return render_template("signup.html", message=msg)
    return render_template("signup.html", message=msg)

```
The passwords are checked and if they don't match, it displays an error code and the user has to reinput it. Additionally, I have added a tech crew question which enables the site to be restricted to only tech crew members. If the passwords match then I first hash the password to make it more secure, to do this I call on a function that I imported from my library called encrypt password. Then I used the database_worker class to insert the information into the users page in the social_net database and redirect them to my login page. 

```.py
@app.route('/login', methods=["GET","POST"])
def login():
    msg = ""
    if request.method == "POST":
        username = request.form['username']
        passwd=request.form['passwd']
        db = database_worker("tech_web.db")
        user = db.search(f"Select * from users where username = '{username}'") #Check the user in the database
```
For the login, in addition to checking the method and However, to check that the username is correct I use the database_worker function to see if the user does exist

```.py
        if user:
            user = user[0] #because search function returns a list
            id, email_db, hashed = user
            if check_password(hashed_password=hashed, user_password=passwd): #Call function from my_lib to check password
                db = database_worker("tech_web.db")
                posts = db.search("Select * FROM posts")
                response = make_response(redirect('home'))
                response.set_cookie('user_id', f"{id}")#Set cookie for functions later in the website
                return response
            else: msg = "Please enter the correct password"
        else:
            msg = "user does not exist"
    return render_template("login.html", message=msg)

```
If it does, I get the information from that row and then use the check_password function imported from my library to check if the passwords are correct. If everything is good, I first set the cookie for the user so that I am able to use that later. Then I redirect it to the home page by getting all the posts from the post page in the database, then redirecting to the home page. 

## Success Criteria 3
Tech request form

```.py
@app.route('/', methods=["GET","POST"])
def home():
    msg = ""
    if request.method == "POST":
        location = request.form('location')
        date = request.form('date')
        time = request.form('time')
        equipment = request.form('Equipment')
        contact_name = request.form('Name of Contact')
        contact_email = request.form('Contact person email')
```
For the form, I made it the home page with the route '/' as it would enable the general public to access it without having to go through a signup or login process. Like the posts and the signups, I followed the same process, checking the method, and then getting the information from the form.

```.py
        if len(location) > 0 and len(date) > 0 and len(time) > 0 and len(equipment) > 0 and len(contact_name) > 0 and len(contact_email) > 0:
            if check_email(contact_email):
                db = database_worker("tech_web.db")
                db.run_save(f"INSERT INTO event (location, date, time, equipment, contact_name, contact_email) VALUES ('{location}', '{date}', '{time}', '{equipment}', '{contact_name}', '{contact_email}')")
                msg = "Event added"
        else:
            msg = "Please fill in all fields"

    return render_template("home.html", message=msg)
```
Then I validated the inputs and used the database worker function to enable me to enter them into the database. Lastly, I made sure to put a message so that people would know that their request was submitted or if the request was invalid. 


## Success Criteria 4

```.py

@app.route('/calendar', methods=['GET','POST'])
def calendar():
    if request.cookies.get('user_id'):
        user_id = request.cookies.get('user_id')
        db = database_worker("tech_web.db")
```
This enables the events that people request tech support from to be displayed on the calendar page for tech crew users. I first make sure that the user is logged in, then I get the user_id and connect to the database.

```.py
        events = db.search("Select * FROM event order by date asc")
        current_events = []
        for i in events:
            date1 = i[2]
            date_object = datetime.strptime(date1, '%Y-%m-%d').date()
```
 First, to make sure that the events are in order, I make sure to use the "order by date asc" SQL query. Then, I initiated an empty list to hold future events. I go through every event from the database in a for loop and I get the date and then strip it using the datetime function to make sure it is in the correct format.

 ```.py
            date2 = date.today()
            if date_object>=date2:
                current_events.append(i)
            else:
                item_id = i[0]
                db.run_save(f"DELETE FROM event WHERE id = {item_id}")
                db.close()
        return render_template("calendar.html", events=current_events, user_id = user_id)
    else:
        return redirect('login')


```
I then get the current date and compare them to see if the event has already passed. If it hasn't passed, I append it to the current_event list. If it did, I get the ID and then delete the event from the database. At the end, I make sure to return the calendar page.
Deleting the events that had passed was the most problematic as I had to first get the date of each event, and then I had to find the right function from the DateTime library to format it correctly. Then I had to get the current date so that I could compare. This enabled me to fulfil success criteria number 4



## Pattern recognition

```.py
from my_lib import database_worker, encrpyt_password, check_password
```
I made this to simplify my code. When saving something to the database, I can just call the function instead of writing the code all out every single time. Additionally, if I need to change something I only have one point to change. This is an example of the computational thinking skill pattern recognition as I was able to see that this is something that is repeated throughout. Additionally, it also shows algorithm design as I used an algorithm that enabled me to do the same things many times. 


## User validation

```.py
if request.cookies.get('user_id'):
```
For each web route, I made sure to request the cookies from the user. This made sure that the user was already logged in and had a cookie. This means that even if someone knows the URL of the website and they input the URL into their search bar, they are not able to access it. This increases the security of the whole website as people need to have had accounts made and have to log in as normal.
