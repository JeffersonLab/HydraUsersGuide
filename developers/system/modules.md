---
title: "Modules"
parent: "System"
grand_parent: "Developers"
nav_order: 1
---
The Hydra system contains four modules with well defined tasks. 

# Format
The first Hydra module, called Feeder, ensures that each image is correctly formatted for the given model. Feeder will automatically resize an image if the shape is different from that used to train the model. 

# Distribute
In the event there are multiple instances of the predict module running, the distribute model distrubtes images in a round robin fashion to the various instances of predict. 

# Predict
Predict is responsible for loading the models, waiting for inference requests, running inference with the appropriate models, generating GradCAM heat maps, and writing a report to be analyzed by the Action module. 

# Action
The action module is responsible for analyzing the reports generated from the predict process and performing any number of actions as a result of those reports. This could include raising an alarm (visual or audible), saving the image for labeling, saving the image for viewing on the Log page, and updating the KeeperStatus table. 