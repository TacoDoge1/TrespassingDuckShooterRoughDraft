# Trespassing Duck Shooter

This project attemps to detect ducks

![duck](https://github.com/TacoDoge1/TrespassingDuckShooterRoughDraft/assets/142443743/f3464960-d0a6-4b14-89cf-10e3958cd975)

## The Algorithm

Although it doesnt work despite 4 project restarts, it does not work. Every single image leaves the algoritm sure that the image is not a duck.

## Running this project

1. run this code in jetson-inference/python/training/classification : "imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/duck/02b336d12bc20674.jpg foo.jpg"
2. I used mini-imagenet on kaggle to train this model.

Video: https://youtu.be/ubU0MUPjXFA
