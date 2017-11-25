# Blurb:

This is a state of the art object detection framework called Faster R-CNN described here https://arxiv.org/abs/1506.01497 using tensorflow.  Here is my website http://deepython.com if you want to see other projects!

I took the following video and fed it through Tensorflow Faster R-CNN model, this isn't running on an embedded device yet. 


# Youtube DEMO:

https://www.youtube.com/watch?v=ERglPgx8wFg

[![Demo](./demo.png?raw=true)](https://www.youtube.com/watch?v=ERglPgx8wFg&feature=youtu.be)

Backup mp4 if above video goes down: 
machinesentience.com/videos/Computer_Vision_Systems_Walk_Through_Times_Square.mp4


Source Video without classifications: https://www.youtube.com/watch?v=u68EWmtKZw0

Backup mp4 if above video goes down: machinesentience.com/videos/Walking_tour_of_Times_Square_in_Midtown_Manhattan_New_York_City.mp4



# Whitepaper

Whitepaper Link: https://arxiv.org/pdf/1506.01497.pdf

Whitepaper Local Backup Link: <a href="./Faster_R_CNN_Towards_Real_Time_Object_Detection_with_Region_Proposal_Networks.pdf">./Faster_R_CNN_Towards_Real_Time_Object_Detection_with_Region_Proposal_Networks.pdf</a>

# Author's linkedin, github, website:

https://www.linkedin.com/in/claytonblythe/

https://github.com/claytonblythe/

http://deepython.com/

Snapshot: 
<a href="./deepython.pdf">./deepython.pdf</a>

# Strengths

Flawless and sub-pixel perfect box overlays around correctly classified objects such as cars and people.

# Weaknesses and Blemishes on near perfection: 

1.  At 0.02 it identifies a traffic cone as a fire hydrant. 

2.  At 0:16 it identifies that woman as a horse.  Confusing two people next to each other as a single animal.

3.  A man is holding some kind of greyish oval object which is classified as a frisbee, is not a frisbee. 

# How many frames per second using the tuned model

5 frames per second using a desktop with a GPU.

# Undergirding code: 

Matlab: 
https://github.com/sentientmachine/faster_rcnn

Python:
https://github.com/sentientmachine/py-faster-rcnn


