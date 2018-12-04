---
layout: post
title: Let's Plot With Matplotlib
tags: [matplotlib, python3.0, graph, machine_learning]
---

Let's Plot With Matplotlib

A picture is worth a thousand words. Leaning through images is great. You get more information by looking at some graph or image rathar than reading about it. Same goes with machine learning. Data analysis, data visualization etc are essential for a data engineer and data scientist. 
There are lot of plotting library but Matplotlib is one of my favourite lib when it comes to working with graph. Visualization data with Matplotlib is great. 

Let's draw a small figure before we go in depth : 

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


