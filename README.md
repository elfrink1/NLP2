# Probing Language Models

Dear Jaap,

I included a requirements.txt file. That file does not include Torch.

As I am still a Windows noob, my steps for guaranteed success in being able to run everything properly is:

0. Have Anaconda installed
1. Create a new environment (Python 3.7.10)
2. pip install -r requirements.txt
3. pip install torch==1.8.1+cu102 torchvision==0.9.1+cu102 torchaudio===0.8.1 -f https://download.pytorch.org/whl/torch_stable.html

I made the notebook so that it runs from top to bottom, and trains on the GPU by default (but that can be toggled). However, in two cells (one for the PoS-probe, one for the structural probe), example code is commented. This functions as an example for you in how different experiments could be run. If you don't change anything in the notebook and just run it, no experiments will be conducted (the models will just be loaded and tested).

Hope you enjoy!
