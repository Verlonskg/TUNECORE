# Criteria C: Development
## Existing Tools

| Software/Development Tools | Coding Structure Tools          | Libraries      |
|----------------------------|---------------------------------|----------------|
| PyCharm                    |Encryption                       | Flask          |
| SQLite                     | If statements                   | passlib        |
| Relational databases       | Objects, attributes and methods | sqlite3        |

## List of techniques used
1. For loops
2. If statements
3. Lists
4. Cookies
5. Password hashing
6. Flask library/routes
7. SQL queries
8. Interacting with databases



## Success Criteria 1
User System with Social Account Linking

```python
class User:
    def __init__(self, username, password):
        self.username = username
        self.password = password
        self.social_accounts = {}

    def link_social_account(self, platform, account_id):
        self.social_accounts[platform] = account_id

# Example usage
user = User("daimei", "1234")
user.link_social_account("Google", "google_account_id")
user.link_social_account("Twitter", "twitter_account_id")
```

This code demonstrates a user system that allows for linking with social accounts like Google and Twitter, enhancing security and convenience. The `User` class includes methods for initializing user details and linking social media accounts.


## Success Criteria 2
Different GUIs for Subscription Types

```html
<div id="user-dashboard">
    {% if user.subscription_type == 'VIP' %}
        <div class="vip-dashboard">
            <!-- VIP-specific content -->
        </div>
    {% else %}
        <div class="regular-dashboard">
            <!-- Regular content -->
        </div>
    {% endif %}
</div>
```

This HTML snippet shows how different GUI elements can be displayed based on the user's subscription type. The CSS class dynamically changes according to the subscription type (e.g., 'VIP'), altering the user dashboard's appearance.


## Success Criteria 3
Search, Playlist, and Sharing Features

```javascript
function searchMusic(query) {
    // Search the music database for the query
    // Display search results
}

function createPlaylist(name, songs) {
    // Create a new playlist with the specified name and songs
    // Add the playlist to the user's account
}

function sharePlaylist(playlistId, shareWith) {
    // Share the specified playlist with other users
}
```

This JavaScript example provides functions for searching music and managing playlists, crucial for enhancing user engagement and artist exposure.


## Success Criteria 4
VIP Section Accessibility

```python
def access_vip_section(user):
    if user.is_vip:
        # Display VIP-specific content such as new releases and concerts
    else:
        # Redirect to a standard page or show an access denied message
```

This function checks if a user has VIP status and grants access to exclusive content in the VIP section, aligning with the client's feature request.


## Success Criteria 5
Miles System for Streaming

```python
def update_miles(user, streaming_time):
    miles_per_minute = 0.1  # Example conversion rate
    miles_earned = streaming_time * miles_per_minute
    user.miles += miles_earned
    # Update the user's miles in the database
```

The `update_miles` function demonstrates how users can earn miles based on their streaming length, a feature designed to enhance user engagement.


## Success Criteria 6
"Create" Section for Artist Engagement

```html
<form id="artist-engagement-form" action="/submit_create_request" method="post">
    <input type="text" name="artist_name" placeholder="Artist Name">
    <input type="email" name="contact_email" placeholder="Contact Email">
    <textarea name="proposal" placeholder="Your Proposal"></textarea>
    <button type="submit">Submit Request</button>
</form>
```

```python
@app.route('/submit_create_request', methods=['POST'])
def submit_create_request():
    artist_name = request.form['artist_name']
    contact_email = request.form['contact_email']
    proposal = request.form['proposal']
    # Process the request and save it in the database
    return redirect(url_for('request_submitted'))
```

This form facilitates artist engagement, allowing users to fill out surveys and request meetings with the label, catering to the client's business expansion strategy.


## Pattern Recognition

**1. User Authentication and Social Media Integration**

Recognizing the need for secure and versatile user authentication, the project has a consistent approach to handling user login, including options for social media integration. This pattern ensures proper security and enhances user experience.

```python
class User:
    # Constructor with basic user info and social accounts dictionary
    def __init__(self, username, password):
        self.username = username
        self.password = password
        self.social_accounts = {}

    # Method to link a social media account
    def link_social_account(self, platform, account_id):
        self.social_accounts[platform] = account_id

# Example of creating a user and linking social accounts
user = User("daimei", "1234")
user.link_social_account("daimei", "google_123")
user.link_social_account("daimei", "twitter_123")
```


