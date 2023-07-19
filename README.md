# Telegram Bot for Cocktail Ingredients and Recipes

## Introduction

CocktailBotAPI is a Telegram bot that assists users in discovering cocktail recipes and information about cocktail ingredients. The bot's custom API interacts with a public API to search for cocktail recipes and leverages the Amazon DynamoDB database to store user-contributed cocktail names and images.

### Problem Statement

The CocktailBotAPI aims to address the following challenges:
- Enable users to find and view cocktail recipes based on their names or specific ingredients they input.
- Facilitate the addition, removal, modification, and retrieval of all cocktail names in the database.

## Functionality

CocktailBotAPI offers the following features through its custom API:

- Retrieve cocktail recipes based on their names.
- Get a random cocktail recipe.
- Find cocktail names based on specific ingredients.
- Obtain information about a particular cocktail ingredient.
- Add cocktail information to the database and retrieve details of a specific cocktail.
- Remove cocktails from the database and update their names.

## Client Features

The client, in the form of a chat-bot, interacts with the custom API, providing users with convenient functionalities:

- Choose search criteria for cocktail discovery.
- Select parameters using user-friendly buttons.
- Interact with the database for a seamless experience.

## Technologies Used

The CocktailBotAPI is built using the following technologies:

- ASP.NET Core Web API for creating the custom API.
- Amazon DynamoDB for database storage.
- Telegram bot developed in C# using .NET Core 3.1.

## Bot Links

- Telegram Bot: [CocktailRecipeBot](https://t.me/CocktailRecipeBot)
- Heroku Deployment for Bot: [CocktailBotAPI on Heroku](https://dashboard.heroku.com/apps/tgcocktail)
- Heroku Deployment for API: [CocktailBotAPI's API on Heroku](https://dashboard.heroku.com/apps/cocktail-api1)

## How to Use

To interact with the CocktailBotAPI, access the Telegram bot using the provided [link](https://t.me/CocktailRecipeBot). Enjoy discovering exciting cocktail recipes and ingredients!

## Contribution

We welcome contributions to enhance the functionality of CocktailBotAPI. If you find any issues or have ideas for improvements, please feel free to create pull requests or submit issues on the GitHub repository.

---
We hope you enjoy using CocktailBotAPI to explore the world of cocktails! Cheers! 🍹
