# Movie Recommendation

### Package : 
`keras==2.0.8` &nbsp; ` numpy==1.13.3`  &nbsp;` pandas==0.20.3` &nbsp; `sklearn==0.19.1` &nbsp;


### Note :

The model was stored in ./mnodel folder. <br>
In my .py script, I used the following script to assign the task running on GPU 0.<br>

```
import os
os.environ['CUDA_VISIBLE_DEVICES'] = "0"
```
Usage<br>

```
python3 inference.py [train_data_path] [test_data_path] [train_caption_path] [test_caption_path] [output_path]
```

### Best model architecture :

![alt text](https://github.com/thtang/ML2017FALL/blob/master/hw5/best_model.png)