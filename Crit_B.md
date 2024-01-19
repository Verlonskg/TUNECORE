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



## Test Plan

| Instruction | Category | Input Example / Code | Description | Expected Output | Success Criteria |
|-------------|----------|----------------------|-------------|-----------------|------------------|
| Test the streaming feature | Unit testing | Song: "TestSong.mp3" | The user selects a song to stream from the music library | The song streams without interruption, and playback controls are responsive | 3 |
| Test the search function | Unit testing | Query: "TestBand" | The user searches for a band or song using the search feature | The search returns relevant results from the music database | 3 |
| Test the playlist creation | Unit testing | Playlist name: "TestPlaylist", Songs: "Song1, Song2" | The user creates a new playlist and adds selected songs to it | The new playlist is created with the chosen songs and is accessible | 3 |
| Test account creation with invalid email | Unit testing | Email: "test@invalid", Password: "12345" | The user attempts to create an account with an invalid email address | An error message indicates the email is not valid | 1 |
| Test the volume control | Unit testing | Volume level: 50% | The user adjusts the volume control on the music player | The volume changes according to the user's adjustment | 3 |
| Test the user settings update | Integration testing | New username: "Daimei2" | The user changes their username in the settings | The username is updated in the user's profile and database | 1 |
| Test password reset | Integration testing | User: "Daimei", Old password: "1234", New password: "abcd" | The user requests a password reset and sets a new password | The user's password is updated, and they can log in with the new password | 1, 2 |
| Test the responsiveness of the UI | Usability testing | Various screen sizes | The website is accessed from devices with different screen sizes | The UI is responsive and maintains usability across devices | 2 |
| Test the music library loading time | Performance testing | None | The user accesses the music library | The music library loads within a reasonable time, with all elements displayed correctly | 3 |
| Test the favorite system | Unit testing | Song: "TestSong.mp3" | The user marks a song as a favorite | The song is added to the user's list of favorites and is easily accessible | 3 |
| Test multi-device login | Security testing | Username: "Daimei", Password: "1234" | The user attempts to log in from two different devices simultaneously | The system allows or restricts simultaneous logins based on security policy | 1 |



