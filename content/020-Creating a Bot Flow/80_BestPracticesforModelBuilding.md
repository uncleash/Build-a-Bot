---
title: "Best Practices for Model Building"
chapter: true
weight: 80
---
## Defining Intents
A model is more than intents, it is also a flow and a journey. 
Defining intents:
* Examine the business flow first (Regardless of whether the bot can do something or not) before defining the intents and slots
* Define the intents, definitions - these need to be rooted in the business goals. What do they already do here. (i.e.) press 1 for sales, press 2 for support etc etc
* Make sure your definitions have clear boundaries, with no overlap
## Intent Examples

* Provide at least 20-30 typical examples per intent
* Make sure to provide variations:
    * in the form of questions / statements people can make
    * in the keywords that can represent the intent
    * make sure to include synonyms to intent (book a hotel, reserve a room, make a reservation, etc.)
* If intent has slots (entities) to fill,
    * make sure to define the entity and its possible values
    * include value synonyms
    * provide intent examples with and without entities in the sentences
    * select default or custom prompts for each entity

