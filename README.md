# Bus-Mall
A skymall-similar website for busses

Pair programming with Emery, scaffolding our JS

(typed up notes from notebook)
Hypothesis of what I want to do:
1. Display three unique images simultaneously
2. Create a click event so that when one of the images is clicked it 
  a. throws in an entirely new set (array) of 3 images (not one image can be the same as the previous array of images)
  b. we want to count the number of times one of our image instances occurred (so counting our image array indexes)
  c. we want to count the number of times a particular index of an instance was clicked

What do we want each time an instance iterates in our 'while' loop?
1. generate 3 random nums that we will assign (outside our loop) to the src and filepaths of our 3 imgs within our objects array
2. count the number of times an image (random number index) occurs

How do we count the number of occurrences of each randNum?
- set up an array that contains the name 
