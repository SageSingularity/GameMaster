# GameMaster

## Summary

## Syllabus
* [Python Exercises (CodeCademy)](https://www.codecademy.com/learn/learn-python)
* Combat Tracker
  * Dice Roll
* Database storage and access of open source RPG information ([sqlite?](https://www.sqlite.org/about.html))
* Search feature for finding relevant information (For example, "Orc Rogue" search term)
* [xml storage](https://www.w3schools.com/xml/default.asp) of frequently used data, such as character health/magic/name, and maps
* Create class for characters
  * Think about the word "Human" and how it relates to you; in Python, the class will serve the same function for characters. It's a "Template" to build off of for every player character.
  * The class itself will have variables that will be loaded from the `xml` storage file. This way when you "start" the game, the characters will be loaded automatically. (You can use a single `xml` file per character to allow for using them in different campeigns/parties).
* Create class for handling a map
  * A map class can behave much the same way as the character class, where `xml` files are able to store the condition and parameters of a map and can store a parties progression through the map.
  * Inside the `xml` file, you can specify which room a party will enter once they "leave" the current room, and then load that room.
