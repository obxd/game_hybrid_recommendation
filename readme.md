# Steam Games Hybrid Recommender System
A simple hybrid recommender system based on combination of Content-based filtering with Collaborative Filtering from datasets of the Steam userbase.

## __Data__
Two datasets were used in the making of this recommender system. 
* [kaggle Steam Games Dataset](https://www.kaggle.com/nikdavis/steam-store-games) which contain info about the games. 
* [kaggle Steam Games rating Dataset](https://www.kaggle.com/tamber/steam-video-games).wich contain ratings in the form of hours played by a user per game.

## __Front End__
simple web front-end with flask.

## To Run
0. Clone the repository.
1. Install requirments
2. Download datasets into data/dataset1 and data/dataset2 (steam-200k.csv into dataset2 and the others into dataset1)
3. Run ./game\_recomindation
