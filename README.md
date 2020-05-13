## What's this?
A collection of common myths and facts (opinionated) about computer programming that I wish I knew in my early career.

## How to contribute?
- Submit a pull request with new Q/A and updates

---


### Programing requires math

- Neutral.
- Only a few percentage of programmer deal with math problem in their career. 
- Analytical skills helps to break down the problem. Think of programming as understanding the problem, breaking down into smaller chunks and actually solving it. Similar to math right?    
- However, people who are bad at Math can be a good programmer. It also depends on the type of their role and type of problem they are trying to solve.

### Programming job is similar to typist. It's all about typing code.
- False
- Programming(at entry level) is about: 
    - reading documentation and requirements
    - documenting stuffs
    - thinking how to write code
    - writing code
    - testing
    - debugging bugs
    - deploying
    - discuss with team member/management

- The amount of time you spend typing code depends on your role and job description. There will be days you won't be typing any code. 
- Majority of programming job requires maintaining an existing system written over years by several people. You will be required to add features, customize, fix bugs etc

### You won't require a college degree to be a programmer
### Everyone can learn and be a programmer within months
### Programming is really hard
- Neutral.
- It depends on the individual, their learning/intellectual capability and type of programming role they learn/get into.
- There will be certain things you can learn easily. But a college degree will definitely help to broaden your perspective and learn things quickly.     


### Is monotonous  ... like working in assembly line at a factory
- False
- In certain days or working in same role for a long time, you may get a feel of your job being monotonous.
- But it's not like working in assembly line. It requires lots of thinking and analysis.

### Programming is not for girls
- False

### You need to keep reading new stuff throughout your career
- Neutral
- You don't "need to". But learning new stuff helps advance your career.
- Also, it depends on type of tool and technologies your are using. Some tools/technology (eg: JS Frameworks) get deprecated every few years. Sometimes 
- Learning a new paradigm, best practices, new architecture concepts is always useful.

### Machine Learning and AI seems easy to learn.
### I don't have any knowledge of statistics/probability/modeling. However, the ML/AI tutorial I found online is just 10 line of code and it seems easy.  
- False
- It may seem easy to use ML/AI tools created by somebody else or follow a cookbook. But you will need to understand a great deal of concepts to be actually use those tools when solving real problems. 
Don't get intimidated by simple tutorials. Start by the basics and dig into the tools.

### Using long variable makes program slow. So I should program like this:

```
int a = read()
int b = 1000
if(a > 18 && b > 50)
    println("Entry allowed")


```
- It depends

 - With compiled languages, no. With interpreted languages, possibly but the difference would be negligible.

 - Always focus on readability. Compare the above code with the following:


```
int age = readMemberAge()
int balance = 1000
if(age > 18 && balance > 50)
    println("Entry allowed")

```

### I have to learn as many programming languages eg C, Python, Java, Ruby, Kotlin, Scala, Groovy, C#, Go to be a good programmer.
 - False
 - Think of programming language as natural language eg: Nepali, French, English, Japanese and Chinese. 
 And the art of writing a novel or poem as the actual programming.
 If you mastered five langauges but do not have a skill of writing a (good) poem in either of those you are still not an artist.
-  Think of programming as art. Try to be artist in at least one language. Think of a hobby project and develop with paying attention to code quality, performance, UI, features etc.
- Focus on learning programming rather than learning a language.
    - Programming is a skill that you can gain with just one language. If you know how to do X in Y language then you can do it in Z language too with little effort.


### HackerRank, LeetCode will guarantee me a job 
- False
- There's no doubt that the questions on those site help you think critically and solve a problem.
- Key to land a first job is pet project(s)

### Google, Amazon and Facebook are using X tool. It must be good so I should learn.
- False
- Lot of tools developed by tech-giants are being deprecated after couple of years.
- Looks for a tool/language/framework that's being used by a lot of companies for a long time. 

### X was developed by Google, Amazon and Facebook so it must be good. I should learn and use it.
- False
- There's no guarantee that those tools MUST be good. Don't fall for advertisements
- Review 100 job descriptions on Linkedin/Indeed etc and find yourself what's populat on the market

### I must learn Angular, React, Vue and XYZ web framework to master my web development skills
- False
- Its better to start the web development without the frameworks so that you understand how those frameworks are solving the problems of not using those framework
- You don't need to learn all of these, one would be enough. If you started learning the web development without using frameworks, switching between framework would be easier.
    

### Everyone on social media hate language/framework X. X must be bad.
- False
- Don't fall for people's 'opinions'. People think languages/frameworks/tools as religion. They hate each other.
- Best way to find out what to learn is look at job vacancies. At least a hundred of them.

### Language X does that in one line. So, it is the best language.
- Neutral
```
 DB.allRecords().read().toCsv("file.csv");
```

- Its nice that they provided that functionality in one line out of box. But there is a great deal of code hidden behind the scene.
- All languages support creating library modules to extend the feature. Some languaes are by nature too abstract/low level and it requires developers to write libraries around it to make things simpler.
- So, that doesn't mean langauge X is best.
- 


### I use print statements to debug. I think that's enough to debug an app.
- False
- Use debugger tools provided by your IDE instead of print statements to print everything.




### Everyone hates types. I don't think there's a reason to specify type for each and every variable.
```
//Static Typing
int a = 10 // a is integer, we can't assign string to it
a = "ABC"  // compiler prevents this 

 
//Dynamic Typing
a = 10
a = "ABC"  // `a` can be anything. Compiler won't complain. We might get runtime errors. We need to write unnecessary unit tests just to detect such assignments. Also there's a performance penalty.
```

- Neutral
- It's a choice based on your language. The pros and cons depends on type and purpose of application
- For big apps having type adds lots of value.
- For scripts its okay to not have types.


### I can write CRUD app in five different framework and language. I must be a good programmer.
- False
- Go beyond the CRUD. See  ['Guessing Game - Full Scope Developer'](full-scope-developer.md)  

### I understand all the concepts of langauge X and Y  (or framework A and B). I think that's enough to learn those languages/frameworks. 
- False
- Knowing the language/framework and being able to use it to develop is different. See  ['Guessing Game - Full Scope Developer'](full-scope-developer.md)  

---

## TODO:

- Provide an example of 'Guessing Game - Full Scope Developer' with one 'stack' 
- More Q/A
- Add hints/more steps on 'Guessing Game'