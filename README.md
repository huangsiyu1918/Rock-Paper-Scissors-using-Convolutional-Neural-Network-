# Rock-Paper-Scissors-using-Convolutional-Neural-Network
<h5 align = "left"> :cloud:The dataset contains images of hand gestures from the Rock-Paper-Scissors game. The target is categorizing each hand gesture into three subjects (Rock/ Paper /Scissor). Based on the known information, all the images were taken on a green background with relatively consistent tones and white balance. In this competition, we have conducted experiments based on the given CNN model to achieve the best trade-of between performance and ef iciency. For example, the accuracy of the original model and parameters was around 98% with 1.14G Flops. We applied three tricks based on these data and achieved 100% accuracy with 0.29G Flops.</h5>

<p> The dataset contains a total of 2188 images corresponding to the 'Rock' (726 images), 'Paper' (710 images) and 'Scissors' (752 images) hand gestures of the Rock-Paper-Scissors game. All image are taken on a green background with relatively consistent ligithing and white balance.

All images are RGB images of 300 pixels wide by 200 pixels high in .png format. The images are separated in three sub-folders named 'rock', 'paper' and 'scissors' according to their respective class.</p>

![images Preview](https://github.com/yyywkhd/Rock-Paper-Scissors-using-Convolutional-Neural-Network-/tree/main/asset/images)

<p> Considered tricks </p>
1. Change of advanced training parameters
2. Use of a new loss function.
3. Data augmentation
   
<p> Based on the advanced training parameters, we mainly focus on those fields to improve the accuracy.</p>
* CNN Model
* Training Parameters
* Learning Rate
* Optimizer
* Batch Size
* Drop Out
* Network Structures

<p>Experimental results</p>
|Trick1|Trick2|Trick3|Accuracy
|   N  |   N  |	  N	 |89.2% |
|   Y  |   N  |	  N	 |97.55%|
|   Y  |   Y  |	  N	 |  77% |
|   Y  |   Y  |	  Y	 |  82% |


<h6 align = "center">This project is contributed by peiyan Chen and siyu Huang</h6>
