# CNN-Transformer-based-Encoder-Decoder-Model-for-Nepali-Image-Captioning
Many image captioning tasks have been carried out in recent years, the majority of the work being for the English language. A few research works have also been carried out for Hindi and Bengali languages in the domain. Unfortunately, not much research emphasis seems to be given to the Nepali language in this direction. Furthermore, the datasets are also not publicly available in the Nepali language. The aim of this research is to prepare a dataset with Nepali captions and develop a deep learning model based on the Convolutional Neural Network (CNN) and Transformer combined model to automatically generate image captions in the Nepali language.

-> This repo contains two different codes:
  1. Data Translation
  2. CNN-Transformer Implementation

Models: 
->CNN: ResNet-101, EfficientNetB0 + Transformer
- Model A (ResNet-101 + Transformer)
- Model B (EfficientNetB0 + Transformer)

Evaluation metric: BLEU

Findings:
- Models showed better performance with Flickr8k data compared to Flickr30k.
- EfficientNetB0 outperformed ResNet-101 for this task.
- Model B outperforms Model A based on BLEU score and predicted captions.
- Best model scores: BLEU1:  0.53, BLEU2: 0.43, BLEU3: 0.39, BLEU4: 0.35


Here are the links for the datasets and paper:
  1. Flickr8k_Nepali: https://www.kaggle.com/datasets/bipeshrajsubedi/flickr8k-nepali-dataset
  2. Flickr30k_Nepali: https://www.kaggle.com/datasets/bipeshrajsubedi/flick30k-nepali-dataset
  3. Paper Link: https://aclanthology.org/2022.icon-main.12/

-> This work was preesented in the Proceedings of the 19th International Conference on Natural Language Processing (ICON) 2022, New Delhi, India. 

Paper Citation:
@inproceedings{subedi-krishna-bal-2022-cnn,
title = "{CNN}-Transformer based Encoder-Decoder Model for {N}epali Image Captioning",
author = "Subedi, Bipesh and
Krishna Bal, Bal",
booktitle = "Proceedings of the 19th International Conference on Natural Language Processing (ICON)",
month = dec,
year = "2022",
address = "New Delhi, India",
publisher = "Association for Computational Linguistics",
url = "https://aclanthology.org/2022.icon-main.12",
pages = "86--91",
}

-> There are two code versions in which one has all the detais while other is more simplified. You can work on both of these as per your requirement. 
-> Please star this repo if it was useful in any way as well as cite the corresponding paper given below in your work.

ResearchGate: https://www.researchgate.net/profile/Bipesh-Subedi

Google Scholar: https://scholar.google.com/citations?user=k4fX924AAAAJ&hl=en
