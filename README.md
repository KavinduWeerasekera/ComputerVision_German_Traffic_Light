Real-Time German Traffic Sign Detection (YOLOv11)

This repo contains code to train and run a real-time traffic sign detection model using YOLOv11 (Nano).
The model is trained on the GTSDB dataset, grouped into 4 main classes for better performance on edge devices.

🚀 Performance

Model: YOLOv11n

Accuracy: 95.6% mAP50

Speed: ~14.3 ms per image (~70 FPS)

Class-wise Results
Class	Precision	Recall	mAP50
Prohibitory	0.956	0.985	0.991
Danger	0.968	0.963	0.981
Mandatory	0.776	0.913	0.908
Other	0.922	0.892	0.943
