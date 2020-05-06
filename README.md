# What's this?

A collection of common myths and facts about computer programming that I wish I knew in my early career.


# Using long variable makes program slow. So I should program like this:
 - False

eg: Following two would execute in same time. Second example is best.

```
int a = readInt()
int b = 1000;
if(a > 18 && b > 50){
    println("Entry allowed")
}

```


```
int age = readInt()
int balance = 1000;
if(age > 18 && balance > 50){
    println("Entry allowed")
}
```




# I have to learn as many programming languages eg C, Python, Java, Ruby, Kotlin, Scala, Groovy, C#, Go to be a good programmer.
 - False
 - Think of programming language as natural language eg: Nepali, French, English, Japanese and Chinese. 
 And art of writing a novel or poem as the actual programming.
 If you mastered five langauges but do not have a skill of writing a (good) poem in either of those you are better 

It's really stupid to learn 15 languages. No one should learn 15 language because they will never need it and most importantly.. just because you know N number of language doesn't make you fit for the job.

These are the popular options for a full stack developer. And they will be on the job market for another couple decades.

    Backend: Java (with a framework like Spring
    Database: MySQL
    Client: HTML and JavaScript with little CSS. Don't bother to learn a client side framework if you are a newbie.
    
    
    Stop! Don't learn any new language. Rather try to be perfect on above listed languages.

Focus on learning programming rather than learning a language.

Programming is a skill that you can gain with just one language. If you know how to do X in Y language then you can do it in Z language too with little effort.

Think of an hobby project .. it could be anything. You can create a web app like Quora, Twitter if you run out of idea. And develop with paying attention to code quality, performance, UI, features etc.


# HackerRank, LeetCode will guarantee me a job 

# Google, Amazon and Facebook are using X tool. It must be good so I should learn.

# X was developed by Google, Amazon and Facebook so it must be good. I should learn and use it.


# I must learn Angular, React and Vue and XYZ to master my UI skills
    - start without frameworks
    - learn one of them.. 
    
# I can write CRUD app in five different framework and language. I must be a good programmer.


# Everyone on social media hate language/framework X. X must be bad.

# Language X does that in one line. So, it is the best language.

 DB.allRecords().read().toCsv("file.csv");

Its nice that they provided that functionality in one line out of box. But there is a great deal of code hidden behind the scene.
All languages support creating library to do the same. So, that doesn't mean langauge X is best.


# Everyone hates types. I think they must be right.

int a = 10
--
a = 10
a = "ABC"


- its a choice.
- big program = type is best
- script (less than 100 line) - no worry


# What to program?


1)Console App:
Read a number N from console between a range ( MIN , MAX). Your code should then generate a random number CN between the same range and compare if the computer generated random number CN and the user entered number N matches.

If it matches, user wins.

2) Desktop app:
Create a Interface with JavaFX to enter the MIN/ MAX number and the user guess.

MIN : [ Textbox  ]
MAX: [ Textbox ]
User Guess   [  Text Box  ]

Also provide a button with label "Play" that generates the random number and displays a message in Label if user won.
                [ Play  ]

3) Two player:
Update the GUI application to allow two user to play with computer. The both of of the user can enter their guess and click Play. The user that made the correct guess will win

User A's Guess   [  Text Box  ]

User B's Guess   [  Text Box  ]

4) Multi-Player Game - over socket connection
Update the GUI application to allow a number of users to to play simultaneously. All the user will have the copy of application and can join the Game by running the application on their computer.

The first user to start the game can act as Server.

Database:
5) Require user/password to join the game. So that only the user who knows the password can join

6) Don't allow the user who has been playing for more than 1 hour. Lock them for 2 hour.

8) Log events like who won the most, the winning numbers.. looser numbers

9) Generate a report with stats about the winner, numbers etc


Web Application:

10) Create a web application to play the same game in browser

11) Setup a public web api to expose information about the winners


...

111) Use Machine Learning to do X Y X

---

Focus on readability, reusability 


 