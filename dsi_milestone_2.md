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
