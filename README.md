# DeepLearning_MonkeyClassification

## Purpose
To identify a species of New World monkey. Possible species include: howlers, capuchins, tamarins, squirrel, saki, woolly, spider, marmosets, and night monkeys.

## Description
The train_model.ipynb notebook demonstrates the processes of training the model, fine tuning the model, and interpreting the results. I utilized a convolutional neural network and tried both Resnet34 and Resnet50 architectures implemented with the FastAI library. The final model is with Resnet50 and is 97% accurate. The final model weights are found in: root->models->monkey50-stage1. The images were collected from google images using the notebook get_data.ipynb.

## In progress
I hope to expand this project to include subspecies identification and individual monkey facial recognition.
