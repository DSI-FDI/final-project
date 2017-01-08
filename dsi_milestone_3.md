#Design Framework
##Plan and execution
As we were all in different places for this phase, we had to take a highly distributed approach to this milestone’s work. Furthermore, due to poor connection, most of the time videochat wasn’t even an option, so we had to work asynchronously as well.

##Form factor, posture and input methods
Since our app makes heavy use of Augmented Reality (AR), we decided that the form factor should cover the entire viewport, with high-resolution overlay elements that appear directly in the line of sight of the user. However, as will be detailed later, one of the users’ concerns was that the app would require too much attention and would gen in the way of their date. Therefore, we must strive to make the notifications and controls subtle.

Outside of a date, just before it starts, the app could have a **sovereign posture**, since the users wanted to know details about their dates beforehand, such as biography, goals and aspirations. Thus, it would be useful to display this dense information before the date starts, since it’s the time when the user will have the most urgent need for it. On the other hand, once in the date, the app should sit in the background and only notify the user when there is critical information, such as a dangerous topic approaching or a topic suggestion when the conversations runs out. Therefore, during the date, the app should adopt a **daemonic posture**.

Since the user will not be able to exercise much control over the application while in a date, the input methods will have to be indirect, such as hand gestures, head movements and voice commands. However, while in a date, the app has mainly a responsive functionality, which means that it will not require much input from the user.

##Catalog of data elements 
These elements have been extracted directly from the requriements.

1. Map
 * Track to follow.
 * Places to select.
 * Distance between your location and the target place.
2. Emotion
 * Colour (for each emotion). 
3. Social network widget
 * Profile picture.
 * Pages followed.
 * Interests.
 * Friends in common.
 * Former partners.
4. Online encyclopedia
 * Search bar.
 * Title of the information.
 * Well-organized information.
 * Index.
 * Related somehow with the social network widgets, because we shall be interested in searching the interests that we don’t understand about the other person.
5. Intermittent notifications box
 * Low intrusive appearance.
 * Easy to read.
 * Intermittent (it appears and disappears).

##Functional elements
###Josh:
- Connect (Action) with wikipedia to show biographies or historical facts (objects) that are interesting to know for the user (context).

  1. From our “main view” we can identify an wikipedia search bar showing the title in every moment of the subject that is relevant in that moment form the application point of view.
  2. Josh can see the information about the subject the application decides in any moment.
  3. When seeing the information Josh can select rapidly where to go in an index.

- Connect (Action) to every social network to extract the personal information of the hobbies of the target girl (object) before the date (context).

  1. When Josh starts walking to the date location, a notification will automatically shown in order to open the girl’s profile.
  2. We can open her profile whenever the notification is activated.
  3. When showing the profile Josh can select what to read and when to close it.

- Connect (Action) to Google Maps (object) when requested by the user (context).

  1. A map with your location will be shown in every moment in the “main view”.
  2. In every moment Josh is able to ask for going to different places. At the same time the application is suggesting locations whenever is important from the application point of view.
  3. When the places are found he can select one of them.
  4. A track will be shown whenever Josh selects a target place. Alternative paths can be taken by Josh.

###Aaron:
- Show (Action) the information (Object) in a way that is not very intrusive because the one using it (Context) has to be able to follow the app info at the same time that is having a date with someone.

  1. The “main window” is generally empty in the center and part of the sides.
  2. Notifications will only be shown when it is extremely advisable from the application’s point of view.
  3. Aaron can close any notification as soon he is uncomfortable with it.

###Helene:
- Display (action) a box (object) to see all the previous relationships of the guy and see the comments of their ex-girlfriends beforehand (context). It should search (action) for common hobbies(object) and propose new topics (action) to Helene in the screen when the conversation stalls(context).
 The same as the second functional element of Josh. It can also notify when to talk about some particular topic. (Notice that there are two functional elements in one)

- She wants to know if the guy is trustworthy, so the app has to notify(action) this information and the reasons(object) in advance(context), so Helene does not waste time. The app should notify (Action) if the guy (object) is looking for a long term relationship during the date (context).
 A notification will be shown just the same way as with Aaron. (Notice that there are two functional elements in one)

- The app has to analyze (action) the user gestures and face (object) and find out if the guy is starting to fall in love (action) during the date (context).

  1. We can see the emotional state of the other person permanently in the “main view”.

##Functional groups and hierarchy (first pass)
###Pre-date view
- There should be a field to search for the name of the date.
- Information of his/her social media profiles is displayed and browsable.
- A list of the previous partners of the date will also be available.
- A list of possible topics to talk about will be present.
- The information can obstruct the view (sovereign posture), since the user is not paying full attention to the date yet.

###In-date view (Main view)
- The central space is empty, to be occupied by the date (daemonic posture).
- There has to be a widget to display the emotional state of the date at all times.
- There has to be a space reserved for notifications about:
  - When the user is approaching dangerous topics.
  - When the conversation runs out, a suggestion of topics.
  - Whether the date is lying or not.
- The notifications should be easily closeable.
- There should be a search bar that responds to voice commands. The bar should follow the conversation, and when the user requests “more data”, the bar should already have a digested list of results. The result should not intrude with the central view of the date.

###Moving view
- There should be a search bar to search for places to go.
- There should be a map display, which contains the route to the selected location and suggestions for other locations to move to.

##Sketch of the Interaction Framework (first pass)
The sketches for the first pass of the interaction framework sketches can be found in the folder Prototypes/1st Iteration.

