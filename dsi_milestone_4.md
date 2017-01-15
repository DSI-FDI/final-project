---
title: Milestone 4 - Heuristic Evaluation
author:
  - García Castillo, Pedro
  - García Ferreiro, Jorge
  - Reyes Parrilla, Daniel
  - Lorente Escobar, Borja
rights: Creative Commons - BY-NC
---

# Introduction

In this milestone we want to get insights from our prototypes. So we have reunited a group of experts to give feedback on our interactive prototype.

In this memory, we have documented all of the steps we followed from creating the scripts and prototypes for the evaluators to extracting the key information from their feedback.

At the end of this milestone, we have also created a bunch of ideas to fix in the future of our application. Most of them are minor fixes and they are not so relevant for a first version. However, it’s important to take them into account for new versions so the user experience will be improved.

# Prototype for the evaluators

We have evolved the previous prototype. So we have created an interactive prototype for the experts so they can move through the whole application easily and test different parts of our system independently. 

For this purpose, we have created high fidelity sketches. And we have built an interactive prototype using google slides. This let us to use animations and many interactions though different views.

You can see the interactive prototype: [Prototype](https://docs.google.com/presentation/d/1XPGqq5IAzQ_EloxhJEwI2QHGyqXgwKXgpMEkmk5kC-I/edit?usp=sharing)
In order to let the experts to use our prototype, we have created a ‘How to use it’ guide.

## interactive prototype: How to use it

**Update (12/01/2aps017):** We have included new views for the navigation mode. So now the user can receive topics and sentences while walking. When you go to the navigation slide, the controlling tabs change. So please, continuous reading to know how to use the “navigation tabs”.

The prototype contains a sequence of slides, that will cover the normal scenario when dating. This is useful for the heuristic evaluation. However, for the user evaluation we needed a way to move between views so the user can move freely through the application. 

To achieve this, we have added 8 tabs at the bottom of the prototype. To make the interface clear, we haven’t added any text explaining where are you going by clicking the tab (because this will be click by one member of our team in the background).

### Inside mode tabs

Tabs numbers (from left to right):

1. Home
2. Configure
3. Flirting/Dating
4. Girl Profile
5. Conversation Topics
6. Conversation sentences
7. Places
8. Navigation

And here is the visual explanation:
![alt text](./photos/how_to_use_prototype.png "")

###  Outside navigation mode tabs

When the user is in navigation mode. The tabs change in order to have the topics, sentences, etc views. So we allow our user to use the application in different ways.

Tabs numbers (from left to right):

1. Home 
2. Configure
3. Flirting/Dating
4. Navigation: propose topics
5. Navigation: propose sentences
6. Navigation: change restaurant
7. Arrive destination

# Initial preparation: plan and execution
## Research plan

We had 5 experts available for the evaluation. Our application focuses on **responsiveness** and strives to be **minimally intrusive**. Therefore, we have very few controls and screens, and we thought that every evaluator should be able to evaluate the whole app in a reasonable time. As a consequence, we agreed that a single script would suffice.

In addition to that, we decided to go with Schneiderman's list of heuristics, because we found that they were more aligned with our app. Since our app features a very particular and innovative technology, we thought that the more concrete heuristics in Schneiderman’s list would provide more information about any usability problem. We found heuristic number 8 particularly interesting, since we want to reduce the attention the user pays to our app.

## Research materials
For this evaluation, every expert was provided with two different materials:

- **The evaluation script,** which was taken from the keypath scenarios of the last iteration.
- A link to the evaluation form, created using google form. So they can send directly their heuristic violations while using the application.

## Evaluator script

We have created a evaluator script, so the can see clearly what we are expecting from them.

This evaluation has two main parts 
- The Component Evaluation, where the individual functionalities of our application will be reviewed
- The User Interaction Evaluation, where a complete interaction from start to finish will be evaluated. The app itself is quite short, therefore there should be enough time to perform both evaluations.

### Component Evaluation

In this section you will test isolated functionalities. So you can focus on a few views and screens. In the next chapter, you will need to focus on a whole story.

#### Obtain a person’s information

Here the focus should be on the user’s ability to understand and quickly parse the information about the other person, as well as the density and quality of the information provided. The more information we give and the less attention we require, the better.


1. Start from slide 4.
2. You are at the university taking a walk. You see this beautiful girl and go closer to her.
3. When you get closer, the app scans her face and displays information about her. This information includes her tastes, hobbies and mutual friends. Furthermore, a likeness indicator appears near the girl’s image.

#### Conversation: Select a conversation topic

In this section of the app, we imagine the user having a conversation with his/her date. The mission of the app is to ensure that the conversation never runs out, and that the user leaves a good impression on the girl.

1. Start from slide 6.
2. You start talking to the girl, and after a while the conversation runs out. The likeness indicator goes down.
3. Then, the app will suggest some topics to speak about taking into account the other person’s hobbies and preferences.
4. When you start talking about one of the topics, the app will replace the list of topics with a list of useful sentences to say about that topic.

#### Make reservations in a nice place

Here we assume that the user wants to take the date somewhere more intimate, so the app has to find a suitable place and make reservations.

1. Start from slide 9.
2. The app suggests a list of restaurants to go to. You ask the girl about going to one of those places.
3. When you both accept, the app makes a reservation if necessary and displays navigation information with directions to that place.

#### Use navigation to get to the restaurant

In this view, the app will direct the user towards the destination, providing information on the screen as they walk.

1. Start from slide 10.
2. As soon as they get to the restaurant the navigation information disappears and the app shows again several topics that could fit in the conversation.

### User Interaction Evaluation
#### Flirting

1. You are at the university taking a walk. You see this beautiful girl and go closer to her.
2. When you get closer, the app scans her face and displays information about her. This information includes her tastes, hobbies and mutual friends. Furthermore, a likeness indicator appears near the girl’s image.
3. You start talking to the girl, and after a while the conversation runs out. The likeness indicator goes down.
4. Then, the app will suggest some topics to speak about taking into account the other person’s hobbies and preferences.
5. When you start talking about one of the topics, the app will replace the list of topics with a list of useful sentences to say about that topic.
6. The app notices that the girl is hungry and it’s getting late, so it changes to date mode.

#### Dating

1. The app suggests a list of restaurants to go to.
2. You ask the girl about going to one of those places.
3. When you both accept, the app makes a reservation if necessary and displays navigation information with directions to that place.
4. As soon as they get to the restaurant the navigation information disappears and the app shows again several topics that could fit in the conversation.
5. As soon as you both start talking about one of those topics the app will recognise it and suggest you several useful sentences about that topic.
6. Then the app recognises that the girl is feeling very comfortable being with you and suggest you to take the date to the next level, maybe to go somewhere else. A more intimate place.
7. As it happened with the restaurants it will show you several options and it will recognise when you both accept to go to one of them.
8. The app displays again the navigation information to get to that place.
9. After this the app will just keep on recommending topics during the rest of the date.
10. But there is a last part. If the app detects that the other person wants to have a relationship with you it will notify it.

# How are we going to conduct the evaluations?

We provide different documents to the evaluators. First, a script that contains all the information they need to test our system which contains a list of features and keypaths we want to receive feedback.

Also we give then the document on how to use the prototype and a form to send feedback during the evaluation.

At the beginning of the evaluations we introduce them to our system and then we support them during the whole process (questions, ideas, problems, etc).

Some of the evaluators added feedback on different heuristics. As they said, there are not any heuristic violated. However, some feedback or ideas to improve it. This kind of messages contains the tag (feedback).

#  Severity reports
## Evaluator 1: Jens

Age: 21

Name: Jens

Jeans was really active on the process. He asked some questions and provided useful feedback. In general terms he is happy with the application. But he gave us some useful feedback (they are not violated heuristic, only things to improve the system). We have collected the Jens feedback in the following bullet points:

- **Shortcuts**
	+ (Feedback) Shortcuts are not really needed, so I do not find a real error in this case. But a shortcut could help to switch the settings while a conversation. But if I assume that the glasses, know what information I need because of smartness, such shortcuts will not really needed.		
	+ Heuristic: S02
	+ Severity: 1

- **Consistency**
	+	(Feedback) The glasses are smart and therefore the sequence of informations and dialogs will fit my needs. -> There will be no violation here.
	+ Heuristic: S01 (Consistency)
	+ Severity: 1

- **Informative Feedback**
	+ (Feedback) I can assume that I can get all information without waiting. In this case there cannot be any violation here.		
	+ Heuristic: S03 (FeedbacK)
	+ Severity: 1

- **Closure**
	+ There is no obvious ending in the application. After a night of dating a girl, it could be nice to get statistics and further recommendations to develop the user's dating abilities.		
	+ Heuristic: S04 (Closure)
	+ Severity: 1

- **Errors**
	+ (Feedback) The app is smart. There will not be any bad errors, I assume.
	+ Heuristic: S05 (Error Handling)
	+ Severity: 1

- **Undo**
	+ (Feedback) Nothing is permanent. So, no undo feature is needed.
	+ Heuristic: S06 (Reversal of actions)
	+ Severity: 1

- **Control on the app**
	+ (Feedback) I assume that the app is smart, so I can control it indirectly. Only with my reaction the app will adapt. So, I feel always in control.		
	+ Heuristic:  S07 (Locus of Control	)
	+ Severity: 1

- **Memory**
	+ (Feedback) I detected that no short-term memory is needed. It is perfect for the situation because I do not want to remember anything when I use the app.		
	+ Heuristic: S08 (Short-term memory load)
	+ Severity: 1

## Evaluator 2: Fernando

Age: 21

Name: Fernando

Fernando only submitted two messages to our system. However, he was proposing some ideas “on site” while the evaluation was taking place. For example, he told us about the map situation. He thought is perfect to have it right-bottom. However, what about if the user change the opinion and want to go to another place intentionally? Also, what about if the user wants to give a longer walk instead of going through one way? He said we should take this scenarios into place, so the user can move freely. 

- **App feedback**
	+ (Feedback, not violation): The user could be happy about feedback if he`s doing a good job or after the interaction points for improvement for the next time.	
	+ Heuristic: S01 (Visibility of system status)
	+ Severity: 2
- **Navigation control**
	+ The user can change the opinion and go to another place while going on navigation mode. Also the application needs to recognize if the user wants to make a longer walk because the conversation is nice.
	+ Heuristic: S03 (User control and freedom)
	+ Severity: 3

## Evaluator 3
## Evaluator 4
## Evaluator 5
# Debriefing

We didn’t enough time to make the debriefing with the experts. However, some of them also gave us some ideas and tips to fix some problems while evaluating our design. This was included in the previous section with the tag `Feedback`. So we took into account their information and also our team discussed some of the problems from previous chapter.

With those problems we started to figure out how to fix things in order to improve the user experience. And also, what are the key ideas we should focus on the future of our application.

The good thing on this period is in general terms we did a great job with the interface and there weren’t any serious problems. However, we collected many minor ideas to improve our application. And those details are quite important too.

In the next chapter we show you what are those changes we should fix in the future of our application. Those ideas are resulting from this ‘debriefing’ session.

# Final list of changes and priorities

We have created a list of stuff to improve in the future of our application.
- [LOW] Allow to change the navigation route depending on the user intentions (like staying longer time) or how does the girl feel.
- [MEDIUM] Allow to cancel a reservation depending on a new plan.
- [LOW] Record all the previous dates of the user. And show statics in the screen so the user can know how was the date, get statistics and further recommendations to develop the users dating abilities.


