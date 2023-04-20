## Binary classification of Rabbit and Squirrel

Used VGG1, VGG3, VGG3 with data augmentation and VGG16 with Transfer learning. Tested it on all the above models and made comparisons which one is faster and have a greater accuracy in classifying the images.

The directory where the images are there is dataset_Rabbit_vs_Squirrel. There are total of 200 images of Rabbits and Squirrel. In the test folder, there are 40 images and train 160 images.

# How to run ?


### CASE 1:-

If you want to make a new dataset of Rabbit and Squirrel. Then you have to run the following files in the following order:-

```
python3 DataGeneration.ipynb
python3 MakeDirectories.ipynb
python3 models.ipynb
```

### Case 2:-

Your dataset is already prepared in the directory dataset_Rabbit_vs_Squirrel. Then you can directly run the following file:-

```
python3 models.ipynb
```


# How to run tensorboard ? 
This step is common for both the cases.
Run tensor board in the same directory where you have the project initialized using the following command on terminal.
```
tensorboard --logdir logs    
```