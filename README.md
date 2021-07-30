
#### 🛑 Note: please do not claim diagnostic performance of a model without a clinical study! This is not a kaggle competition dataset. Please read this paper about evaluation issues: [https://arxiv.org/abs/2004.12823](https://arxiv.org/abs/2004.12823) and [https://arxiv.org/abs/2004.05405](https://arxiv.org/abs/2004.05405)


## COVID-19 image data collection ([🎬 video about the project](https://www.youtube.com/watch?v=ineWmqfelEQ))

 ![image](https://github.com/jamjewel/Xray-classification/blob/a16e27bc6391765b13236e547fda973b7dc731d8/Page1.png)
  ![image](https://github.com/jamjewel/Xray-classification/blob/a16e27bc6391765b13236e547fda973b7dc731d8/Page2.png)
   ![image](https://github.com/jamjewel/Xray-classification/blob/a16e27bc6391765b13236e547fda973b7dc731d8/Page3.png)
    ![image](https://github.com/jamjewel/Xray-classification/blob/a16e27bc6391765b13236e547fda973b7dc731d8/Page4.png)
     ![image](https://github.com/jamjewel/Xray-classification/blob/a16e27bc6391765b13236e547fda973b7dc731d8/Page5.png)

Current stats of PA, AP, and AP Supine views. Labels 0=No or 1=Yes. Data loader is [here](https://github.com/mlmed/torchxrayvision/blob/master/torchxrayvision/datasets.py#L867)
``` 
COVID19_Dataset num_samples=481 views=['PA', 'AP']
{'ARDS': {0.0: 465, 1.0: 16},
 'Bacterial': {0.0: 445, 1.0: 36},
 'COVID-19': {0.0: 162, 1.0: 319},
 'Chlamydophila': {0.0: 480, 1.0: 1},
 'E.Coli': {0.0: 481},
 'Fungal': {0.0: 459, 1.0: 22},
 'Influenza': {0.0: 478, 1.0: 3},
 'Klebsiella': {0.0: 474, 1.0: 7},
 'Legionella': {0.0: 474, 1.0: 7},
 'Lipoid': {0.0: 473, 1.0: 8},
 'MERS': {0.0: 481},
 'Mycoplasma': {0.0: 476, 1.0: 5},
 'No Finding': {0.0: 467, 1.0: 14},
 'Pneumocystis': {0.0: 459, 1.0: 22},
 'Pneumonia': {0.0: 36, 1.0: 445},
 'SARS': {0.0: 465, 1.0: 16},
 'Streptococcus': {0.0: 467, 1.0: 14},
 'Varicella': {0.0: 476, 1.0: 5},
 'Viral': {0.0: 138, 1.0: 343}}

COVID19_Dataset num_samples=173 views=['AP Supine']
{'ARDS': {0.0: 170, 1.0: 3},
 'Bacterial': {0.0: 169, 1.0: 4},
 'COVID-19': {0.0: 41, 1.0: 132},
 'Chlamydophila': {0.0: 173},
 'E.Coli': {0.0: 169, 1.0: 4},
 'Fungal': {0.0: 171, 1.0: 2},
 'Influenza': {0.0: 173},
 'Klebsiella': {0.0: 173},
 'Legionella': {0.0: 173},
 'Lipoid': {0.0: 173},
 'MERS': {0.0: 173},
 'Mycoplasma': {0.0: 173},
 'No Finding': {0.0: 170, 1.0: 3},
 'Pneumocystis': {0.0: 171, 1.0: 2},
 'Pneumonia': {0.0: 26, 1.0: 147},
 'SARS': {0.0: 173},
 'Streptococcus': {0.0: 173},
 'Varicella': {0.0: 173},
 'Viral': {0.0: 41, 1.0: 132}}

 ```


## License

Each image has license specified in the metadata.csv file. Including Apache 2.0, CC BY-NC-SA 4.0, CC BY 4.0.

The metadata.csv, scripts, and other documents are released under a CC BY-NC-SA 4.0 license. Companies are free to perform research. Beyond that contact us.
