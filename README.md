# Democrat or Republican

Can the political party of a congress members be identified by their photo?

## Why 
This was part of my homework for Part 1 of fast.ai's Deep Learning Course. It required searching for a new dataset to train an image classifier on. I was curious if a model could learn to determine a congress members party by their photo. So, I pieced together code to scrape images and tried to build a learner...


## Results
...it didn't work. 

## Why did it fail?

Might have to do with the shifting platform of each party across time. The consistency of the data might be improved by only looking at images of members from certain decades. 

Also, some members later changed parties or left the party they're listed under on the congress.gov site. This information was not always reflected there. Improvements might be made by treating the problem as a multiclass problem. 

## Ideas for future direction
Exploring these methods:
https://osf.io/zn79k/

