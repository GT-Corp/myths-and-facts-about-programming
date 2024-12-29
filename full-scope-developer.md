
## Guessing Game - Full Scope Developer

If you are wondering what would be a perfect project to practice your programming skills. You are in the right place!

It's a simple number guessing game. We start with a console app and migrate to a web app with lots of features.

## Steps


#### Console App:

- Read a number N from the console between a range (MIN, MAX). Your code should then generate a random number CN between the same range(MIN, MAX) and compare if the computer-generated random number CN and the user entered number N matches.

    If it matches, the user wins. If it doesn't match, the computer wins.
   
- Loop/keep playing until user enters 'QUIT' for the input value

- Also validate the user input - range(MIN, MAX), non-numeric value/ non-integer value


- Save the win/loss counts and winning/losing number in a text file 'stat.csv'. 

- Display the average win/loss on UI when the user quits the app.

    Req: Scanner, Math class, conditional, loop, FileWriter, FileReader

```
    eg:
    DATE_TIME, WINNER, WINNING_NUM(computer gen random number)
    2020-05-10 20:01:50, USER, 5
    2020-05-10 20:02:50, USER, 3
    2020-05-11 20:05:50, COMPUTER, 7
```

#### (Optional) Desktop app:

- Create an interface to enter the MIN/ MAX number and the user guess.

```
    MIN :        [ Textbox  ]
    MAX:         [ Textbox  ]
    User Guess   [ Textbox  ]
```

Also provide a button with label "Play" that generates the random number and displays a message in Label if the user won.

Req: Swing: JPanel, JWindow, JButton, JTextFiel etc


```
    [ Play  ]
```


#### Two player:
- Update the GUI or Console application to allow two users to play with the computer. Both of the users can enter their guess and click Play. The user that made the correct guess will win

```
    GUI mockup:

    User A's Guess   [  Text Box  ]
    
    User B's Guess   [  Text Box  ]

                     [    PLAY    ]
```

#### (Optional) Multi-Player Game - over socket connection:
- Update the GUI application to allow several users to play simultaneously. All the users will have a copy of the application and can join the Game by running the application on their computer. The first user to start the game can act as a Server.

#### Web Application:

- Create a web application to play the same game in the browser. Reuse the previous code on the backend

    Req: Use Spring Boot / Spring Web , HTML (JSP or Thymeleaf)

- Add a sign-up page to register users. Update logic to allow only the registered/logged-in users to play. 
    
    Req: DB(Use H2), Spring Data JPA to store User info, Spring Security
 
- (Optional) Use ReCaptcha to prevent robot making requests.

- Block users from playing more than 1 hour. Lock them for 2 hours.

- (Optional) Two-player: list online users and provide the ability to request/accept to play with the user. Use WebSocket to listen for updates in realtime.

- (Optional) Make it multi-player

- Store the win/loss statistics into DB.

-  Generate a CSV report with stats about the winner, numbers, etc that you can download it from the web interface. 

    Req: https://github.com/gtiwari333/spring-boot-blog-app/blob/master/src/main/java/gt/app/web/mvc/DownloadController.java

-  Schedule the report to run every day and deliver it to your email address.

    Req: Spring `@Scheduled` 

-  Setup a background job that sends an account deactivation email if the user is not logged-in in last 20 days

-  Setup a background job to deactivate user if the user is not logged-in in the last 30 days

-  Setup a public web REST API to expose information about the winners

    Req: Spring `@RestController`

-  Use caching to read user profile from the cache instead of reading from DB on every request
    
    Req: Spring's `@Cacheable`

-  Setup a Dockerfile script to run your app in docker. Or use buildpack plugin

-  Setup static code analysis with local SonarQube instance. You can use docker to run SonarQube. Take care of SonarQube warnings.

-  Deploy your app in a cloud environment (eg Heroku, AWS, Azure, Oracle). Use free tier resources. Oracle has "always-free" tier.

- Write e2e test

- ...


### Note: 

- Focus on readability, reusability throughout the development.
- Try to make your app modular
- Use the build system eg: Maven, Gradle
- Use git
- Writ tests(unit, integration) after each step 
