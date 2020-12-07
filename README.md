# AI4Dev-Lab

Data and code release for Zakaria Sawadogo, Wendkuuni A. M. Christian Ouedraogo, Aminata Sabané,			         
Idriss T. Tinto and Tegawendé F. Bissyandé, "An explorative Investigation into Neural Machine Translation:    
the Case of Low-Resource Language Pairs in Burkina Faso"													                             


# Dataset
The French-Moorée Bible


# The dataset presentation 

train_data represents the training data pre-processed (27,909 lines)

valid_data represents the validation data pre-processed (597 lines)

test_data represents the pre-processed test data

bpe_data represents the vocabulary generated with the BPE used during the training phase with OpenNMT-py

align_data represents the data alignment model generated with fast_align used during the training phase with OpenNMT-py



# Tools used

OpenNMT-py the framework for training and testing https://github.com/OpenNMT/OpenNMT-py

subword-nmt for the BPE https://github.com/rsennrich/subword-nmt

fast_align for word alignment https://github.com/clab/fast_align
