🚀 Just wrapped up a YOLO-based object detection experiment on a reference video!

I built a pipeline that runs object detection frame by frame, overlays bounding boxes, and exports an annotated video for further analysis and visualization.

📊 Run Statistics

Processed frames: 1,063

Total detections: 5,318

Processing time: 456.74 seconds

Processing speed: 2.33 FPS

📦 Detections per class

person: 3,457

motorcycle: 1,053

car: 349

bicycle: 173

truck: 142

train: 71

tennis racket: 29

bench: 25

vase: 4

skateboard: 4

horse: 3

dog: 3

traffic light: 2

bird: 1

bus: 1

cow: 1

💾 The processed output video is saved as output_detected.mp4, showcasing all detections over time.

💻 Source code
GitHub repo: https://github.com/AshcharyaR/YOLO-based-object-detection-pipeline/tree/main
This repository contains the complete pipeline: video input handling, frame extraction, YOLO inference, drawing bounding boxes and labels, aggregation of detection statistics, and writing the final annotated video.

🔍 Next steps: optimizing FPS, experimenting with different YOLO variants, and testing on custom datasets for domain-specific use cases like traffic analytics and surveillance.

#computerVision #YOLO #objectDetection #DeepLearning #OpenCV #Python
