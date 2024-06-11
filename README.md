# Style Transfer Transformer (*STTR*)

**Image Style Transfer** is a computer vision techique that combines a content image and a style image generating a thrid output image that preserves both the content and style.

![imagem](https://github.com/pedrops164/AP-STTR/assets/73351929/ba4741a7-d368-43f9-8111-4aae939dbd74) 

## Install

```
conda install -c pytorch pytorch torchvision
conda install cython scipy
```

## Test

Download pre-trained model here

https://drive.google.com/file/d/1OsRljnuWBb9BQzFJnidkhwuPKOt6YYx9/view?usp=sharing

Put it under ```./checkpoint_model```

Please change the images you want to use in the following folders:

```
inputs/content: a folder to store all content images
inputs/style: a folder to store all style images
```
Then run 

```
python demo_sttr_image.py
```

You could see results in ```outputs/test_outputs/0005```
