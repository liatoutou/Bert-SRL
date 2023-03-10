# Bert-SRL
Code for finetuning pretrained BERT for SRL task and making predicitons

## Running instructions for train.py

1. Install required libraries: 

>pip install -r requirements.txt

2.In the terminal :

>python train.py --epochs int --batch_size int --learning_rate float
example:
>python train.py --epochs 2 --batch_size 4 --learning_rate 1e-4

## Running instructions for predict.py

1.If you haven't already installed the rwquired libraries:
>pip install -r requirements.txt

2.In the terminal :

>python predict.py  --batch_size int 
example:
>python predict.py  --batch_size 4 
