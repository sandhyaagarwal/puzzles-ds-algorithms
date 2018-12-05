### Prisoner hats puzzle

#### Description

There are 3 white hats and 2 black hats with the warden. There are 3 prisoners in line, the first one facing the remaining 2, the second one facing the third prisoner and the last one facing the wall. Each prisoner is given a hat. Following are the conditions :

* A prisoner cannot see the hat he is wearing
* The first prisoner can see the hats worn by the 2 prisoners in front of him
* The second prisoner can see the hat worn by the 3rd prisoner in front
* When the first prisoner was asked the colour of his hat, he did not know
* When the second prisoner was asked guess the colour of his hat, he did not know
* The third prisoner knows that the colour of his hat is "white"

The third prisoner is right. The puzzle is to figure out how the third prisoner got that right ?

#### Solution

Let us backtrack and deduce.
Had the first prisoner seen 2 black hats in front of him, he would immediately know that his hat colour is white, as there are only 2 black hats. But, when asked, the first prisoner responded that he did not know the colour of his hat, which implies that the first prisoner is seeing a black and a white hat or 2 white hats, in front of him.
If the third prisoner was wearing a "black" hat, then the second prisoner would know immediately that the colour of his hat is white, based on the first prisoner's dilemma about the colour of his hat. But, given that the second prisoner too did not know the colour of his hat, it means that the second prisoner is seeing a white hat. 
Given the first and second prisoner's dilemma about the colour of their hats, the third prisoner correctly concluded that the colour of his hat can only be white, otherwise the first and second prisoners would not be unsure about the colour of their hats. 
