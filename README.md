This Project is a Novel Manager App project.
Author: LDKTC 

Novel Manager App is an App for Story Management, like Story, Timelines, Characters, relations of characters, and Events.
Built with Electron and SQLite.
Important note: on version 1.2.0, there will be only Thai Text in the Application.
Dev plan 1.3.0: will update settings for others language, e.g., English, Japanese, and Korean.

Dev Objective: I am a writer who has 100+ stories to write down in a novel, game, etc.
With that many of infomation, I use many apps for notes, but still confusing in infomation that I have in many apps.
But all the apps in the market I have tried, there are not useful for my objective.
So I created this app for Personal use and for any person who has the same problem as me.
The app is used to memo the character identity, like power, clan, signature, and everything, as custom depending on the story. 
Many apps I try had the same problem; if there were no paid limits, then there wouldn't be enough functions to use.
These apps have a custom Category template to create anything in the story you want, like Character, Monster, Item, Artifact, Clan, etc.
On Timeline, you can use it as the Story Main Timeline and multiverse, or as a Chapter you plan to write.
And in relation, you can use it to mark the relationship between objects you create to show how they have a relation.
, for example, Char A is in love with Char B, or Char A owns Item C at the moment.

```text
App Function List
  -Project,
  -Project Folder,
  -Category,
  -Category Template,
  -Object,
  -Object View,
  -Timeline,
  -Event,
  -Relation,
  -Relation Type,
  -Relation Graph,
  -Map,
  -Area,
  -Tag,
  -Color Tag,
  -Search,
  -Import DB,
  -Export DB
```
```
    -Project
  Create a project, click on the plus symbol on the header of the project list
  Use to contain the story of a novel, DnD, Game, or anything you want
```

```
    -Project Folder
  Create a folder, click on the folder symbol to the side of the plus symbol
  Folder, used to contain projects such as categories like fantasy, isekai, romance
  Will show the project you assign under the folder
```

```
    -Category
  Create a category in the project page, at the top of the main area. There will be a Category Button
  Use to create categories like character, item, clan, skill, etc.
```

```
    -Category Template
  Manage your template, click on the Manage field button beside the Object create button.
  There will be 3 types of attributes to create
    -text, text with one sentence or less.
    -number, can only write the number in the box.
    -text area, Get memo for the long note or story about that object.
```

```
    -Object
  Create an object, after creating a category, there will be an Add Button show up in the category you selected
  After creating an object inside the description page, all the attributes that you create in the template should show in the box.
```
```
    -Object View
  In the 1.2.0 version, there will be two view styles for objects
    -list view, the original view that will show the list of all objects in the category you selected
    -table view, shows all the objects and attributes inside as a table, you can manage what you want to show or hide by using the button at the top of the table
```
```
    -Timeline
  Create Timeline, when you open your timeline page after opening a project, there will be the same button as on the project page
  After creating the timeline, nothing would show because you haven't created any events yet.
```
```
    -Event
  After creating a timeline, there would be a button to create an event at the top right corner of the main area.
  An event is used to mark a time at which the event happened; there will be two sets of dates in detail: Start and End. End is optional.
  There, you can type 0 in hours and min if you don't want to make too small a detail.
  And in date dd/mm/yy, you can type a custom number, like for a scifi novel, such as day 44, month 15 
  I have to modify this function for more convenient use later.
```
```
    -Relation
  A relation is a function to turn a spider web into an easy graph to view
  There will be a button at the top left corner of the main area to create a relation
  relation in any object will show up in the description of the object on the project page, too
```
```
    -Relation type
  Create a relation type, use the same button at the top of the left panel
  This function is used to create a relation type that has duplicate use with many objects.
```
```
    -Relation graph
  The function shows the object and all the relations between all of them
  There are 3 views available for the graph now
    -Category view, to show all objects and relations between them in the category
    -Object view, The selected objects are shown with the relation it had with all other objects
    -Project view, Show all objects in that project, and Show the relation between them
```
```
    -Map
  Create a map, use the same button in the left panel
  The map function is on developing and still has bugs and malfunctions
  A map is used to create a sheet of the area you want to show
```
```
    -Area
  Create Area, using the button under the map graph that shows up
  You must select the area first to use the map tool
  There are 3 tools available
    -Create, make a dot for the area, if there are 3 dots, or move the area will be created using that dot
    -Erase, delete a dot from that area
    -Move, move a dot that was on the map *This function is still not working properly.
```
```
    -Tag
  Create a tag, use for search by menu
  There will be more about the tag.
```
```
    -Color Tag
  At the bottom of the menu panel, there is a color page button used to create a color
  Use to customize your workspace
```
```
    -Search
  The search function is on the top of the left panel,
  You can search for the name of the project, object, category, or tag, and the item that relates to your search will show up
```
```
    -Import DB & Export DB
  Function used to back up and import the App DB in case of moving to another device or sharing with others
  I will add the function that allows exporting only the selected project in the future 
```

> Update Plan & notice
```
  I will give all the code for free until version 2.x.0
  In version 1.x.0, I will focus on the novel manager function and how flexible to use the app, 
  and after version 2, I am going to expand the novel manager by creating a World manager,
  a manager that connects all the story Projects in the same world or multiverse setting into one world project that will help me write down the connected story.
```
