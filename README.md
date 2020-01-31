# BERT-SIDE

Please note that this is research code. It is not optimized, slow, not very clean, and not well documented. 

This work is an improvement of the RESIDE model proposed by [Vashishth et al. (2019)](https://www.aclweb.org/anthology/D18-1157/). Any further coding details about baseline works applied in our work please refer to baselines code in [RESIDE github page](https://github.com/malllabiisc/RESIDE/)

![](https://github.com/guardiaum/BERT-SIDE/blob/master/images/bert-side_architecture.jpg)*Overview of BERT-SIDE (proposed method): A distantly-supervised relation extraction method that uses the BERT approach aggregated to a side information mechanism to improve the performance of the RE task. We replaced the **Syntactic Sentence Encoding** module of RESIDE [Vashishth et al. (2019)](https://www.aclweb.org/anthology/D18-1157/) by  using  sentence  representation  obtained  from BERT.*


### Before proceeding download experiments data available at:

- [DATA](https://drive.google.com/file/d/1LIeKCjnrBWIS0rOw2sfcUn349qmW_8Q-/view?usp=sharing): place it into the folder `data/`. 
- [PRE-TRAINED MODELS](https://drive.google.com/file/d/17Fex2HIEq-55gPzHg4vLn20R9u27r5SH/view?usp=sharing): place it into the folder `models/`. 
- [PAPER RESULTS](https://drive.google.com/file/d/1LUk6Fsi01mrs8OO4A0s6iq_jLtuG0vrV/view?usp=sharing): place it into the folder `results/`. 

### Dependencies

* Tensorflow 2.x, Python 3.x, hyperas, hyperopt and sklearn
* Install other dependencies using `requirements.txt`