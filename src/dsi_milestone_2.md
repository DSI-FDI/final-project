---
title: Milestone 2 - Modelling and Requirements
author:
  - García Castillo, Pedro
  - García Ferreiro, Jorge
  - Reyes Parrilla, Daniel
  - Lorente Escobar, Borja
rights: Creative Commons - BY-NC
---

# Modelling
## Plan and Execution

For this part of the design process we gathered all the artifacts generated in the Research phase and tried to create meaningful groups of information. For that, we chose the bottom-up approach, since it was the most convenient for a distributed online workflow. In addition to that, our data was already skewed towards certain trends and populations (Undergraduate male) and therefore we thought that it wouldn’t be hard to identify clusters of behavioral variables.

During the modeling phase and after identifying the behavioral variables, we came to the realization that we had not specified the name of the users to which the concrete factoid applied, but instead we were writing statements such as “One male user thinks that…” or “Most users said that…”. Therefore, the classification of attributes according to the class notes (with the names of the users in the X axis of the table) was not going to be possible. Instead, we proposed several alternatives:

1. Simplifying the classification to a single group, with a property list more resembling the factoids.

| Aptitude | How much?     |
| :------------- | :------------- |
| Organizes the first date      | Often       |

2. Exchanging the X and Z axes of the table, putting in the columns the magnitude in which an aptitudes and mentalities happen in the users, and in the cells the group of users to which it applies.

|                          | Not at all              | Rarely          | Sometimes  | Often | Always |
|--------------------------|-------------------------|-----------------|------------|-------|--------|
| Organizes the first date | One user                |                 | Most users |       |        |  |

|                          | No                      | Yes   |
|--------------------------|-------------------------|-----------------|
| Works?                   | All male users except 1 | One female user |

After some experimentation, we decided to go with the second option, as it provided sufficient clarity to allow identifying patterns.

Once the behavioral variables were identified, we used that list and the factoid list to classify our users’ responses using the technique described above. As expected, the data was not very concrete, but it was detailed enough and had enough variables so as to provide a clear direction for distinct behavior patterns, which finally lead to the creation of three distinct personas.

These three personas confirmed our hypotheses, since the primary persona was a male undergraduate student, and the secondary personas were a female undergraduate student and a male graduate who is working.

## Behavioral variables

The behavioral variables were extracted from the factoids and the interviews:

### Activities
What the user does; frequency and how much time do they spend:
- Dating on a public place (bar, cafeteria, restaurants or pubs) where you can talk without interruptions.

   **Frequency:** very frequent.

   **Time spent:** from a short meeting (30 minutes) to a long date around 3 hours.

- Organizes the first date.

   **Frequency:** normal

   **Time spent:** from 30 minutes to 1 hour.

### Attitudes
How the user thinks about the product domain and technology:
- Intrusive for their privacy.
- Skeptics to see how it will work. They don’t want to use something that feels  artificial.
- Curious to see how good and valuable are the tips while dating.

### Aptitudes
What education and training the user has; capability to learn:
- University studies.
- Capacity to learn.

### Motivations
Why the user is engaged in the product domain:
- Catch liars and detect “fake” people.
- Want long term relationships.
- Be successful on dating.
- Improve their ability to date new people.

### Skills
User capabilities related to the product domain and technology:
- They are good at using mobile apps.
- They have some prior dating experiences.
- Feel nervous while dating.

## Behavioral variable map

After identifying the behavioral variables, we laid them out in the variable map, so as to identify behavioral patterns in our users. The result is included in a separate file.

With the results, we were able to identify several behavioral patterns:

- The users that organize first dates are usually male.
- The users that want to know if the other person is lying about him/herself also want to know the other person’s biography and dating history.
- The users that want to know things about the other person during the date want to be informed by a notification.
- The users that want a long-term relationship are usually female.
- The users that listen to and apply friends’ advice are looking for long-term relationships.
- The users that don’t advice their friends to be themselves during a date are male.
- Females want to make them first date in a place where they can talk.

## Draft of personas

### 1st  persona (Primary):
Boy studying at the university:
- **Life goal:** Being sure the other person will like them, have a long relationship if they like the girl very much.
- **End goals:** Know how to organize a good first date, they want to know topics of conversation, know hobbies of the other person beforehand, know trending places to go with the girl.
- **Experience goals:** They want to be sure that everything is under control.

2nd persona (Secondary):
Girl studying at the university:
- **Life goal:** Have a long-term relationship
- **End goals:** Know about other person’s life before dating, they want to feel comfortable and “be themselves”, want to talk during the date.
- **Experience goals:** They don’t want to have information about how to act because it is very artificial

3rd persona (Secondary):
    Man with university studies:
- **Life goal:** Be compatible with the person he likes.
- **End goals:** Know how to organize a good first date, they want whether he is  going to step over a boundary, would like the possibility of having a long-term relationship.
- **Experience goals:** They don’t matter to know people by applications.

## Personas

We have created 3 personas.

- Josh (Primary)
- Helene (Secondary)
- Aaron (Secondary)

Go to the folder **personas** to see their profiles.

# Requirements & intermediate process for the personas

