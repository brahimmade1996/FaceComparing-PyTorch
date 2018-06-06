# FaceComparing-PyTorch
For my final year project, I did a little project about Face Comparing.
All the codes are based on PyTorch 0.3.1. And it needs to be modified if u want to run it under the newest 0.4.0(launched in late April).
I used 2 metric learning algorithms(Siamese CNN and Triplet CNN).
## Online Triplet Mining
As the Triplet CNN model is hard to converge by randomly choosing the triplets, I wrote 3 different ways to do the mining(Batch-all,batch-hard and batch semi-hard). However, codes of this online triplet mining part might be dirty and inefficient as I'm quite new to Python and PyTorch.
