# boardgame-searching-tool

The main product of this repo is boardgame searching tool that users can find boardgames that they want.
Searching keywords include: Age, game categories, number of players, playing time and rating of games.
Also, analysis of top 1000 ranking games is included. This analysis is based on the game ranking on Aug 10, 2021.
(BGG ranking is updated on every mondy. Current ranking may differ from this analysis.)
Dataset for this tool is acquired from BoardGameGeek website which is large database for the boardgame.


![image](bgg_tool.jpg)
![image](analysis.png)

## Technologies
-xml API

-Python

-Excel

-Tableau

## Process
![image](process.png)

## Difficulties
-Using xml format API was challenge part in this project. 'xml.etree.ElementTree' module solve this problem for this project.

(Fun fact) There was bug on website on August 9. All the numbers on ranking page went n/a so couldn't get the data and delay the process.
