# Action-recognization-with-I3D
This  demonstrates recognizing actions in video data using the tfhub.dev/deepmind/i3d-kinetics-400/1 module.
The underlying model is described in the paper "Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset" by Joao Carreira and Andrew Zisserman. 
The paper was posted on arXiv in May 2017, and was published as a CVPR 2017 conference paper. The source code is publicly available on github.
"Quo Vadis" introduced a new architecture for video classification, the Inflated 3D Convnet or I3D.
This architecture achieved state-of-the-art results on the UCF101 and HMDB51 datasets from fine-tuning these models. 
I3D models pre-trained on Kinetics also placed first in the CVPR 2017 Charades challenge. 
The original module was trained on the kinetics-400 dateset and knows about 400 different actions.
Labels for these actions can be found in the label map file. we will use it recognize activites in videos from a UCF101 dataset. 
