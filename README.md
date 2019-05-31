# Project 4 Generative Visual

Megan Visaya, mvisaya@ucsd.edu

## Abstract

Ice hockey is objectively the Whitest Sport among those which are associated with one of the Big Four professional athletic
leagues in the United States (i.e., the NHL, the NFL, the NBA, and MLB). I took on this project to comment on how our understanding of 
what hockey players (or CEOs, or presidents, or criminals) look like is shaped by "typical" representation, which in turn is 
informed by histories of violence, systematic marginalization, and imbalances of power. The homogeneity of the images output by the 
machine emphasizes the absence of racial diversity in a sports league that was integrated as recently as 1958 (making it the last of the 
Big Four to do so), and that still only has around 30 Black athletes across 31 teams as of the 2014-2015 season. I invite my audience to 
reflect on what makes the sport inaccessible, and how these factors added onto the already notable lack of players of color can create 
or intensify an intolerant and white patriarchal culture among both fans and athletes.  

That being said, #GoSharks.

I used a face generating GAN in which a generator learns to create images that look like faces from a discriminator, which is able to 
discern between what is and is not a face. I trained the model on the dataset I created by scraping player photos from twenty years' 
worth of NHL rosters. The github repository that provided a basis for my model is included in my references.


## Model/Data

Included in this repository are the Python notebooks for training the model and producing an output (MrHockey.ipynb) as well as generating the dataset and the dataset itself (ECE198_Project4_DataCollection.ipynb, nhlroster_urls.txt, nhl_images.zip). 

## Code

As above.

## Results

Example outputs are included in the Example folder, taken after around 15-20 epochs of training.

## Technical Notes

Necessary modules are listed in the Setup block at the top of the model notebook, and can be installed using pip.

## Reference

Face generating GAN: https://github.com/zackthoutt/face-generation-gan
