
## Guessing Game - Full Scope Developer

If you are wondering what would be a perfect project to practice your programming skills. You are on the right place!

It's a simple number guessing game. We start with a console app and migrate to web app with lots of features.

## Steps


#### Console App:

- Read a number N from console between a range (MIN, MAX). Your code should then generate a random number CN between the same range(MIN, MAX) and compare if the computer generated random number CN and the user entered number N matches.

    If it matches, user wins. If it doesn't match, computer wins.

#### (Optional) Desktop app:

- Create an interface to enter the MIN/ MAX number and the user guess.

```
    MIN :        [ Textbox  ]
    MAX:         [ Textbox  ]
    User Guess   [ Textbox  ]
```

Also provide a button with label "Play" that generates the random number and displays a message in Label if user won.

```
    [ Play  ]
```

- Save the win/loss counts and winning/losing number in a text file 'stat.csv'. Display the average win/loss on UI when user closes the app.

```
    eg:
    DATE_TIME, WINNER, WINNING_NUM, LOSING_NUM
    2020-05-10 20:01:50, USER, 5, 10
    2020-05-10 20:02:50, USER, 3, 4
    2020-05-11 20:05:50, COMPUTER, 7, 9
```

#### Two player:
- Update the GUI or Console application to allow two user to play with computer. The both of the user can enter their guess and click Play. The user that made the correct guess will win

```
    GUI mockup:

    User A's Guess   [  Text Box  ]
    
    User B's Guess   [  Text Box  ]

                     [    PLAY    ]
```

#### (Optional) Multi-Player Game - over socket connection:
- Update the GUI application to allow a number of users to play simultaneously. All the user will have the copy of application and can join the Game by running the application on their computer. The first user to start the game can act as Server.

#### Web Application:

- Create a web application to play the same game in the browser. Reuse the previous code on backend

- Support single player mode (play with the computer). 

- Add a sign-up page to register users. Update logic to allow only the registered/logged in users to play. Use recaptcha to prevent robot making requests.

- Block user from playing more than 1 hour. Lock them for 2 hours.

- Multi-player: list online users and provide ability to request/accept to play with the user. Use websocket to listen for updates in realtime.

- Store the win/loss statistics into db. 

-  Generate a CSV report with stats about the winner, numbers etc that you can download it from web interface. 

-  Schedule the report to run every day and deliver to your email address.

-  Setup a background job that sends an account deactivation email if user is not logged-in in last 20 days

-  Setup a background job to deactivate user if user is not logged-in in last 30 days

-  Setup a public web api to expose information about the winners

-  Use caching to read user profile from the cache instead of reading from DB on every request

-  Setup a dockerfile script to run your app in docker 

-  Setup static code analysis with local sonarqube instance. You can use docker to run sonarqube. Take care of sonarqube warnings.

-  Deploy your app in a cloud environment (eg herouku, aws, azure)

-  ...


### Note: 

- Focus on readability, reusability throughout the development.
- Try to make your app modular
- Use build system
- Use git 
