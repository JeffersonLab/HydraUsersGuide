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
In the event there are multiple predict processes running, the distribute model distrubtes images in a round robin fashion to the various instances of predict. 

# Predict


# Action