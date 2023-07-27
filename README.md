# OSA-Project (On-shelf Availability Project)

### Detailed Explication can be found in the report and in the code.

#### Description: This project aims to revolutionize supermarket inventory management by deploying an advanced AI-based shelf monitoring system. By strategically placing a camera in the store, the custom-trained AI model will continuously scan the shelves in real-time. The AI system can accurately detect empty spaces on the shelves and promptly notify the supermarket management system. This real-time alert mechanism empowers store staff to quickly replenish stock, ensuring that shelves remain adequately stocked at all times. The implementation of this system promises to optimize inventory control, minimize product shortages, and enhance overall customer satisfaction, making it a game-changer for modern supermarkets.

#### Tools: YOLOv8, Roboflow

#### Roboflow Dataset: https://universe.roboflow.com/fyp-ormnr/on-shelf-stock-availability-ox04t
#### Spinneys Dataset: https://universe.roboflow.com/yolo-wujjy/spinneys-test
#### Combined Dataset: https://universe.roboflow.com/yolo-wujjy/ce-s
#### Test0 Dataset: https://universe.roboflow.com/yolo-wujjy/test0-gf6hu

The Combined Dataset is the combination of the Roboflow and Spinneys Datasets.

#### Solution 1: Labeling Empty and Semi-Empty Spaces (Roboflow Dataset and some images from Spinneys Dataset)
#### Solution 2: Labeling Empty Spaces only (Roboflow Dataset and some images from Spinneys Dataset)
#### Solution 3: Labeling Empty Spaces only (Combining the full Spinneys Dataset with the Roboflow Dataset)

"Train Solution3 Predict" and "Train6 Solution3 Predict" are predictions on the test set of the Combined Dataset.
"Train Solution Predict Test0" are predictions on the Test0 Dataset.
