# Khảo sát các model CNN
Chúng em đã khảo sát các model CNN với cùng tham số như sau:
* `learning rate`: 0.0001
* `epochs`: 25
* `batch size`: 64
* `fully connected layer`: 35 nodes, `activation`: sigmoid


|     **Model**           | **Fold 1**  | **Fold 2**  | **Fold 3**  | **Fold 4**  | **mAP**     |
| ----------------------: | ----------: | ----------: | ----------: | ----------: | ----------: |
|     **[VGG-16](https://github.com/thangdduong/CS114.M11.KHCL/blob/main/final/survey/vgg16.ipynb)**          | 0\.446      | 0\.476      | 0\.476      | 0\.463      | 0\.465      |
| **[ResNet50](https://github.com/thangdduong/CS114.M11.KHCL/blob/main/final/survey/resnet.ipynb)**        | 0\.284      | 0\.275      | 0\.275      | 0\.281      | 0\.279      |
| **[InceptionV3](https://github.com/thangdduong/CS114.M11.KHCL/blob/main/final/survey/inception.ipynb)**         | 0\.796      | 0\.813      | 0\.804      | 0\.793      | 0\.801      |
| **[MobileNet](https://github.com/thangdduong/CS114.M11.KHCL/blob/main/final/survey/mobilenet.ipynb)**           | 0\.801      | 0\.823      | 0\.826      | 0\.814      | **0\.816**  |
| **[DenseNet121](https://github.com/thangdduong/CS114.M11.KHCL/blob/main/final/survey/densenet.ipynb)**         | 0\.78       | 0\.797      | 0\.791      | 0\.775      | 0\.786      |
| **[EfficientNetB0](https://github.com/thangdduong/CS114.M11.KHCL/blob/main/final/survey/efficientnet.ipynb)**      | 0\.182      | 0\.183      | 0\.195      | 0\.191      | 0\.188      |

# Khảo sát các classifiers:
Notebook: [classifiers.ipynb](https://github.com/thangdduong/CS114.M11.KHCL/blob/main/final/survey/classifiers.ipynb)

Chúng em đã chọn 6 classifier cơ bản, để mặc định chúng và không sử dụng rút trích đặc trưng:

|     **Model**                | **Fold 1**  | **Fold 2**  | **Fold 3**  | **Fold 4**  | **Fold 5**  | **mAP**    |
| ---------------------------: | ----------: | ----------: | ----------: | ----------: | ----------: | ---------: |
|     **KNN**                  | 0\.445      | 0\.472      | 0\.46       | 0\.455      | 0\.473      | 0\.461     |
| **Decision Tree**            | 0\.239      | 0\.242      | 0\.243      | 0\.247      | 0\.241      | 0\.242     |
| **Random Forest**            | 0\.563      | 0\.576      | 0\.575      | 0\.56       | 0\.578      | **0\.57**  |
| **SVC**                      | 0\.503      | 0\.518      | 0\.498      | 0\.538      | 0\.533      | 0\.518     |
| **Logistic Regression**      | 0\.297      | 0\.295      | 0\.3        | 0\.298      | 0\.285      | 0\.295     |
| **Naive Bayes**              | 0\.202      | 0\.213      | 0\.198      | 0\.209      | 0\.225      | 0\.21      |

# Kết hợp rút trích đặc trưng từ MobileNet và đưa vào các classifiers:
Notebook: [FE_to_classifiers.ipynb](https://github.com/thangdduong/CS114.M11.KHCL/blob/main/final/survey/FE_to_classifiers.ipynb)

|     **Model**                | **Fold 1**  | **Fold 2**  | **Fold 3**  | **Fold 4**  | **Fold 5**  | **mAP**     |
| ---------------------------: | ----------: | ----------: | ----------: | ----------: | ----------: | ----------: |
|     **KNN**                  | 0\.797      | 0\.798      | 0\.768      | 0\.787      | 0\.786      | 0\.787      |
| **Decision Tree**            | 0\.405      | 0\.401      | 0\.4        | 0\.423      | 0\.436      | 0\.413      |
| **Random Forest**            | 0\.806      | 0\.805      | 0\.819      | 0\.809      | 0\.824      | 0\.813      |
| **SVC**                      | 0\.892      | 0\.879      | 0\.882      | 0\.882      | 0\.881      | **0\.884**  |
| **Logistic Regression**      | 0\.814      | 0\.815      | 0\.809      | 0\.82       | 0\.803      | 0\.812      |
| **Naive Bayes**              | 0\.478      | 0\.472      | 0\.491      | 0\.471      | 0\.469      | 0\.476      |
