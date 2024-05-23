# A Debiased Nearest Neighbors Framework for Multi-Label Text Classification
Code of Our Paper "A Debiased Nearest Neighbors Framework for Multi-Label Text Classification"


## Enviroment
```
pip install -r requirements.txt
```


### Datasets

For the AAPD and RCV1-V2 datasets, we use the division following SGM. You can find it from the code of [SGM](https://github.com/lancopku/SGM).

For the EURLEX-57K, you can download from https://github.com/iliaschalkidis/lmtc-eurlex57k.

### Training
For the AAPD dataset:
```
!bash run_AAPD.sh 0.1 0.05 30
```

For the RCV1-V2 dataset:
```
!bash run_RCV1-V2.sh 0.3 0.05 40
```


### Test

You can download our well-trianed [checkpoint](https://drive.google.com/drive/folders/1ulGsIsFZ_eaitAc_yKx4tCf6RrV0QlNB) and use it to test.

# Contact
If there are any questions, please feel free to contact me: Zifeng Cheng (chengzf@smail.nju.edu.cn).
