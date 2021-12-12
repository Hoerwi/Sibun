# Sibun - Build 2.0.2.2b
a Logic puzzle Game written in Livecode Community 9.6.3

Gameplay:

The goal is to raise all fields in a 5x5 grid to the score of 7.
For this you get a value between 1 and 4 which you have to place on the field.
This is offset against the existing value of the target field. 
If this value exceeds 7, the field is reset to 0. 
If the value is exactly 7, the field is highlighted in green and blocked for further setting.
The fields next to the field also receive a part of the set value as follows: 
1 = 0, 2 = 1, 3 = 2, 4 = 2
In addition to a 7-field can be set three times a value in which the neighboring fields, the values are increased. 
The status of the 7-field then changes from green to yellow to red. If a red 7-field is increased from a neighboring field, it is reset to 0. Only when all fields are at 7, the game is over.
The numbers 1 to 4 below the field are wild cards that can be used once each

New Game:
Set each field to 0

Random Game: 
Set each field to a random number between 1 and 5

