---
title: "Run"
parent: "User Interface"
nav_order: 3
---

# Hydra Run 

The Hydra Run page displays a "security cam" view of monitoring histograms and their classifications. The page automatically updates by polling the database for new images. The core component of the Hydra run page are the image cards. Each monitoring image is contained in its own image card, with text information in the card header and actions in the card footer. A detailed view and description of the image cards can be found below. 

![Bad Image Card][/assets/GoodPlotBox.png "Example of Bad Image Card"]

Optionally, GradCAM (cite) heat maps can be overlayed for images that are classified as bad. These heat maps indicate where the model is looking when classifying a bad image. The opacity slider can be used to increase or decrease the opacity as needed. 

