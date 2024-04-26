---
layout: essay
type: essay
title: "Cooking Up Delicious Software (through Design Patterns)!"
# All dates must be YYYY-MM-DD format!
date: 2024-04-24
published: true
labels:
  - Design Patterns
  - Software Engineering
---

<img width="300px" class="rounded float-start pe-4" src="../img/cooking-up-delicious-software.jpg">

## A Restaurant Order without Order

Suppose you went into a restaurant and immediately after walking through the entrance, it was chaos. No waiters in sight, customers in the kitchen interfering with the work of the cooks, and the cooks unable to coordinate themselves. This would be a restaurant that has not implemented the principles of design patterns. They have not implemented a standard way for customers to order dishes from the kitchen and subsequently deliver the dishes to the customer. It is completely up to the whims of individual customers of how an order is conducted, and thus cooks have to contend with all those whims in a way that decreases productivity and reduces quality of the final product. So, shall we go about constructing an actual restaurant?

## Chefs are pretty important!

Unsurprisingly, a key element of a customer order is the chef making the order. As customers, we do not want to be involved with the creation of the food! The chef, in the confines of their kitchen, hides, or abstracts, the messy details of cooking away from the customer and focuses on making the dishes. Each particular dish has its own particular ingredients, its own requirements for preparation, but in the end, we do not have to think about it! We delegate that work to the chef.
This is what the factory pattern is all about. Rather than using the normal constructor methods associated with object oriented programming, a “factory” class is created which handles the creation of objects, which in this metaphor is dishes. It can return dishes from multiple kinds of recipes (classes) and handles the creation/preparation of different dependent ingredients required for the dishes. Of course, this kind of middleman does add some complication to the endeavor of making food, but for the user/customer, they will usually not see that complexity. They will just get the food.

## The waiter is also quite important!

In the restaurant equation, the waiter or cashier is also a crucial element. Again, we do not really want to be involved in the creation of the food! Thus, the waiter/cashier acts as an intermediary between us and the kitchen. We tell the waiter what we want and the waiter will relay that order to the kitchen. Now, the kitchen is doing much more than just making your dish, but you do not need to know about it. All you will know is that, when your dish is done, it will be brought to your table, and you will be able to eat.
This is essentially the MVC model. As programmers, we want to split a data model’s internal structure from how it is presented to users, so as to keep it simple and accessible. So, we only let users interact with a controller, which then manipulates the data model, and the data model will in return eventually update the view that users see. It makes sense, and although it requires more code and some more thought, it makes the user experience a lot more pleasant!

## …so how is this software engineering?

Through these different patterns, we can build our applications in a way that is simpler to follow and function better as a result. For instance, in our “Rainbow Cards” website, which is a trading card game where the cards have different professors, several patterns have been implemented or are planned to be implemented. One such pattern is the MVC model we just covered! We do not directly interface with the data collection of cards while adding or editing cards; we instead use a page which accepts a valid format of information and passes it to the data model, which then inserts the new information and updates the various catalogs users can access to look at the newly created or modified cards.
As part of the “V” part of the MVC, we use another pattern called the observer pattern. Using our restaurant metaphor, this would be like the pizza tracker Domino’s employs on its website, the TV some fast food restaurants use to display ongoing orders, or, in a very basic sense, someone from the kitchen shouting a name for the rest of the restaurant to hear. We subscribe observers, or catalog pages, to the data model’s collection of cards. Whenever the collection is modified, the subscription notifies all catalog pages of the modification, and they will change in accordance with the modifications. It is responsive in every way you’d want such a page to be, and what is shown on each catalog page will be consistent with how the data model actually is.
While tricky at first to learn, it became very apparent what these patterns were. In some cases, it is almost common sense. Of course you would not let the user directly edit the database, that would be insane! However, in other cases, it feels like unnecessary redundancy. The factory pattern, while useful for creating objects with many dependencies, feels needlessly complicated for most situations where you want to create objects. The singleton method, as well, seems like asking for trouble with its ability to enable global-esque variables. However, in the end, it’s understandable why we have these patterns to begin with. Standardization ultimately helps ease the learning curve for those new to software design, and once one understands them, do quite a lot. Plus, with design patterns either abstracting or separating all the messiness of code, we can finally get to do what we wanted to do in the first place; we get to eat (create)!

