# Pokemon

Trying to train Pokemon images of Generation one on a VGG16 model for practising the concepts learnt in Deep Learning.
<br><br>

Dataset: https://www.kaggle.com/thedagger/pokemon-generation-one
<br><br>

First I tried to train the entire dataset of 10644 images which contains 149 classes of Pokemons on Colab but the accuracy I got was very bad due to computational reasons. Increasing the batch size would improve the results but it exceeds Colabs RAM so that cant be done.
<br>
Here are the results - https://github.com/aayushkothari11/Pokemon/blob/master/pokemon.ipynb
<br><br>

Then I tried to run the same model on a much smaller dataset consisting of only 5 classes and got a Training and Test accuracy above 90%.
<br>
Here are the results - https://github.com/aayushkothari11/Pokemon/blob/master/Pokemon_small.ipynb
<br><br>

Then I tried Transfer Learning on VGG16 model pretrained on imagenet dataset and the results are - 
<br>
With the entire datase - https://github.com/aayushkothari11/Pokemon/blob/master/pokemon_transferLearning.ipynb
<br>
With only 5 classes - https://github.com/aayushkothari11/Pokemon/blob/master/pokemon_transferLearning_small.ipynb
<br><br>
Well in this case I trained on only 10 epochs because I was bored by all the waiting. Training for more epochs can increase the accuracy(I hope so).

<br><br>
If anyone has any idea about how to increase the accuracy then help this rookie out.
