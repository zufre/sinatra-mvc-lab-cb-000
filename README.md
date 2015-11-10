# Sinatra MVC Lab - Pig Latinizer

In this lab, you'll be building a **Pig Latinizer** using Sinatra and the MVC paradign of app development. Your app will take in a string from a user through a form, convert it to pig latin, and return the string to the user. Using the previous code-along as a guide, get the tests to pass by building out this application. Use the guide below to get you started!

## What you'll need to do

+ Build a form to take user input in user_input.erb
+ Create a `POST` method in your controller (`app.rb`) to receive your form's `params`.
+ Build a `PigLatinize` model (in your models directory) that converts a string into pig latin.
+ In your application controller, create an instance of the `PigLatinize` class to convert your user input to Pig Latin.
+ Use ERB within a new view to display the final pig latin string to the user.