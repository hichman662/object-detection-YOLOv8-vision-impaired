# object-detection-YOLOv8-vision-impaired
Enhance object detection for the visually impaired using YOLOv8. Includes annotated datasets, training scripts, and evaluation tools. Empowering independence in navigation
Data Overview
We annotated 390 images containing thirteen different objects, including stairs, standing signs, crosswalks, road maintenance equipment, potholes, cones, trash cans, garbage, columns, planters, tree-pit, streetlight, and bollards. The dataset was partitioned into training (71%), validation (20%), and testing (9%) sets.

Model Performance
Performance metrics of the YOLOv8 model during training and validation phases showcase accuracy and proficiency in object detection and classification.

Training Methodology and Regularization Techniques
Regularization methods, including dropout, weight decay, L1 and L2 regularization, and data augmentation, were employed to mitigate overfitting and enhance generalization. The impact of these techniques on model stability and performance metrics is analyzed and compared against a non-regularized model.

Execution Instructions
Clone this repository to your local machine.
Navigate to the directory containing the code files.
Run the training script train_model.py to train the YOLOv8 model with regularization techniques.
Execute the evaluation script evaluate_model.py to assess model performance metrics.
License
This project is licensed under the MIT License. See the LICENSE file for details.

For further details and insights, refer to the project documentation and analysis provided in the repository.
