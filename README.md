# Landmark Recognition (using Kaggle Datasets)

## Understanding the Data

The training set was created by clustering photos based on their geolocation and visual similarity using an algorithm. Matches between training images were identified through local feature matching. Note that a single landmark may have multiple clusters, typically representing different views or sections of the landmark. To avoid bias, no computer vision algorithms were used for generating ground truth. Instead, human annotators established ground truth correspondences between test images and landmarks.

## Implementation Details

1. Clustering Photos by Geolocation and Visual Similarity -
   - I clustered photos based on their geolocation and visual similarity using an algorithm. This clustering helped me organize the data and identify potential landmarks.

2. Local Feature Matching -
   - I established matches between training images using local feature matching techniques. This step ensures that visually similar images are accurately grouped together, which is crucial for recognizing landmarks from different angles and perspectives.

3. Multiple Clusters per Landmark -
   - I accounted for multiple clusters per landmark, typically corresponding to different views or parts of the landmark. This allows my system to recognize landmarks even when they are viewed from various angles or when only parts of the landmark are visible.

4. Human Annotation for Ground Truth -
   - To avoid bias and ensure accuracy, I established ground truth correspondences between test images and landmarks using human annotators instead of relying solely on computer vision algorithms. This human-in-the-loop approach improves the reliability of the training data.

5. Comprehensive Dataset Preparation -
   - By preparing a comprehensive dataset that includes diverse views and parts of landmarks, I tried to ensure that the recognition system can handle a wide range of scenarios, improving its robustness and accuracy.

6. Utilization of Advanced Algorithms -
   - I leveraged advanced algorithms for clustering and feature matching, ensuring that the system is capable of high-precision landmark recognition.

By combining these techniques, I build a solution for identifying and recognizing landmarks from images, addressing key challenges and leveraging both algorithmic and human expertise to achieve high accuracy and reliability.

Kaggle Dataset: [Landmark Recognition Dataset](https://www.kaggle.com/c/landmark-recognition-2020/data)

### Refrences
 - [A Very Extensive Landmark Exploratory Analysis](https://www.kaggle.com/codename007/a-very-extensive-landmark-exploratory-analysis)
