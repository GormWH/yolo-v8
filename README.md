# Two Shot Generator using YOLOv8

## Background

Using YOLOv8, I made a simple program that merges a character image in to a picture of a person.  
First, I tested the program with jupyter notebook.  
I managed to get results of what I wanted, but I needed many more outputs to determine some parameters.  

"two_shot_generator.py" is literally a program that generates two-shot images.  
It's just a more organized and efficient version of the jupyter notebook.

## Program flow

1. Load the character image and the person image.
2. Detect both character's face and person's face using YOLOv8.
3. Resize the character image to fit the person's face.
4. Merge the character image into the person image.