## Josh
### Problems and vision statements

#### Problem 1:
- Josh is uncomfortable and doesn’t know what to say. The conversation is getting dangerous for himself.
Vision statement: A small notification will be shown at the right-upper part of the interface with information about subjects of interest of the girl and what to say in the very first beginning of this new conversation.

#### Problem 2:
- The girl is bored of the place where they are and wants to go to do something else. She asks Josh for advice but he is in blank.
Vision statement: Whenever he is asked for going to another place a map will be shown also on the right-upper part of the interface. There Josh can see some trending places to select one. He only has to say loud the keywords “Let’s go to..” and the name of the place. So the map will update showing the actual track he has to follow.

#### Problem 3:
- Josh doesn’t know the girl and he doesn’t know where to set the first date in order to success.
Vision statement: A list of the hobbies of the girl can be shown beforehand to get more close to the likes of that person.

#### Problem 4:
- The girl starts a conversation with a subject that Josh doesn’t control (for example a tv star that Josh doesn’t know). Josh is getting out of control of the situation.
Vision statement: A Wikipedia’s biography of the famous person, historical fact or whatever will be shown in the left part of the interface. So Josh will know at least the most important details to follow the conversation.

#### Problem 5:
- Josh doesn’t know how the girl feels because he is very nervous and doesn’t feel the confidence to look for a while to her eyes/face.

Vision statement: A word specifying the emotional state of the other person will be shown always at the bottom-center of the interface.

### Identifying Josh expectations

Josh has known a very beautiful girl the last weekend in a club. He has begun to talk to her a week ago by whatsapp. It is the moment of meeting her in person, the problem is that he doesn’t know her very well so he puts on the contact lenses and search for hobbies of the aforementioned girl, let’s call her Anne. Now that he knows exactly where to date he chats in whatsapp in order to finish the proposition. Anne accepts because she really wants to go to that place and she likes Josh.

After a day they meet in a really cool rock bar in Madrid, where they are going to buy some drinks. Josh would like that Anne doesn’t realize that he is using the app so it seems to be natural.

He also expects those notifications to be away of Anne’s face to ignore them and continue the conversation if he wants. Also he thinks that the app will know what to notify in every moment without making evident inputs so he won’t become nervous or weird.

### Josh context scenarios

Today Josh is walking to a bar where he is going to have a date with a very beautiful girl called Anne. He puts on his e-ContactLenses and starts to improve his probability of success in his day. John first see Anne’s hobbies and biography before getting into the bar so he knows beforehand some useful information.

Josh enter to the bar so happy because he is going to date his favourite girl but he is so nervous that he didn’t notice that when greeting Anne she was a little bit sad. He realized that something was wrong when he perceived that the emotional state of she showed by the application says that she was sad. Josh then decided to start the conversation by saying “I perceive that you are not very happy today, has something happened to you today?”. Then they start to talk for a long time about their studies, life and friends.

The date was going amazing until the girl started to talk about Harry Potter that was her favourite film. Josh never have watched that film so he asked for information about that film, because he wanted to keep that amazing moment between them. As this was a very dangerous way of following the conversation he wanted to know a way of changing the subject they are speaking right now without being so evident.

He asked the app what topic of conversation was better to change at that moment and he received that it could be interesting to know the role of wizards on viking’s society. This a very good topic for Josh since he is a history students and he knows a lot of it and also he is going to have fun when talking about it. On the other hand Anne will be surprised about Josh’s knowledge a she will be very interested about how Harry Potter is some kind of connected with ancient viking's societies.

At this moment the conversation was very interesting for Josh but Anne was becoming bored and so the emotional state showed by the application changed. At this moment Josh thinked that this was not so important because he was enjoying that moment so he decided to continue.
After some more minutes Anne’s was tired of the conversation and the place where they were and she decided to suggest Josh to go to some cool place on the street to breath fresh air.

Josh didn’t know any cool square or maybe avenue near to their location. He started the map on the app and decided to go to a beautiful banks on the sea promenade, following every step indicated by the app.

When they arrived a notification was shown telling him that it is the moment for kissing her. They kissed and end of the date.

### Josh requirements

- Connect (Action) with wikipedia to show biographies or historical facts (objects) that are interesting to know for the user (context).
- Connect (Action) to every social network to subtract the personal information of the hobbies of the target girl (object) before the date (context).
- Connect (Action) to Google Maps (object) when requested by the user (context).
- Communicate (action) with the e-ContactLenses (object) in any moment in the date (context). 

## Helene

### Identifying Helene expectations

Helene is a very good law student who was born in a happy family. He is very enthusiastic and during the week she is really busy with the university.

Her main aspiration is to build a family with the right guy. Helene doesn't like to waste time with guys because her previous experience with guys was really bad.

She wants to find the right guy who is trustworthy and wants to make a family with her.
Helene main wish using the product is to know beforehand as much information as possible about the guy. She is really interested in knowing past relationships to check if the guy is good or not. And also she wants to know all the information regarding to the guy hobbies.

Using the application she wants to see in real time what are the feelings of the guy and also if he is falling in love. That is because Helene is very insecure while dating and she wants to be sure that he is the man of her dreams.

