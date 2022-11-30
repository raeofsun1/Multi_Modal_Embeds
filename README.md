# Multi-Modal Vision and Language Transformer

This repository provides code for fine-tuning tasks on Vision and Language.

---



## Downloads



### Pre-trained model
- [BLIP weights](https://storage.googleapis.com/sfr-vision-language-research/BLIP/models/model_base.pth) - Pretrained weights for multi-modal transformer architecture.


### Datasets
- [vqaV2](https://visualqa.org/download.html) - Download latest dataset from the original website.
- [NLVR2](https://github.com/lil-lab/nlvr/tree/master/nlvr2) - Download latest dataset from the original repository.



## VQA
- Download VQAv2 dataset and update path in config file.
- Finetune the model on pre downloaded weights using
  <pre>python -m torch.distributed.run --nproc_per_node=16 train_vqa.py </pre>
  
  
  
  ## NLVR2
- Download NLVR2 dataset and update path in config file.
- Finetune the model on pre downloaded weights using
  <pre>python -m torch.distributed.run --nproc_per_node=16 train_nlvr.py </pre> 
  
  
 
