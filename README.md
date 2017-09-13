## Project: Perception Pick & Place
### Writeup Template: You can use this file as a template for your writeup if you want to submit it as a markdown file, but feel free to use some other method and submit a pdf if you prefer.

---
[INFO] [1505260632.503903, 997.250000]: Detected 3 objects: ['biscuits', 'soap', 'soap2']
[INFO] [1505260632.505661, 997.251000]: Starting pr2_mover with 3 objects
[INFO] [1505260632.526745, 997.258000]: Successfully output 3 objects to yaml file


[INFO] [1505260286.962225, 1107.847000]: Detected 5 objects: ['biscuits', 'book', 'soap', 'soap2', 'glue']
[INFO] [1505260286.964570, 1107.848000]: Starting pr2_mover with 5 objects
[INFO] [1505260287.005873, 1107.859000]: Successfully output 5 objects to yaml file




[INFO] [1505260464.245457, 1321.253000]: Detected 8 objects: ['snacks', 'biscuits', 'book', 'soap', 'soap2', 'soap2', 'sticky_notes', 'biscuits']
[INFO] [1505260464.248257, 1321.254000]: Starting pr2_mover with 8 objects
[INFO] [1505260464.267704, 1321.258000]: Can't Find Object: eraser
[INFO] [1505260464.276326, 1321.258000]: Can't Find Object: glue
[INFO] [1505260464.290378, 1321.261000]: Successfully output 8 objects to yaml file

---
### Writeup / README

#### 1. Provide a Writeup / README that includes all the rubric points and how you addressed each one.

You're reading it!

### Exercise 1, 2 and 3 pipeline implemented
#### 1. Complete Exercise 1 steps. Pipeline for filtering and RANSAC plane fitting implemented.

![figure_objects](/images/fig_objects.png)
![figure_table](/images/fig_table.png)

#### 2. Complete Exercise 2 steps: Pipeline including clustering for segmentation implemented.  

![figure_cluster](/images/fig_cluster.png)

#### 2. Complete Exercise 3 Steps.  Features extracted and SVM trained.  Object recognition implemented.
Here is an example of how to include an image in your writeup.

![fig_confusion_mat](fig_confusion_mat.png)
![fig_confusion_mat_normalized](fig_confusion_mat_normalized.png)

### Pick and Place Setup

#### 1. For all three tabletop setups (`test*.world`), perform object recognition, then read in respective pick list (`pick_list_*.yaml`). Next construct the messages that would comprise a valid `PickPlace` request output them to `.yaml` format.

![fig_world_1](fig_world_1.png)
![fig_world_2](fig_world_2.png)
![fig_world_3](fig_world_3.png)

Spend some time at the end to discuss your code, what techniques you used, what worked and why, where the implementation might fail and how you might improve it if you were going to pursue this project further.  
