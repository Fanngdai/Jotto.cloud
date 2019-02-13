# Jotto - ONLY ONE SUBMISSION

### Technologies
* Spring Boot 2.1
* Java 11
* Intellij IDEA 
* MongoDB -- Spring Data MongoDB
* Can we use Angular

### Build and run instructions
* To build and run project through Maven
From Jotto Server directory run:
```
mvn spring-boot :run
```
* To run Mongodb database
```
mongod --dbpath localuserpathtoJottodir/Jotto/data/db
```
* To open an instance of mongo shell (while db is open)
```
mongo
```
### Rules of Jotto
* number of letter (5 letters, no repeating letters)
* Array of 26 (alphabets) which is displayed on the web
* These letters can be toggled by the user to change color (black, red, & green)
* Each time the user guesses the a word, you tell them how many of those also appear in your word (which they are guessing)

* Give the game a dictionary so that user cannot enter random words (optional)
https://www2.cs.duke.edu/courses/spring06/cps100/assign/jotto/code/kwords5.txt

* Play new game
* Show previous game
* Pc should be able to win. Randomly.

### Pages
* Home Page - Registration & Login
* Game play
* See previous plays (list) clickable
* See previous plays
* About (optional)

### Database
* Each user needs an account - username & password
* Database for words?
* Database for the past game results - the words and process
* Database files stored in /data

https://www2.cs.duke.edu/courses/spring06/cps100/assign/jotto/

