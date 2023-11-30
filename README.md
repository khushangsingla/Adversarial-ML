# Adversarial-ML
This project was about exploring various techniques of adversarial attacks and defenses as part of CS337 course project.

Link to Presentation: https://docs.google.com/presentation/d/1ur1dAlllRn1_w_sxVUNhjUQXDi6CGmi9x7VDnufalZI/edit?usp=sharing

## Files

```bash
Adversarial-ML
    ├── GTSRB
    │   ├── GTSRB_adversery.ipynb
    │   ├── GTSRB_defensive.ipynb
    │   └── GTSRB_model_training.ipynb
    ├── ImageNet
    │   ├── imagenet_adv.ipynb
    │   ├── imagenet_data_collection.ipynb
    │   └── Images
    ├── README.md
    └── SMS_spam
        ├── SPAM_adverserial_attack.ipynb
        └── spam.csv
```


- GTSRB/GTSRB_adversery.ipynb

    This notebook has code for FGSM. It also explores various other modifications.
- GTSRB/GTSRB_defensive.ipynb
    
    This notebook explores effects of adversarial training.
- GTSRB/GTSRB_model_training.ipynb

    This notebook has code for the adversarial attack on SMS for spam classification.
- ImageNet/imagenet_adv.ipynb

    This notebook has code for the adversarial attack on ResNet50 for a [subset of ImageNet](https://docs.voxel51.com/user_guide/dataset_zoo/datasets.html#imagenet-sample) using Gradient Ascent.
- ImageNet/imagenet_data_collection.ipynb

    This notebook has code for data collection pertaining to the adversarial attack on ResNet50.
- SMS_SPAM/SPAM_adversarial_attack.ipynb

    This notebook contains the model used for adversarial attacks.

## Team Members
- Aman Sharma	        	210100011
- Kevin P. Baua			210050084
- Khushang Singla	       	210050085
- Pratham Garg 	    	210050121
- Siddharth Patil	    	21d070071
