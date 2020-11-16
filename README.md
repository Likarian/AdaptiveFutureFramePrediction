# AdaptiveFutureFramePrediction
Code and Data of 'Adaptive Future Frame Prediction with Ensemble Network,' ICPRW 2020

* Code and Data (5.4GB) : https://drive.google.com/file/d/1E30DpI0Pc8X0sQsbTPtr7WJ2ijSfIQP1/view?usp=sharing
  
The paper of the data :  
 **Wonjik Kim, Masayuki Tanaka, Masatoshi Okutomi, Yoko Sasaki, "Adaptive Future Frame Prediction with Ensemble Network", International Conference on Pattern Recognition Workshop, 2020.** ([link](https://arxiv.org/abs/2011.06788))

---
# How to use
### Dependencies
* Python 3.7.0
* Pytorch 1.2.0
* Cuda 10.0

### Run DownloadAndUnzip.sh
In your own directory, please run the following command in terminal.
<br>
> bash ./DownloadAndUnzip.sh 

### Sample code
You can see sample code for performance evaluation. When you want to check sample code, please run the following command in that directory.
<br>
Test with pre-trained only (Table 1 in the paper)
> python Test_PreTrained.py
Test with online-updating (Table 2 in the paper)
> python Test_EnsembleNetwork.py

---
# License
Code and data are allowed only for noncommercial usage. Please cite our paper if our data were used in your work.
You can see specific terms of use in the LICENSE.md.
