# Comprehensive Analysis of Deepfake Detection Models in Video: Performance Comparison and Optimization
Deepfake technology is widely used, which has led to serious worries about the authenticity of digital media, making the need for trustworthy deepfake face recognition techniques more urgent than ever. This study employs a resource-effective and transparent cost-sensitive deep learning method to effectively detect deepfake faces in videos. To create a reliable deepfake detection system, four pre-trained Convolutional Neural Network (CNN) models: XceptionNet, InceptionResNetV2, EfficientNetV2S, and EfficientNetV2M were used. FaceForensics++ and CelebDf-V2 as benchmark datasets were used to assess the performance of our method. To efficiently process video data, key frame extraction was used as a feature extraction technique. Our main contribution is to show the model’s adaptability and effectiveness in correctly identifying deepfake faces in videos. The XceptionNet model on the CelebDf-V2 dataset gave the proposed methodology a 98% accuracy, which was the highest possible whereas, the InceptionResNetV2 model, achieves an accuracy of 94% on the FaceForensics++ dataset. 

## Dataset
We used publicly available datasets they are [CelbDF-V2](https://github.com/yuezunli/celeb-deepfakeforensics) and [FaceForensics++](https://github.com/ondyari/FaceForensics)

## Result

####  Performance Metrics of Weighted Average on CelebDf-V2 Dataset

| Model         | Accuracy   | Precision  |  Recall | F1 Score   |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| 
|  XceptionNet  | **98%**  | **0.98**  | **0.98**  | **0.98** |
|  InceptionResNetV2  | 97%  |  0.97  | 0.97  | 0.97 |
|  EfficientNetV2S  | 97%  | 0.97  | 0.97  | 0.97 |
|  EfficientNetV2M  | 97%  | 0.97  | 0.97  | 0.97 |

####  Performance Metrics of Weighted Average on FaceForensics++ Dataset

| Model         | Accuracy   | Precision  |  Recall | F1 Score   |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| 
|  InceptionResNetV2  | **94%**  |  **0.94**  | **0.94**  | **0.94** |
|  XceptionNet  | 93%  | 0.93  | 0.93  | 0.93 |
|  EfficientNetV2S  | 92%  | 0.92  | 0.92  | 0.92 |
|  EfficientNetV2M  | 88%  | 0.89  | 0.88  | 0.88 |

## License

This repository is licensed under the MIT License. See the [LICENSE](https://github.com/maimuna01/BTECH-DEEPFAKE-DETECTION/edit/main/LICENSE) file for more information.
