This is my server to my streaming app. It handles all the routing stuff. My streaming app allows you to create an account to make playlists or sign in as a guest (but you won't be able to create playlists). When you first sign in you will be taken to the homepage that has 8 cartoons on it you can select any of those 8 cartoond and be taken to the first episode from that cartoon. Or you can select the "Cartoons List ->" button on the top right and see a whole list of cartoons from A-Z. When you are on the cartoons page the video player is the first thing you see if you scroll down, You will see a "add to playlist" where you can add that video to a selected playlist or create a new one.

PLANNING STRATEGY:<br>
To plan for this the first thing I did was come up with an ERD.<br>

<img src="./README images/ERD.png"></img><br>

after that I got to work on creating the playlist schema and the playlist routes. After that was done I started working on the front-end.<br>


API:<br>
| Action | Verb   | URI Path               |
|--------|--------|------------------------|
| Sign-Up | POST   | `/sign-up`             |
| Sign-In | POST   | `/sign-in`             |
| Sign-Out | DELETE | `/sign-out`            |
| Change Password | PATCH  | `/change-password`   |
| Show All Playlists | GET    | `/playlists`             |
| Create A Playlist | POST   | `/playlists`             |
| Delete A Playlist | DELETE | `/playlists`            |
| Update A Playlist | PATCH  | `/playlists`     |

set-up and install istructions:<br>
  npm install<br>

List of technologies:<br>
  HEROKU<br>
  MONGODB<br>
  JAVASCRIPT<br>

Links:<br>
  Front-end repo: https://github.com/gitlep1/streaming-client <br>

  Live Client: https://gitlep1.github.io/streaming-client/#/ <br>

  Live Server: https://cartoonstreaming-server.herokuapp.com/ <br>

unsolved issues:<br>
  nothing