# Comprehensive Analysis of Deepfake Detection Models in Video: Performance Comparison and Optimization

## Dataset
We used publicly available datasets they are [CelbDF-V2](https://github.com/yuezunli/celeb-deepfakeforensics) and [FaceForensics++](https://github.com/ondyari/FaceForensics)

## Result

####  Performance Metrics of Weighted Average on CelebDf-V2 Dataset

| Model         | Accuracy   | Precision  |  Recall | F1 Score   |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| 
|  XceptionNet  | **98%**  | **0.98**  | **0.98**  | **0.98** |
|  InceptionResNetV2  | 0.97  |  0.97  | 0.97  | 0.97 |
|  EfficientNetV2S  | 0.97  | 0.97  | 0.97  | 0.97 |
|  EfficientNetV2M  | 0.97  | 0.97  | 0.97  | 0.97 |

####  Performance Metrics of Weighted Average on FaceForensics++ Dataset

| Model         | Accuracy   | Precision  |  Recall | F1 Score   |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| 
|  InceptionResNetV2  | **94%**  |  **0.94**  | **0.94**  | **0.94** |
|  XceptionNet  | 93%  | 0.93  | 0.93  | 0.93 |
|  EfficientNetV2S  | 92%  | 0.92  | 0.92  | 0.92 |
|  EfficientNetV2M  | 88%  | 0.89  | 0.88  | 0.88 |

## License

This repository is licensed under the MIT License. See the [LICENSE](https://github.com/maimuna01/BTECH-DEEPFAKE-DETECTION/edit/main/LICENSE) file for more information.