##Keypath scenarios (first pass)
With the initial sketches in hand, we created a series of keypath scenarios to demonstrate the main ways the user can interact with the app.

###Pre-date Keypath Scenario
Josh is having a date this afternoon but he wants to prepare before so he starts the app in the pre-date mode (in which the information occupies the whole screen) because he wants to look for some information about the girl.

So the app starts loading all the information about the girl that Josh is meeting today.
When the information is ready Josh observes that there are several tabs in which the info is organized (social networks, previous partners, hobbies).

He selects via voice command the social network tab (Saying “social network”) and then the Facebook tab (Saying “Facebook”)  in which he wants to see how is the girls relation with his parents because Josh thinks that a person that has problems with his family do also tend to have problems in any friendship or love relation. He finds that the girl do usually post photos with her family which he finds a good thing.

After a while surfing at the girl’s Facebook he wants to know more about the girl’s hobbies so he changes to that tab (Saying “Hobbies”). In it there is a list of the girl’s hobbies and he sees that the first of them is that she loves cats. He had suspected that when seeing her photos but now he is sure about it. The girl’s next hobby is playing basketball and the last two ones watching films and reading. Is then when Josh starts planning somehow some topics for the date and he feels prepared for it, but before meeting the girl he wants a last piece of information he wants to check the “previous partners” tab so he changes to it (Saying “previous partners”) and checks how their previous partners were. 

There are three guys and all of them look normal. He realises that all of them are 3 years older than the girl exactly as Josh and that gives him a boost of confidence feeling ready for the date.

###In-date Keypath Scenario
As soon as the date starts the application changes to a different mode, the “In date” mode in which the central space is empty and all the information needed during the date is moved to the sides.

First of all Josh wants to check how is his partner mood so he checks the icon in the right-top corner that shows how it is going. He sees that as the date has just started the app shows his partner mood to be normal(green color) not excited nor bored or angry.
So Josh looks at the right bottom corner where the topic suggestions appear and decides to talk about cats cause the lady he is dating seems to be a cat lover. The problem is that Josh doesn’t know many things about cats and he wants something interesting to tell to the girl about that topic and he decides to search some information in the searching dialog that is on the left top corner using voice commands. He just look for “cat curious information” and he checks quickly the answers until he finds one that may fit his purpose of impressing the girl.
The problem is that after a while talking about cats the icon showing the mood of Josh partner starts to turn yellow (meaning uncomfortable) and a notification appears on the notification’s box telling Josh that he should change the topic of the conversation because the girl is starting to feel uncomfortable so he checks again the list of topics and chooses a different one.

He chooses this time to talk about sports and the move to basketball a well known sport for him and of which is also fan his partner.

After a while talking about sports and basketball the mood indicator of the screen turns to normal (green color) meaning that the girl is feeling comfortable again.

The problem is that is getting late and Josh needs to go because has to work early on the next day and they decide to meet another day cause they both felt quite comfortable with each other.

###Moving Keypath Scenario
Josh and the girl talk about moving to a different place, she would like to go to a quiet park so Josh via voice command (Saying “Go to a park”) and the app scans the area to search the nearby parks. Then Josh selects one of them (using gestures) from the list of possibilities that the app has found.

As soon as he selects it, the route to the park is loaded in the app and it starts giving him information about how to get to the park as a normal GPS for the car does.

So they both Josh and the girl start the route and they keep with the conversation they were having. Josh realises that the app information about the route is shown in a very subtle way what he finds a very good idea because he wants to focus his attention on the girl and prefers the app not to be very intrusive. The next step of the route they are following is just shown with a little message below the map.

After a while walking and talking they get to the park and the map starts just showing Josh position.

##Validation scenarios (first pass)
We decided not to do any validation scenario as we found them not very useful in our app. 

This step is usually thought to find some flaws in the design of very complex apps in terms of controls or having too many different views. It is also used to find missing functionalities that were thought but that never reached to the sketches so they aren’t missing in the final product.

Our app do have just a few functionalities and screens and our main focus is how to not to be very intrusive for the user at the same time we give enough information in a subtle way.

##First Iteration Takeaways
After discussing the prototypes and keypath scenarios, we distilled a list of changes that we wanted the next iteration to have.
###Pre-date view:
- The first thing that should appear is a sort of cover with the tastes of the date, similar to the one in Daniel’s prototype.
- The size and organization of the tabs will follow Borja’s prototype, except that the active tab will be brighter, and the inactive ones will be darker.
- The search bar was identical in both prototypes, so it should remain unchanged.
- The social networks will not be individually filterable, and instead a digest will appear, containing unified information of each of them.
- The “Iterests” tab will contain information about the last posts made, followed pages and personalities, common acquaitances and former partners.

###In-date view:
- The map will not be present.
- The search bar will be on the top-left side, and will display information with pictures taken from Wikipedia or other sources. Two examples are provided, being the second one better for our app:

#Imagenes
- The notification box will be located following Daniel’s prototype with the same size. In the lower part of that same side, there will be a circle with a color that matches the emotional state of the date. Somewhere around that element (not yet decided), there will be a heart bar, similar to that in Borja’s prototype, which aims to know the level of likeness that the other person has for the user.

###Moving View
- Will be similar to In-date view, but in this case the map will be located where the search bar was (top-left), and just below that a text will appear with indications to reach the destination, such as “In 200m, turn left”.
