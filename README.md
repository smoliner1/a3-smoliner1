## a3-smoliner1

https://a3-smoliner1.glitch.me/

This project takes the program from a2 a step further, while still being an Arcade Scoreboard website, but now including the use of a database for data storage, as well as a login page and the use of nes.css.
There were several times where I got stuck, but I managed to figure it out within the same day most of the time. There were a few things that took longer, and ended up being very minor and simple fixes.
Authentication simply checks the database for matching credentials to what was entered. If a match exists, it logs in with those credentials. If not, it creates an account with those credentials if the given username doesn't already exist (if it does, it will simply fail to login and you will need to try again). I went with this because it's both easy and relatively user-friendly.
I used nes.css because it fits with the Arcade theme.

## Technical Achievements
- **Express Middleware Packages**: I used cookie-session, which essentially stores a cookie with the login credentials used.

### Design/Evaluation Achievements
- **Custom**: I'm just going to try and be a little cheeky here, I did manage to appropriately use nes.css of all things, and I feel like I ought to ask for 1 or 2 bonus points for working with that style of all things and still getting an acceptible accessibility score due to the limited options for colors (and I'm not making all the buttons white, that's just not appealing to anyone). Just putting that out there.
