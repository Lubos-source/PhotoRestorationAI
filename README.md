# Implement AI for Photo Restoration to Google Colaboratory.

### [AI to use](https://github.com/sczhou/CodeFormer)
#### Citation:
*inproceedings:* **zhou2022codeformer** <br/>
    *authors:* **Zhou, Shangchen and Chan, Kelvin C.K. and Li, Chongyi and Loy, Chen Change** <br/>
    *title:* **Towards Robust Blind Face Restoration with Codebook Lookup TransFormer** <br/>
    *booktitle:* **NeurIPS** <br/>
    *year:* **2022** <br/>

### TO DO:
+ setup functional environment in *.ipynb --> good to use *Google Colaboratory* ✅
+ install requirements ✅
+ test if program is working ✅
+ make detail commented steps and documentation ✅
+ make easy to use user interface for using AI ✅
+ try to train model ? --> new colab (to not break working proof)

<br/>

### TESTED + results:
+ Whole Image Restoration - good working ✅
+ Face Restoration - good working ✅
+ Face Colorization - so, so working ✅
+ Face Inpainting - not working ❌ - scamed?
+ AI face repair - good working ✅
+ Video Enhancement - ✅

<br/>

### DEAD LINE 11.12.23


## [ *GC* version v1.2.1](https://drive.google.com/file/d/1YqDCJ2802Gi_7sm2TykyJ0Q8EE_sE2Ym/view?usp=sharing)

### Proof of not working Face Inpainting:

Copied whitespace and created new white line:
![PSProof1](./img/PHOTOSHOPproof.png)

On the original image. Added copied whitespace:
![PSProof2](./img/PHOTOSHOPproof2.png)

Not working -> final "repaired" image dont fill these white lines, it fill just the original ones.

Comparison of existing Photo Restoration AIs (from documentation):
![Comparison](./img/compre.jpg)

Used Algorith -> from documentation:
![algorithm](./img/algorithm.jpg)
