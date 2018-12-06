---
layout: post
title: Let's Plot With Matplotlib
tags: [matplotlib, python3.0, graph, machine_learning]
---

Let's Plot With Matplotlib

A picture is worth a thousand words. Leaning through images is great. You get more information by looking at some graph or image rathar than reading about it. Same goes with machine learning. Data analysis, data visualization etc are essential for a data engineer and data scientist. 
There are lot of plotting library but Matplotlib is one of my favourite lib when it comes to working with graph. Visualization data with Matplotlib is great. 

Let's draw a small figure before we go in depth : 

```
# Import the necessary packages and modules
import matplotlib.pyplot as plt
import numpy as np

# Prepare the data
x = np.linspace(0, 10, 50)

# Plot the data
plt.plot(x, x, label='linear graph')
plt.legend()

# Show the plot - important 
plt.show()
```

Output - 

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

We have jsut created a simple graph. The beauty of Matplotlib is that it can be customize 100%. We can add label, legend, title, fontsize etc. Let's modify our grapgh and add some basic features - 
Whatever you want to customize, it must be added before the show() function call.

```
import matplotlib.pyplot as plt
import numpy as np

x = np.linspace(0, 10, 50)

plt.plot(x, x, label='linear graph')
plt.legend()
plt.xlabel("X Axis")
plt.ylabel("Y Axis")
plt.title("Simple linear graph.")
plt.show()
```

Not output would be like below - 

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

