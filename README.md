# Age of Villagers 

We need to build part of a game named _Age of Villagers (AoV)_. The game is about people from different parts of the world trying to build their villages. The game has a lot of features, of which you need to focus only on the village creation part. Therefore all the user stories are assumed to be of a _village editor_ user role.

A village can have several types of objects like _house_, _tree_ and _water source_. There are also several nations available. Based on the nation, the objects may look different. For example, the house of the Inuits can be an igloo, whereas the house of the Bedouin can be a tent.


### Constraints of implementation
*As a village editor, we want to place the following items in a village:*
1. House
2. Tree
3. Water source

We want the following steps when placing an item:
1. Select a type of item from a radio button on the side pane
2. Click on a location on the village
3. Draw the selected item at that location
4. Repeatedly click on different locations to place items of the selected type

We want the size of the items to be as below:
1. House: 16px by 16px
2. Tree: 16px by 24px
3. Water source: varies based on the nation

We want the shape of the items to vary based on the nation. Please check individual nation details for the shapes of the items.

*As a village editor, I want to open a village that was previously saved.*

#### Notes
1. The village can be edited after it is opened.
2. When a village is being opened, I would like to choose a nation for which the village will be drawn.

**As a village editor, I want to save the current state of a village so that I can open it later.**

#### Notes
The village should be saved in a `.aov` file. You are free to save in any format.

*As a village editor, I want to create a new village.*

#### Notes
* When creating a new village,  I want a 600px x 400px drawing space to be available.
* If there is anything already on the drawing space, it should be cleared.
* I want to be able to give my village a name.
* The village editor window should look like below: 
![Picture1](https://user-images.githubusercontent.com/1958088/88481975-49d9de80-cf80-11ea-8c36-064f670fd2bd.png)


## _Inuit Hunters_
1. The house is an igloo and looks line below:![image](https://user-images.githubusercontent.com/1958088/87903150-2644fe80-ca7d-11ea-9841-16695cfcb8d5.png)
2. Relies on natural water sources so it is not possible to place water sources.
3. Also cannot plant trees.
4. The terrain should be pure white.
5. The shapes should resemble as shown above, but do not have to be exactly the same.


## _Egyptian Kings_
1. The house, tree and water source looks as follows:
![image](https://user-images.githubusercontent.com/1958088/87902813-622b9400-ca7c-11ea-8c3e-93268dd4c3f7.png)

2. They did not live in the pyramids, but it is a well-known symbol of ancient Egypt!
3. The water source is a well and it should be 12px by 12px.
4. The terrain should be a plain yellow colour.
5. The shapes should resemble as shown above, but do not have to be exactly the same.


## _Arab Bedouin_
1. The house and tree look as follows:
![image](https://user-images.githubusercontent.com/1958088/87860849-99a61d80-c962-11ea-8384-cf16b7d92dce.png)
2. Bedouin villages do not build their own water source, therefore, the water sources should disappear for Bedouin villages.
3. The terrain should be a yellowish colour.
4. The shapes should resemble as shown above, but do not have to be exactly the same.


## _Bangladeshi Farmers_
1. The house, tree and water source looks as follows:
![image](https://user-images.githubusercontent.com/1958088/87860624-ab86c100-c960-11ea-857d-9d2efeb92cd4.png)
2. The water source is a pond and it should be 24px by 16px.
3. the terrain should be a plain green colour.
4. The shapes should resemble as shown above, but do not have to be exactly the same.

## Details


