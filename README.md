# Recipe-Tracker

This project is a basic recipe manager. It stores recipes with details like ingredients, cooking time, ratings, and automatically calculates useful properties such as average rating, total ingredients, and difficulty level.

📌 Features

Store multiple recipes in an array.

Each recipe contains:

Name

Ingredients

Cooking time

Ratings

Automatically calculates:

✅ Average rating

✅ Total number of ingredients

✅ Difficulty level (easy, medium, hard)

🛠️ Functions

getAverageRating(ratings) → returns the average of recipe ratings.

getTotalIngredients(ingredients) → counts the number of ingredients.

getDifficultyLevel(cookingTime) → assigns difficulty based on cooking time:

<= 30 mins → easy

31–60 mins → medium

> 60 mins → hard