### Helene context scenario

Monday. Afternoon. Law university library.

Helene was studying in the university library. She suddenly saw a beautiful guy next to her. Helene was very enthusiastic and started to imagine a life with this guy. Before doing anything she asks our lenses how is that guy. Our app tells Helene that he is a completely asshole. Basically he broke up with all the previous girls and he is not looking for a long term relationship. Thanks to this information, Helene decides not to talk with the guy and not waste her time.

Saturday. Night. Madrid Bar.

Helene is hanging out with her university friends in a cool place in Madrid. She saw a nice guy in the entry. Then she asks our lenses to get a summary of all the previous relationships of that guy. Our app, tells Helene that he is trustworthy. All the ex-girlfriends say he is a nice man. And also that he is looking for a long-term relationship (the same as Helene is looking for). So! That's all the information Helene needed to decided to approach and start talking with the guy!.
During the conversation she asks our app to get all his hobbies. She realize that both like "romantic" films. This makes Helene really happy because she is also looking for a romantic and cool guy. All the conversation flows really good!.

Our app tells Helene that the man is starting to fall in love. So she was happy and acting very natural!. At the end Helene proposes to meet the next day. And the rest is a story with a happy ending!

### Helene requirements

- Display (action) a box (object) to see all the previous relationships of the guy and see the comments of their ex-girlfriends beforehand (context).
- She wants to know if the guy is trustworthy, so the app has to notify(action) this information and the reasons(object) in advance(context). So Helene does not waste the time.
- The app should notify (Action) if the guy (object) is looking for a long term relationship during the date (context).
- The app has to analyze (action) the user gestures and face (object) and find if the guy is starting to fall in love (action) at every moment (context).
- It should search (action) for common hobbies(object) and propose new topics (action) to Helene in the screen when the conversation stacks (context).

## Aaron
### Identifying Aaron expectations

Aaron is not a shy man so he feels quite comfortable while dating with a girl but he has another problem he had some problematic relationships in the past and since then he likes to know some information about the past of the girl he dates before deciding to continue with her. That’s why he would find very useful to have access to that.

Also he likes the program to give all the information at the same time he is having the date but in a fashion that he can focus half of his attention on each the program and the girl. He doesn’t want many information to be shown on the screen because he thinks he can get distracted easily.

### Aaron context scenario

A couple days ago Aaron met a girl online and today is going to be the first day they meet in person, Aaron proposed to meet in one of his favourites art galleries and the girl accepted the invitation.

While he was waiting the lady he puts on his e-ContactLenses and he starts the dating app so he is ready at the moment when the girl arrives.

And that moment finally arrives she is so beautiful, but Aaron doesn’t want to be guided just by the appearance of the girl so he asks the app to give him some information about the girl biography, he wants to have an idea about her past to know if there’s something strange on it since he is having a bad feeling.

He checks it a bit while he talks to the girl and as he doesn’t find anything strange he decides to keep up with the date.

As the date advances they start talking about hobbies and what they would like to do in the future and Aaron decides to check if the girl is lying about the information on any of those. And as he finds some minor lies but he thinks that they are perfectly normal.

Then the app suggests Aaron to change the place because they have been talking all this time inside the art gallery and they are getting somehow stuck on the same themes, so he asks the app which could be a good place to go and the apps points about a walk on the riverside since the girl loves the nature.

After a while walking on the riverside the app announces Aaron that the girl is showing some clues that she is getting bored and that he should finish the date there and just meet another day. Aaron follows its advice and they talk about meeting on weekend for a lunch in a new restaurant in the City Center.

### Aaron Requirements

- Recognize gestures on the others person face to know when is feeling comfortable/uncomfortable on a theme or in a place (other). 
- Show (Action) the information (Object) in a way that is not very intrusive because the one using it (Context) has to be able to follow the app info at the same time that is having a date with someone.

## Final list of requirements

###Josh
- Connect (Action) with wikipedia to show biographies or historical facts (objects) that are interesting to know for the user (context).
- Connect (Action) to every social network to subtract the personal information of the hobbies of the target girl (object) before the date (context).
- Connect (Action) to Google Maps (object) when requested by the user (context).
- Communicate (action) with the e-ContactLenses (object) in any moment in the date (context). 

###Helene
- Display (action) a box (object) to see all the previous relationships of the guy and see the comments of their ex-girlfriends beforehand (context).
- She wants to know if the guy is trustworthy, so the app has to notify(action) this information and the reasons(object) in advance(context). So Helene does not waste the time.
- The app should notify (Action) if the guy (object) is looking for a long term relationship during the date (context).
- The app has to analyze (action) the user gestures and face (object) and find if the guy is starting to fall in love (action) at every moment (context).
- It should search (action) for common hobbies(object) and propose new topics (action) to Helene in the screen when the conversation stacks (context).

###Aaron
- Recognize gestures on the others person face to know when is feeling comfortable/uncomfortable on a theme or in a place (other). 
- Show (Action) the information (Object) in a way that is not very intrusive because the one using it (Context) has to be able to follow the app info at the same time that is having a date with someone.
