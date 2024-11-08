---
title: "Model Library"
parent: "User Interface"
nav_order: 3
---

# Model Library

The Library page allows you to compare the training and performance of each model trained for each particular image. General information about the model creation date, who created it, training loss and accuracy curves, and model thresholds can all be accessed on this page. 

The tabs allow you to view the enhanced confusion matrix, loss, and accuracy curves. The enhanced confusion matrix contains a histogram in each cell that plots the output weight of each particular classification. We can use this information to determine thresholds for each classification. If a particular output weight is above this threshold, Hydra can visually or audibly alarm. 