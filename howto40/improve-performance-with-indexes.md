---
title: "Improve performance with indexes"
category: "howto40"
space: "Mendix 4 How-to's"
---
## Description

This section describes how to improve your search performance by adding indexes to your entities. The related reference guide article can be found [here](https://world.mendix.com/pages/releaseview.action?pageId=9699433).

## Instructions

![](attachments/819203/917932.png) **Double-click on the entity.**

![](attachments/819203/917932.png) **Go to the Index tab and press the 'New' button.**

![](attachments/2621531/2752549.png)

![](attachments/819203/917932.png) **Add the desired attributes to the 'Index attributes' list and finish by pressing 'OK'.**

![](attachments/2621531/2752546.png)

Note that you will only see a performance gain if the attributes added are used in a search, and are searched for in the order they are sorted. If this is not the case you are likely to see a performance reduction since change and delete actions on objects of which the entity has an index take longer.

[![](attachments/819203/917564.png)](improve-performance-with-indexes)[(Back to Top)](improve-performance-with-indexes)