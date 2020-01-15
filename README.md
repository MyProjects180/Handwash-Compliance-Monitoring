# Handwash-Compliance-Monitoring

A hand wash monitoring system to help maintain proper hygiene.

Practicing hand hygiene is a simple yet effective way to prevent infections. Hospital staff tends to perform hand hygiene properly often only when they are aware that they are being observed. To track compliance, we aim to design a simple, cost‐effective solution easily reproducible on a mass scale which will in real time, monitor the entire process of hand washing.

In this project, we present a hand wash monitoring and reminder system that monitors hand wash events and their quality, provides real time feedback , reminds the person of interest how he is required to wash hands. Aim is to develop a working product that can differentiate hand wash gestures from other gestures with an high accuracy .Product must be robust, scalable, and easy to install, and it over‐comes most of the problems of existing related systems.


For training purpose we used Visual Studio. ML.NET Model Builder provides an easy to understand visual interface to build, train, and deploy custom machine learning models. Prior machine learning expertise is not required. Model Builder supports AutoML, which automatically explores different machine learning algorithms and settings to find the one that best suits the scenario.

1. Starting with the selection of the scenario, in our scenario it is image classification problem.

2. And then selecting a folder with the Images.

Model Builder expects image data to be JPG or PNG files organized in folders that correspond to the categories of the classification. 

To load images into Model Builder, provide the path to a single top level directory: 
•Top level directory contains one subfolder for each of the categories to predict. 
• Each subfolder contains the image files belonging to its category.

3. And now we start the training process. We created 350 image dataset for each step ,and there were 8 such steps. Approximate time required for training the model was 4.5 hrs.

4. In evaluation step we provided our sample input images and tested the acuuracy of the model.
