---
layout: post
title: "Nilsen's Heuristics, or 10 principles of a good user experience design"
author: "Konstantin Smirnov"
categories: journal
tags: [documentation,sample]
# image: cards.jpg
---

End user rather will close your website before trying to understand how to use it if is overcomplicated. Of course if your website is not a tax payment service and is the only place where user may pay its taxes - then there is no another option.

Jakob Nielsen was a well known expert in usability. In 1990 in collaboration with Rolf Molich he developed and later refined ten heuristics  - rules that a user friendly interface should follow.

Heuristic - it's a useful algorithm or method which does not have strict proof or guarantee of being optimal or perfect, but useful in practice and helping to reach short-term goals. In most cases heuristics help to solve problems

In spite of many years passed since Jakob Nielsen had introduced his ideas, they are still widely used due to its simplicity and universality. Interfaces became more complicated, but the same principles still successfully used by researchers to analyse the usability.


In common, heuristics are used as a check list when researchers evaluate and analyse websites and mobile app interfaces and compare them with best practices on the market. This peer review method is quite popular and much simpler and cheap than usability researches with focus groups etc.

<br>

## 10 Usability Heuristics for User Interface Design by Jakob Nielsen

### 1. Visibility of system status
End user should always be aware what happens with the system. Interactions should be supported by a feedback within a reasonable time.
There are a few examples: when you press a button, you expect some action to happen. If there is a long process behind the button (processing some data to display calculation results) - then the button should reflect the process behind it (a spinner or a progress bar etc) or some notification should appear.
Another example - when you order an Uber taxi, then after submitting the request you expect to see your order was picked up and where the driver is. That is proper feedback.

### 2. Match between the system and the real world
The system should interact with users on a language they understand and a natural way. The user should see well known words from the real world, not technical terms. For example, "The list of subscriptions is not initialised" better sounds as "You have no subscriptions". It is also important to notice here that in most case the researcher's language is not equal to the customer's language therefore it requires to be analysed carefully.
Another example is the website architecture and navigation. It should reflect user's understanding of the world, so he will be able to find things quicker. As you may know, it's a scientific fact that a watermelon is a berry. But would a customer looking for it on a website go to the 'Berries' category for that? Not sure.

### 3. User control and freedom
User should have the possibility to revert back an action done by mistake, or if the user changed their mind. Interfaces should let users to get back to previous system condition with a minimal effort.

For example, if a user cancelled email subscription, he should be able to subscribe again. If an order was cancelled (by mistake or by error), it should be simple to repeat the order.

### 4. Consistency and standards
Do not confuse users by providing different experience for similar functionalities, or by using different terms for same processes. The use experience should be consistent in the whole system (or ecosystem).

Users spend a lot of energy to get used to the system functionality, therefore you shouldn't make drastic changes in the patterns user is used to. Also it has meaning for market standards - the patterns which were learned on other websites and applications.

The principle of consistency may be applied at different levels
- system visual style (should use a style guide)
- system components behaviour (a good idea to maximally reuse components where it makes sense)
- navigation consistency
- content consistency (labels, terms, button names etc)
- etc

### 5. Error prevention
All users may make mistakes, that is normal. The interface should do as much as possible to prevent situations in which a mistake may cause improper system behaviour or do negative impact to the user or business. Even if you have error messages indicating that provided data is invalid, still would be nice to help user provide data in a correct format from the beginning.

If you ask the user to provide a phone number, do not ask to type in an empty field. Use a smart phone number format masking - automatic + symbol in the beginning, then pre-filled default country code (depends on your service if that can be changed by a user), the number digits separation according standard phone format should be done automatically. Something like that will be accepted by users better than an error message "Your phone number format is invalid. Please provide correct one".

### 6. Recognition rather than recall
Do not force the user to remember a lot of objects, instructions etc. Working in the system should be natural and relatively simple. Placing an order, user should get all the needed information about the order, payment options, delivery address and when it will be delivered in personal account as well as in an email.

### 7. Flexibility and efficiency of use
Users working with the interface having some routine actions, especially if users are experts - they should have ways to perform actions more efficiently and quickly.

For example hotkeys improve speed of working with advanced functionality and help experienced users perform better.
If there are some frequent actions, there should an option to find them quickly: phone number to call the company usually is placed in the header or footer for an easy access.

### 8. Aesthetic and minimalist design
This principle is related to multiple areas - texts, visual design, forms, etc.

Texts should not contain useless or redundant information. This is not only about content pages, but also interface labels. Buttons, fields names should reflect their functionality in a concise and clear way. While working on texts always think how the customer will perceive it. Each extra text makes interface elements less visible, therefore the user has less chances to find the needed information or function.

The minimalism in design is very subjective, but still the recommendation here is to provide the user with minimum options that need to complete the user flow. No redundant functionality should be added.

### 9. Help users recognise, diagnose, and recover from errors
While the point 5 says that we should avoid user making mistakes if possible, in some cases error message should be displayed. Error messages should be clear, written on customer language and help to solve the problem.

As an example of an error message was provided such example: "Your phone number format is invalid. Please provide correct one". This message contains information that a problem appeared, but still does not say anything about how to fix that. Better variant would be "Please provide phone number in format +1 234 345 56 67" - it indicates what should be done and how.

Also a possible case is an empty page with search results. One of the variants of how not to display an empty page, may be displaying a proposal of correct key phrase (of original key phrase has many mistypes) and some links to content pages, or products (highest rating, top selling etc).

### 10: Help and documentation
We try to create systems that are intuitive to users and do not require additional documentation. We admire products from Apple, Uber, Netflix and believe that is how a product should be designed. But not always is possible - it may depend on business or user flow specifics, some technical limitations and so on.

Documentation, or additional materials should help users to work with new functionality. It should be simple, well structured, concise and easy to get the needed information. Different tooltips available during the first time using the system may be also counted as a kind of documentation and should help user, not distract him.

<br>

## When to use heuristics

Nilsen's heuristics are the minimal criteria an interface should follow. They are widely known and accepted by user experience researchers.

In spite Nielsen's heuristics bring real benefits in most cases, they are still subjective. That is why it's important to perform heuristics analysis in a team. Performing an analysis alone, the expert's bias affects research results. Experts tend to note the facts that prove their personal opinion or view on a problem. Something may seem a problem for the researcher, but not to be a problem for a customer. Also, one person can not find all problems alone, in many cases it requires different views from different persons to discover all problems. Still, very often heuristics analysis are done by one person.

Can the heuristics be used for anything? It would be fair to say that there are cases when Nilsen Heuristics do not work well.

When Nielsen developed his heuristics based on a thousand of inputs trying to figure out common rules fitting any interface. In result, heuristics are too common that does not help to discover specific interface problems. For example, touchpad have different principles of interaction with a user than desktops or laptops.

Minimalistic design is also a subjective matter. Each person has their own understanding of what is that, based on its background.

<br>

## How to make a good research by heuristics

- *Use a team of researchers* so that subjective opinion of a separate expert is minimised. Estimations from different persons will be different and the medium value will be more objective.
- *Understand business challenges.* Check the usability standards  which may fit to your product. Investigate which other products do customers use and see what are the common user experience patters used there. See what is trending now, what will become a standard in the near future. May be a combination of standards would fit your product better.
- *Basic skills in the area.* The researcher should understand the product which is being analysed and the related area of knowledge. It is important that the researcher and the customer have similar thinking and understanding of the product, so that the found problems would be closer to customer problems.
