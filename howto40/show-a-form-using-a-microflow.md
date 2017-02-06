---
title: "Show a form using a microflow"
category: "howto40"
space: "Mendix 4 How-to's"
---
## Description

This section describes how to open a form and pass an object to it using a microflow. The related reference guide article can be found [here](https://world.mendix.com/pages/releaseview.action?pageId=10420581).

## Instructions

![](attachments/819203/917932.png) **Open the microflow, or if necessary create a new one. If you do not know how to add documents to your project, please refer to [this](https://world.mendix.com/display/howto25/Add+documents+to+a+module) article.**

![](attachments/2621596/2752901.png)

The microflow will have to pass an object to the form it opens, so make sure that this object is either created in the microflow, or passed to it.

![](attachments/819203/917932.png) **Add a 'Show form' activity to the microflow. If you do not know how to add activities to a microflow please refer to [this](https://world.mendix.com/display/howto25/Add+an+activity+to+a+microflow) article.**

![](attachments/2621596/2752902.png)

![](attachments/819203/917932.png) **Double-click on the 'Show form' activity to start configuring it.**

![](attachments/2621596/2752887.png)

![](attachments/819203/917932.png) **Press the 'Select' button next to 'Form' and select the form you want the microflow to open in the menu that appears.**

![](attachments/2621596/2752900.png)

![](attachments/819203/917932.png) **You can use the radio buttons at 'Location' to choose if you want the form to open in the content or as pop-up, and whether or not the pop-up should be blocking.**

![](attachments/819203/917932.png) **If you want the form to have a custom title, place a check mark next to 'Override form title' and enter the custom title.**

![](attachments/2621596/2752899.png)

![](attachments/819203/917932.png) **Finally at 'Form object' use the drop-down menu to select the object you want to pass to the form.**

![](attachments/2621596/2752888.png)

[![](attachments/819203/917564.png)](show-a-form-using-a-microflow)[(Back to Top)](show-a-form-using-a-microflow)