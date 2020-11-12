### Toronto Machine Learning Summit (TMLS) Workshop

# Put Deep Learning to work: 
## Accelerate Deep Learning through Amazon SageMaker and ML Services

#### Date: November 16, 2020
#### Time: 2:00 PM to 4:30 PM (EST)


## Abstract
Deploying deep learning (DL) projects are becoming increasingly more pervasive at enterprises and startups alike. At Amazon, [Machine Learning University (MLU)](https://www.youtube.com/channel/UC12LqyqTQYbXatYS9AA7Nuw) trained engineers are taking DL to every aspect of Amazon’s businesses, beyond just Amazon Go, Alexa, and Robotics.
In this tutorial, [Wenming Ye](https://www.linkedin.com/in/wenming-ye-0170b11/) (Amazon Web Services) and [Rachel Hu](https://www.linkedin.com/in/rachelsonghu/) (Amazon Web Services) offer a practical next step in DL learning with instructions, and hands-on labs using the latest Nvidia GPUs and AWS Inferentia. You will explore the current trends powering AI/DL adoption, powerful new GPU/AWS Inferentia accelerator instances, distributed training and inference optimization in neural networks.



## Author Bios

**Rachel Hu** is an applied scientist on the AWS AI working on deep learning. She received her master’s degree of statistics from University of California, Berkeley. She is an instructor at Amazon Machine Learning University and frequently presents at external events such as AWS Re:invent, Nvidia GTC, etc. She enjoys empowering everyone who is curious about start-of-the-art deep learning algorithms with easy to understand instructions and innovative new teaching tools. Before joining Amazon, Rachel also worked on natural language processing projects to promote user engagements in multiple industries.

**Wenming Ye** is a senior technical product manager at AWS AI, helping researchers and enterprise customers use cloud-based machine learning services to rapidly scale their innovations. Previously, Wenming had a diverse R&D experience at Microsoft Research, SQL engineering team, and successful startups.





## Agenda


|   EST Time    |  Title    |  Speaker | Slides/Notebooks    |
| ---- | ---- | ---- | ---- |
| 2:00 PM | **Welcome and Logistics** |  Rachel Hu; Wenming Ye | N/A |
| 2:10 PM | **Amazon AI and SageMaker Overview** | Wenming Ye | [slides](https://github.com/goldmermaid/TMLC2020/blob/master/tmlc2020.pdf) |
| 2:40 PM | **BERT and Transformer** | Rachel Hu  | (same as above)  |
| 3:20 PM | **Lab: Fine Tuning BERT Model on Q&A dataset** | Rachel Hu  |  [jupyter](https://github.com/goldmermaid/TMLC2020/blob/master/bert_finetune/bert_pytorch_finetuning.ipynb) |
|  | (10 min break during model training)  |
| 4:00 PM | **Lab: Model Deployment** | Rachel Hu  | (same as above) |
| 4:30 PM | **Conclusion** |  Rachel Hu; Wenming Ye | N/A  |




## Prerequisites
You will need a Laptop. We recommend that you have an extra Screen if available.

## Slides

Download [Here](./tmlc2020.pdf). 

## AWS Account
AWS account is not required for this Lab, you will be provided with a Hash URL to access a pre-provisioned AWS environment and Amazon Sagemaker.

Amazon SageMaker is a fully-managed service that enables developers and data scientists to quickly and easily build, train, and deploy machine learning models at any scale. Amazon EC2 P3 instances deliver the highest performance compute in the cloud, are cost-effective, support all major machine learning frameworks, and are available globally. In this workshop, you'll create a SageMaker notebook instance and work through sample Jupyter notebooks that demonstrate some of the many features of SageMaker and how Amazon EC2 P3 is used to accelerate machine learning model training.


## Live Lab Instructions:
1. Go to Events engine website (will be given during live event), on team dashboard, click on AWS Console. If you are using your own account, skip to step 3.

1. Now click on `Open AWS Console`. Find, and click on `Amazon SageMaker` service link on the main page.

    <img src="./img/zzz.png" width="400">
    
1. On the left side menu, go down to Notebook, select submenu item `Notebook instances`. Now, click on the orange `Create notebook instance` Button.

    <img src="./img/zz.png" width="150">
    
1. Pick a notebook instance name in the first text box.
1. For notebook instance type, select "**ml.p3.2xlarge**".
1. Click `Additional Configuration`, and set "Volume size in GB" to be "50 GB".

    <img src="./img/volume.png" width="400">

1. Scroll down and click `Git repositories`. Click the drop-down menue and select `Clone a Public Git....`. Then, enter: "**https://github.com/goldmermaid/TMLC2020**" in the text box.

    <img src="./img/gitrepo.png" width="400">
    
1. Finally, click on the orange `Create notebook instance` Button. Now the notebook instance launching request is sent and the instance's status is show `Pending`. It should be launched in 2-5 minutes.

Once the instance's status turns Green `In Service`:
1. Click on `Open Jupyter`.

    <img src="./img/zzzz.png" width="600">
    
    
1. In the directory `bert_finetuning`, open Jupyter notebook "**bert_pytorch_finetuning.ipynb**".



Now go ahead and finetune your BERT model on SQuAD dataset!


(If you are interested in our Research reward program, please see the link below. Or contact us directly. https://aws.amazon.com/aws-ml-research-awards/)




## License
The contents of this workshop are licensed under the Apache 2.0 License.
