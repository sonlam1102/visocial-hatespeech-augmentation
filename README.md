# Information  
## Dataset: 
We use two Vietnamese datasets: UIT-ViCTSD and ViHSD  
The dataset are available in this link: https://sites.google.com/uit.edu.vn/uit-nlp/datasets-projects 
## Models:
+ Deep neural model: TextCNN and GRU  
+ Multilingual transformers: mBERT, XLM-R, and DistilBERT  
+ Monololingual transformers: PhoBERT, BERT4News, and VELECTRA   
## Method: 
+ EDA: Data augmentation on minority classes.
+ Focal loss: Loss function that treat the sample in the minority class by down-weighting the impact of majority examples

# Source code file name convention:
The source code are written in Python with Jupyter notebook

The name of the files are written as follow: "&lt;dataset&gt; &lt;type of models&gt; &lt;a&gt;_&lt;b&gt;.jpynb"   

+ &lt;dataset&gt;: the name of dataset (ViHSD or ViCTSD) 

+ &lt;type of models&gt;: the type of model. DNN - Deep neural network. Monolingual transformer and Multilingual transformer.

+ &lt;a&gt;: aug - the model trained on the augmented data. If there are no "aug" term, the model trained on the original dataset. 

+ &lt;b&gt;: no_pp - no pre-processing techniques. If there are no "no-pp" term, the model trained with pre-processing steps as described in the paper. 


# Publication 
Luu, S.T., Van Nguyen, K. & Nguyen, N.LT. An approach of data augmentation to improve the performance of BERTology models for Vietnamese hate speech detection. Multimed Tools Appl (2023). https://doi.org/10.1007/s11042-023-16968-5     

Cite as: 
```
@article{luu2023approach,
  title={An approach of data augmentation to improve the performance of BERTology models for vietnamese hate speech detection},
  author={Luu, Son T and Van Nguyen, Kiet and Nguyen, Ngan Luu-Thuy},
  journal={Multimedia Tools and Applications},
  pages={1--21},
  year={2023},
  publisher={Springer}
}
```
