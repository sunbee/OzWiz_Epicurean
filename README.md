# OzWiz_Epicurean
A Telegram chatbot to suggest healthy recipes with available ingredients.

We like to eat healthy by cooking at home. Picking up fresh ingredients on the daily commute is a time-saver and avoids waste. But we are often guessing what's in the pantry at home to plan for the day. What if we had a robot do the due-diligence and make a recommendation, wouldn't that be great?!

Mobility is key. But building an app involves software development effort beyond a weekend project. A better approach is to use existing platform and fit it out to the requirement. Sounds like a job for a chat-bot!

Chat-bots have become popular of late. A bot can be programmed to respond to text messages and commands. A bot appears like just another person with a name and id. However, a bot can only respond to a message and not initiate a conversation. (Otherwise the platform would quickly be overwhelmed with spam.)

Bots are just special accounts that subscribers can interact with. Any subscriber can create a bot. A bot can respond to text messages and commands. However, a bot can never initiate conversations with users. (Otherwise the Universe would be awash with spam.)

I picked Telegram to implement a chat-bot. As an app, Telegram is an instant messaging software like WhatsApp. Unlike WhatsApp, Telegram has an awesome API. And unlike WhatsApp, the platform actively encourages bots. And unlike WhatsApp, it isn't owned by Facebook. ;-)

The [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) project offers the means to program a bot in Python. Aside from support for the base API that a developer would expect to find, the [telegram.ext](https://github.com/python-telegram-bot/python-telegram-bot/wiki/Extensions-–-Your-first-Bot) sub-module offers cool features in modern programming style for automation with queues, filters and handlers. It is a fantastic way to program in the DRY style advocated in [The Practical Programmer](https://en.wikipedia.org/wiki/The_Pragmatic_Programmer) and a natural choice for my Epicurean bot.

For querying recipes, I selected the [Spoonacular Food API](https://spoonacular.com/food-api). The free account works on a points system with a fixed daily quota. Points are deducted per query made depending on the API end-point used. The Spoonacular API offers access to a comprehensive database of world-wide cuisines with smart querying based on Natural Language Processing (NLP).

So after a weekend of programming in the COVID-19 curfew, here is what the product looks like. If you have Telegram on your phone, strike up a chat with Epicurean a.k.a. @epicurryin_bot. Type /start in the message box and follow instructions. You don't even have to say hello! 

Here is a snap-shot from what was in my fridge today.Here is a screenshot of Epicurean, the chatbot I have programmed.

![Epicurean_snap](https://user-images.githubusercontent.com/5471571/84470785-e8acb480-ac38-11ea-977e-d224500f4352.png)

My bot will build a recipe for you based on the ingredients you provide and tastefully present it as a recipe card. Here is a sample recipe card I got for dal (Indian lentils), onions and carrots. It is pretty impressive how effortlessly the [Spoonacular API](https://spoonacular.com/food-api/docs) uses NLP to bridge-over different languages and culinary idioms. 

[
![recipeCard-1591936354848](https://user-images.githubusercontent.com/5471571/84470346-075e7b80-ac38-11ea-983d-88f63a49dbbc.png)
](url)

And it even tells a dirty joke or two! Send a /joke command to get a random joke when the kids are not around.

![Epicurean_snap2](https://user-images.githubusercontent.com/5471571/84470910-2ad5f600-ac39-11ea-95a0-6ff23c19d48d.jpg)
