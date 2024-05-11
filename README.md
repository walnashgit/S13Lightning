# S13 Resent Lightning

## The code in jupityer notebook [S13Lightning.ipynb](https://github.com/walnashgit/S13Lightning/blob/main/S13Lightning.ipynb) trains the ResNet model written in pytorch lightning.

## Model: [S13ResNetLightning_model](https://github.com/walnashgit/ERAV2_main/blob/main/model/S13ResNetLightning_model.py)

## Demo: https://huggingface.co/spaces/walnash/erav2s13demo

### Dependencies to install:

    !pip install torch-lr-finder
    !pip install grad-cam     
    !pip install pytorch-lightning
    
### Clone the main repo for model and training code:
    !git clone https://github.com/walnashgit/ERAV2_main.git

Follow the code in S13Lightning.ipynb for detailed code.

### LR Finder graph:
<img width="582" alt="image" src="https://github.com/walnashgit/S13Lightning/assets/73463300/989eeea0-6088-4e5f-881c-ea066ed14574">

### Training and vaidation accuracy at last epoch

<img width="1407" alt="image" src="https://github.com/walnashgit/S13Lightning/assets/73463300/ab9d8db3-7704-4439-95ea-12db73551fe3">


### Training Accuracy
<img width="840" alt="image" src="https://github.com/walnashgit/S13Lightning/assets/73463300/1f833e38-d1f5-4210-a159-2605eb1f8196">

### Training Loss
<img width="836" alt="image" src="https://github.com/walnashgit/S13Lightning/assets/73463300/467f81ca-d71f-4124-a6dd-dd021aa17932">


### Validation Accuracy
<img width="844" alt="image" src="https://github.com/walnashgit/S13Lightning/assets/73463300/59bc5b85-89cb-4f61-a03f-519d4e15e203">


### Validation loss
<img width="844" alt="image" src="https://github.com/walnashgit/S13Lightning/assets/73463300/dd02e5c8-5a65-4061-8ae9-95d57d54b0c5">

### Miss-classified images
<img width="646" alt="image" src="https://github.com/walnashgit/S13Lightning/assets/73463300/b9298a00-4d4c-428e-a59f-7a897f66257e">

### Miss-classified images with grad cam at -1 layer
<img width="547" alt="image" src="https://github.com/walnashgit/S13Lightning/assets/73463300/062e273d-01c0-437e-be1e-030dbb28bcf4">
