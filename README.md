# Face-Generation-Using-DCGANs

Run the First Section of any of the Notebook to download and extract the Celebrity Dataset in the current working directory

                                                OR

Download and extract the dataset manually from this link and put the files in this structure

  -/DC_GANs_for_3_channel_images.ipynb<br/>
  -/100k<br/>
  --/1.jog<br/>
  --/2.jpg
  
Run all the cells of the notebook to train on 100,000 batches of images

## Best Results From Each Notebook

Each Batch Contains 64 randomly selected images from the dataset

### Best Result from the Shallow Network                                                                     
(After 60000 batchs of training)

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/images/60000.png)

### After 10000 batches                                                                     

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/10000.png)


### After 30000 batches                                                                     

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/30000.png)

### After 40000 batches                                                                     

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/40000.png)

### After 50000 batches                                                                     

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/50000.png)

### After 60000 batches                                                                     

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/70000.png)

### After 80000 batches                                                                     

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/80000.png)


## Architecture

### _Generator Model_

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/generator.png)

### _Discriminator Model_

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/discriminator.png)

### _Combined Model_

![alt text](https://github.com/OverGeek/Face-Generation-Using-DCGANs/blob/master/combined.png)
