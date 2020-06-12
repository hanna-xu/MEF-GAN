# MEF-GAN
This is the code for multi-exposure image fusion via generative adversarial networks

## Architecture:<br>
<div align=center><img src="https://github.com/hanna-xu/MEF-GAN/blob/master/imgs/Architecture.png" width="740" height="320"/></div><br>

## Fused results:<br>
<div align=center><img src="https://github.com/hanna-xu/MEF-GAN/blob/master/imgs/results.png" width="700" height="390"/></div>

## To train:<br>
CUDA_VISIBLE_DEVICES=0,1 python main.py (2 GPUs are needed. One is for the self-attention block and the other one is for other blocks and the discriminator.)<br>

## To test:<br>
CUDA_VISIBLE_DEVICES=0,1 python test_main.py<br>

## Tips:<br>
Large files should be downloaded separately, including the following files: <br>
#### For training:<br>
* [Training dataset](https://pan.baidu.com/s/18hQyGNlhVb3oXAXOJ5LZCQ)<br>
The code to create your own training dataset can be found [*here*](https://github.com/hanna-xu/utils).
The multi-exposure image pairs can be downloaded [*here*](https://github.com/csjcai/SICE). 

#### For testing:<br>
* [Trained model](https://pan.baidu.com/s/1zH6DC0N78Mw2jvPRB2I6HA)<br>

If you have any question, please email to me (xu_han@whu.edu.cn).

