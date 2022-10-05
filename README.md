# Flashcards Django Webapp
To view the live site visit:

## Tech Stack
* Django
* Heroku

## Introduction
In this project I built a simple flashcards app. This project is based on the **Leitner system** and uses **spaced repitition** to test knowledge of new and challenging concepts. The flashcards in the first box are practiced more frequently and the following boxes are practiced in larger time intervals.


## Project Overview
For the demo, I have chosen English to Spanish translations
The home page shows all of the flashcards and allows the user to either create a new card or edit existing cards.
![Homepage Image](/images/home_page.JPG)

The flash cards are divided into 5 boxes. All new flashcards are placed into the first box. To test knowledge, the user can select one of the 5 boxes. The app will randomly select a flashcard from the box and the answer is hidden.
![Box Image](/images/box.JPG)

The user then attempts to answer the question. If the answer is correct the flashcard moves from one box to the next (i.e. box 3 to box 4), if the ansewer is incorrect the flashcard moves back to box 1.
