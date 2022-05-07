Dataset - https://www.kaggle.com/mfekadu/darpa-timit-acousticphonetic-continuous-speech (630 speakers)

Paper - https://arxiv.org/abs/1710.10467

We have taken a speaker verification model from the internet to implement the GE2E loss function. 

In file GE2E_Voice_AI.ipynb, we have implemented the loss function proposed in the paper. Our implementation makes used of the softmax loss (other is contrast loss) from the paper.
This was trained using a subset of TIMIT dataset which cosisted around 141 speakers.

Here, we have implemented it for 10 epoches, we can see that the loss fluctuating but is indeed decreasing.

We encountered a problem in our testing function in this file

Therefore, we had used a readymade test function for along a training function which we used to train for 250 epoches on a larger TIMIT dataset with 630 speakers.
On this dataset, 10% data, i.e. 63 speaker's data was used for testing where we got an EER of around 16%

