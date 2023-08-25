# Trespassing Duck Shooter

I wanted this project to be part of a broader project to detect ducks who use my pool as a toilet and squirt them with a water cannon to scare them away. This project attemps to detect images of ducks. It used the resnet18 classification model. I got the images for ducks from an animals set on kaggle, and I got images for not_ducks from mini-imagenet on kaggle.

![duck](https://github.com/TacoDoge1/TrespassingDuckShooterRoughDraft/assets/142443743/f3464960-d0a6-4b14-89cf-10e3958cd975)

## The Algorithm

Unfortunately, after 4 project restarts, I still could not get my project to detect ducks. Every single image I run inference on leaves the algorithm sure that the image is not_duck. I could really use some help on why it only detects not_duck. Even if I use images from the train directory, which the model should guess 100% correct, it still thinks the ducks are not_duck.

## Running this project

Run this code in jetson-inference/python/training/classification : "imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/duck/02b336d12bc20674.jpg foo.jpg"

Video: https://youtu.be/ubU0MUPjXFA
