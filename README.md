# 🐦‍⬛Bird vs 🚁Drone classification Convolutional NCural Network⚛️

Being inspired buy building custom digit recognition nerural network, I thought that it would be cool to make it one step further and build a custom CNN. Objective stays the same – understand how it works under the hood!

# Dataset 📊
The dataset containes images of drones and birds in separate folders and can be found here (kaggle): [dataset](https://www.kaggle.com/datasets/harshwalia/birds-vs-drone-dataset)
Get them and add the two folder to, in my case, another folder called 'drone_or_bird'

# How it works 🧠
1. First and formost, we have to process the images into a csv file. We will resize them to 128x128, storing all 3 RGB colour channels and labeling all with 0 for bird and 1 for drone. Total length of 1 raw will be 128*128*3+1=49153

2. The structure of CNN
I used 3 convolutional, 3 pooling and 2 fully connected layers

3. I wrote some code to view how NN trains over time per epoch and over all epoches

# Results of training
7th epoch
![image_progress_epoch_1](https://github.com/user-attachments/assets/89fffce9-584e-4fe0-82ff-5522203fab7a)

I am also working on Medium article for this one in details, once it is dones, the link will be here: <...>
