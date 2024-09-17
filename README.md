[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/i4hXRRHN)
# introduction-to-plotting

## Learning Objectives

This repository contains three Jupyter notebooks designed to improve your understanding of creating and customizing visualizations using Matplotlib and related tools.

### 1. Plotting with Matplotlib
In this notebook, you will learn how to:
- Build a **reusable plotting function** for creating custom line plots.
- Customize line styles, labels, axis limits, and subplots for multiple datasets.

### 2. Contour Plots with Matplotlib
In this notebook, you will learn how to:
- Create **contour plots** to visualize 3D data in 2D space.
- Use **filled contours** with `plt.contourf()` and **labeled contours** with `plt.contour()` and `plt.clabel()`.
- Customize plot properties, such as colormaps, axis labels, gridlines, and color bars.
- Build **reusable plotting functions** to streamline your workflow.

### 3. Interactive Plots with Ipywidgets
In this notebook, you will learn how to:
- Use **`ipywidgets`** to create **dynamic visualizations** that allow user interaction.
- Dynamically customize filled contour plots based on user input.
- Visualize and manipulate a mathematical function:
  
  $f(q_1, q_2) = k_1 \cdot q_1^2 + k_2 \cdot q_2^2 + c \cdot q_1 \cdot q_2$
  
- Adjust plot parameters like contour range and number of contours in real-time.


---

## Assignment
In this assignment, you will create your own Jupyter Notebook with a multipanel figure and sliders to explore the response of anharmonically coupled oscillators.

### Background:
An important area of research in the last decade has been the study of the following model of coupled oscillators. See, for example, this review article, if you'd like to explore why: [**Engineering Crystal Structures with Light**](https://www.nature.com/articles/s41567-021-01366-1).

$U(Q_1,Q_2) = \frac{1}{2} K_1 Q_1^2 + \frac{1}{2} K_2 Q_2^2 + C Q_1 Q_2^2$

In this exercise, we will explore why people are interested in this model by using side-by-side plots, like those derived in the Jupyter Notebooks for this week.

### Preparation:
Review the construction of plots from this week's notebooks with `matplotlib` using `plt.plot` and `plt.contourf`, and the use of `ipywidgets`.

### Getting started:
Create a Jupyter Notebook which defines the energy above and plots in two side-by-side panels:

- Plot $U(Q_1,Q_2)$ with $Q_1$ on the horizonal axis adn $Q_2=0$;
- Add several lines with fixed positive and negative values of $Q_2$ chosen to explore the possible effect of $Q_2$ on $Q_1$;
- Add a second panel which plots $U(Q_1,Q_2)$;
- Add an `ipywidgets` environment so that you can explore what different values of $K_1$, $K_2$, and $C$ does to your plot.
- Make sure that your axes are labeled and that you have a plot legend, if appropriate.

### Explore the physics
After tinkering with your plots, answer the following questions:

1. As you increase $C$, how do the low-energy contours start to change?
2. Does the force on $Q_1$ depend on the direction of $Q_2$?
3. What do you expect the influence of driving $Q_2$ to be on the motion of $Q_1$?
3. If $Q_1$ is kicked away from equilibrium, what do you expect its influence to be on $Q_2$?

