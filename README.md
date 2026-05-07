# Multi-Model-Object-Detection-and-Segmentation-using-YOLOv8  
                                                              INTRODUCTION
Object Detection and Image Segmentation are two important tasks in the field of Computer Vision. Computer vision enables machines and computer systems to understand and interpret visual information from images and videos. With the rapid development of Artificial Intelligence and Deep Learning technologies, object detection systems have become widely used in many real-world applications such as autonomous vehicles, surveillance systems, smart cities, medical imaging, robotics, and security monitoring.
Object detection refers to the process of identifying and locating objects within an image or video frame. The system not only detects the presence of objects but also draws bounding boxes around them and labels them with appropriate class names. On the other hand, image segmentation goes one step further by identifying the exact shape and boundaries of objects within an image. Segmentation divides the image into multiple segments so that each pixel belongs to a specific object category.
In recent years, deep learning based models have significantly improved the performance and accuracy of object detection systems. Among these models, the YOLO (You Only Look Once) family of algorithms has gained significant popularity due to its high speed and accuracy. YOLO models perform object detection in a single pass through the neural network, making them suitable for real-time applications.
This project focuses on implementing Multi-Model Object Detection and Segmentation using YOLOv8, which is one of the latest and most advanced versions of the YOLO architecture. YOLOv8 provides improved detection accuracy, faster processing speed, and enhanced segmentation capabilities compared to previous YOLO versions.
The system is developed using the Python programming language along with libraries such as Ultralytics YOLOv8, OpenCV, Streamlit, and PyTube. These technologies help in building a user-friendly application capable of detecting objects from different sources including images, stored videos, webcam streams, and YouTube videos.
The application provides a graphical interface built with Streamlit, allowing users to easily upload images or videos and perform object detection or segmentation. The system loads a pre-trained YOLOv8 model and processes the input media to identify objects in real time. The detected objects are displayed with bounding boxes and confidence scores, making it easier for users to visualize the results.
Additionally, the system also supports real-time object detection through webcam streaming and video processing. This makes the project suitable for practical applications such as surveillance monitoring, traffic analysis, and automated object recognition systems.
The main objective of this project is to design and develop a flexible and efficient object detection system that can process multiple types of input sources while maintaining high accuracy and performance using YOLOv8 deep learning models.
Artificial Intellingence
Artificial intelligence (AI) is the ability of a computer program or a machine to think andlearn. It is also a field of study which tries to make computers "smart". As machines become increasingly capable, mental facilities once thought to require intelligence are removed from the definition. AI is an area of computer sciences that emphasizes the creation of intelligent machines that work and reacts like humans. Some of the activities computers with artificial intelligence are designed for include: Face recognition, Learning, Planning, Decision making etc.,

Artificial intelligence is the use of computer science programming to imitate human thought and action by analysing data and surroundings, solving or anticipating problems and learning or self-teaching to adapt to a variety of tasks.

Machine Learning 
Machine learning is a growing technology which enables computers to learn automatically from past data. Machine learning uses various algorithms for building mathematical models and making predictions using historical data or information. Currently, it is being used for various tasks such as image recognition, speech recognition, email filtering, Facebook auto-tagging, recommender system, and many more. Machine Learning is said as a subset of artificial intelligence that is mainly concerned with the development of algorithms which allow a computer to learn from the data and past experiences on their own. The term machine learning was first introduced by Arthur Samuel in 1959. We can define it in a summarized way as: “Machine learning enables a machine to automatically learn from data, improve performance from experiences, and predict things without being explicitly programmed”.

A Machine Learning system learns from historical data, builds the prediction models, and whenever it receives new data, predicts the output for it. The accuracy of predicted output depends upon the amount of data, as the huge amount of data helps to build a better model which predicts the output more accurately.

Suppose we have a complex problem, where we need to perform some predictions, so instead of writing a code for it, we just need to feed the data to generic algorithms, and with the help of these algorithms, machine builds the logic as per the data and predict the output. Machine learning has changed our way of thinking about the problem. The below block diagram explains the working of Machine Learning algorithm:

 
Features of Machine Learning
o	Machine learning uses data to detect various patterns in a given dataset.
o	It can learn from past data and improve automatically.
o	It is a data-driven technology.
o	Machine learning is much similar to data mining as it also deals with the huge amount of the data.
Classification of Machine Learning
o	At a broad level, machine learning can be classified into three types:
o	Supervised learning
o	Unsupervised learning Reinforcement learning
Supervised Learning

Supervised learning is a type of machine learning method in which we provide sample labeled data to the machine learning system in order to train it, and on that basis, it predicts the output.

The system creates a model using labeled data to understand the datasets and learn about each data, once the training and processing are done then we test the model by providing a sample data to check whether it is predicting the exact output or not.

The goal of supervised learning is to map input data with the output data. The supervised learning is based on supervision, and it is the same as when a student learns things in the supervision of the teacher. The example of supervised learning is spam filtering.
Supervised learning can be grouped further in two categories of algorithms:

o	Classification
o	Regression

Unsupervised Learning

Unsupervised learning is a learning method in which a machine learns without any supervision. The training is provided to the machine with the set of data that has not been labeled, classified, or categorized, and the algorithm needs to act on that data without any supervision. The goal of unsupervised learning is to restructure the input data into new features or a group of objects with similar patterns.

In unsupervised learning, we don't have a predetermined result. The machine tries to find useful insights from the huge amount of data. 

It can be further classifieds into two categories of algorithms:
o	Clustering
o	Association


Deep Learning   
Deep learning is a branch of machine learning which is completely based on artificial neural networks, as neural network is going to mimic the human brain so deep learning is also a kind of mimic of human brain. In deep learning, we don’t need to explicitly program everything. The concept of deep learning is not new. It has been around for a couple of years now. It’s on hype nowadays because earlier we did not have that much processing power and a lot of data. As in the last 20 years, the processing power increases exponentially, deep learning and machine learning came in the picture.

In human brain approximately 100 billion neurons all together this is a picture of an individual neuron and each neuron is connected through thousands of theirneighbours.
The question here is how do we recreate these neurons in a computer. So, we create an artificial structure called an artificial neural net where we have nodes or neurons. We have some neurons for input value and some for-output value and in between, there may be lots of neurons interconnected in the hidden layer.

Recurrent 
(perform same task for every element of a sequence) Neural Network – Allows for parallel and sequential computation. Similar to the human brain (large feedback network of connected neurons). They are able to remember important things about the input they received and hence enables them to be more precise.

YOLO 
In our comprehensive system designed to enhance road safety and enforce helmet-wearing regulations, the YOLO (You Only Look Once) algorithm plays a pivotal role in real-time bject detection. Specifically, YOLO is employed to identify individuals on motorcycles who are not wearing helmets. YOLO is renowned for its remarkable efficiency in real-time object detection. It allows our system to process video feeds from live webcams and promptly 
