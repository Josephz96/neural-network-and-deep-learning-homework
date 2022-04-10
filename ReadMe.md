## The first assginment of neural network and deep learning 
**file structure**  
.  
* __init__.py  
* parameter——search.py  
* train.py  
* model_param  
    * joseph_module_param.npy  
* plot_image.py  
* __pycache__  
    * plot_image.cpython-39.pyc  
* ReadMe.md 
* plot
    * MLP_w2.png
    * result.png
* test.py  

----

**operating environment**  
pyhton3.9  

----

**file description**  
- train.py  It is the main training file and can be run directly

- test.py   It is the main testing file and can be run directly

-  parameter_search.py   The test file for searching hyperparameter and can be run directly

-  plot_image.py    files for drawing

-  readme.md    manual
----
**Instructions for use**
- Start training: You need to enter the epoch for training, and the batch_size for training: the default is already a hyperparameter that has been searched in parameter_search.py
```
pyhton train.py --train_num_epochs = 10 --batch_size = 32
```

- Start the test:  the test_dataset of minist is used here, if there is no such dataset, it will be downloaded automatically
```
python test.py
```

- Start parametric search
```
python parameter_search.py
```

-----

**Model file Baidu cloud address**  
Link: https://pan.baidu.com/s/1x5v4Hx1ars7X8Vjcc-Sp_w  Extraction code: dwca
