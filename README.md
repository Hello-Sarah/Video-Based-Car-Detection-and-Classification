# Video-Based-Car-Detection-and-Classification

•	Designed and implemented a video-based vehicle detection and classification system to detect, track and mark the model, brand, and color of the moving vehicles in the video.

•	Designed a vehicle detection algorithm based on the combination of BP-neural Network and Histogram of Oriented Gradients feature for SVM classifier training, and then achieved 96.23% mean accuracy rate and 19.35 fps handle speed.

•	Adopted YOLO model and optimized it with resizing images to meet the real-time detection demand (32.15 fps).

•	Used CNN model to identify the models of cars with the confidence of 0.99 and the overall accuracy rate of 93.52%.

•	Used two methods, one was the combination of the color histogram features and KNN classification algorithm and another was Faster-RCNN model, to recognize the colors of the vehicles.

•	Used the crawler to collect 20,778 images of 40 brands and processed them, and then designed a CNN model based on VGG19 suitable for the dataset and achieved 96% accuracy rate for brand recognition.

•	Designed and implemented a license plate recognition algorithm based on hidden Markov models and optimized it by calculating the dissimilarity matrix of relevant factors to obtain optimal threshold with 0.945 of AUC and 91% accuracy.
