# Project 4 Generative Visual

Megan Visaya, mvisaya@ucsd.edu

## Abstract

Ice hockey is, arguably, the Whitest Sport among those which are associated with one of the Big Four professional athletic
leagues in the United States (i.e., the NHL, the NFL, the NBA, and MLB). I took on this project to highlight the lack of
ethnic diversity in a sports league that was only integrated in 1958 (making it the last of the Big Four to do so), and that
still only has around 30 Black athletes across 31 teams as of the 2014-2015 season. I invite my audience to reflect on 
what makes the sport inaccessible, and how these factors added onto the already notable lack of players of
color can create or intensify an intolerant and white, patriarchal culture among both fans and athletes.  

That being said, #GoSharks.

I used a face generating GAN in which a generator creates images and is trained to generate faces based off of responses from a 
discriminator, which is able to discriminate between what is not and is not a face. I trained the model on the dataset I created
by scraping player photos from twenty years' worth of NHL player rosters. The github repository that provided a basis for my model is
included in my references.


## Model/Data

Briefly describe the files that are included with your repository:
- trained models
- training data (or link to training data)

## Code

Your code for generating your project:
- Python: generative_code.py
- Jupyter notebooks: generative_code.ipynb

## Results

Documentation of your results in an appropriate format, both links to files and a brief description of their contents:
- image files (`.jpg`, `.png` or whatever else is appropriate)
- move files (uploaded to youtube or vimeo due to github file size limits)
- ... some other form

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- Does this code require other pip packages, software, etc?
- Does it run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

Face generating GAN: https://github.com/zackthoutt/face-generation-gan
