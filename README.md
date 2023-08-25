# Trespassing Duck Shooter

This project attemps to detect images of ducks. It used the resnet18 classification model. I got the images for ducks from an animals set on kaggle and non ducks from mini-imagenet on kaggle.

![duck](https://github.com/TacoDoge1/TrespassingDuckShooterRoughDraft/assets/142443743/f3464960-d0a6-4b14-89cf-10e3958cd975)

## The Algorithm

Despite 4 project restarts, it does not work. Every single image leaves the algoritm sure that the image is not a duck.

## Running this project

Run this code in jetson-inference/python/training/classification : "imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/duck/02b336d12bc20674.jpg foo.jpg"

Video: https://youtu.be/ubU0MUPjXFA
