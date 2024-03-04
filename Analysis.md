1. Strength
It has a double the accuracy than a random guess.
2. Weakness
The model has low accuracy, and high loss. There is gap between predicted outputs and expected outputs.Might be over fitting due to discrepency in accuracy between 
3. Process of data sets.
I realised that there was large under representation and imbalance in the dataset, with there being extremely little textArea images in the dataset but an over representation of h3, button, h2 and a tags.
I attempted to overssample the under represented classes to overcome this.  I split the data into a 7-1.5-1.5 train test validate split. I also rescaled picture pixel values from 1 - 255 to betweeen 0 and 1.
4.  Because of how little there were of some classes especially textArea, there was extreme over sampling that might have led to over fitting.
5. Future modifications
I would try to fine tune Hyperparameters such as the learning rate or number of epochs. I would also attempt to introduce.  I would use Synthetic Data Generation to create new, synthetic instances of the minority class by interpolating between existing instances for under represented classes. A principle component analysis could also be done to reduce dimensionality of the dataset, so that the model could train faster