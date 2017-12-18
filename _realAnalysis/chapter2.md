---
layout: realAnalysisBlog
permalink: /realAnalysis/chapter2
title: Rudin Chapter 2
---

# Major Theorems and Definitions

## Definition 15
Here, we will visualize many of the new terms given in this definition.  For all of these definitions, $X$ is a metric space with a distance function $d$.

* Neighborhoods: a **neighborhood** of $p$ is a set $N_r(p)$ consisting of all $q$ such that $d(p,q) < r$ for some $r > 0$.  The number $r$ is the **radius** of $N_r(p)$.  

The below image helps to visualize a neighborhood in $E$.  

![2_15_1](chapter2Assets/2_15_1.png)

Note that $N_r(p)$ is not necessarily the entirety of the shaded orange region, but rather the collection of points $q_i$ within that region (representing a distance less than $r$ away from $p$).  

* A point $p$ is a **limit point** of the set $E$ if every neighborhood of $p$ contains a point $q \neq p$ such that $q \in E$.

![2_15_2](chapter2Assets/2_15_2.png)

Here, we can see that no matter the distance $r$ for each neighborhood, there still is a point $q_i$ in $N_r(p)$ where $q_i \in E$.  

* If $p \in E$ and $p$ is not a limit point of $E$, then $p$ is called an **isolated point**.

The essence of an isolated point is that there can be a radius $r$ such that $N_r(p)$ does not contain any point $q_i \in E$.  For example, $p$ below is an isolated point:

![2_15_3](chapter2Assets/2_15_3.png)
