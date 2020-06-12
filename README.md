# OzWiz_Epicurean
A Telegram chatbot to suggest healthy recipes with available ingredients.

My wife and eat healthy by cooking at home and avoid waste.
Picking up ingredients on the daily commute is a time-saver.
But we are often guessing what's in the pantry for the dish we will make.
What if we had a chat-bot to do due-diligence and make a recommendation, wouldn't that be great!

Mobility is key! We are always on the move. But building an app incurs development overhead. I want to use an existing platform and fit it out for my needs.

Chat-bots have become popular of late. A bot can be programmed to respond to text messages and commands. A bot appears like just another person with a name and id. However, a bot can only respond to a message and not initiate a conversation. (Otherwise the platform would quickly be overwhelmed with spam.)

I have implemented the chat-bot in Telegram. Telegram has an awesome API in comparison with other options like WhatsApp. The platform encourages use of bots unlike WhatsApp. For Python programmers, the `telegram.ext` library over the base API is top-notch and offers features to set up automation with queues, filters and handlers. 

For querying recipes, I have used the Spoonacular database. The account works on a points system with a fixed daily quota of free points. Points are deducted as queries are made depending on the API end-point used. The Spoonacular API offers comprehensive querying capabilties to access a huge database of recipes from cuisines world-wide.

Here is a screenshot of Epicurean, the chatbot I have programmed.

![Epicurean_snap](https://user-images.githubusercontent.com/5471571/84470785-e8acb480-ac38-11ea-977e-d224500f4352.png)

Here is a snap of a recipe-card build using Spoonacular API.

[
![recipeCard-1591936354848](https://user-images.githubusercontent.com/5471571/84470346-075e7b80-ac38-11ea-983d-88f63a49dbbc.png)
](url)

And it even tells a dirty joke or two!

![Epicurean_snap2](https://user-images.githubusercontent.com/5471571/84470910-2ad5f600-ac39-11ea-95a0-6ff23c19d48d.jpg)
