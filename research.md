---
layout: page
title: Research
---



### Delta Arrays
<img align="left" width="200" height="200" style="margin:20px 20px" src="/assets/img/research/delta_arrays.jpg" alt="">

<p style="text-align: justify;"> </p>

Dexterous manipulation capabilities of end-effectors afford us a wide range of strategies for fine-grained manipulation tasks. Recent utilization of readily available materials like soft filaments and silicone elastomers has enabled the development of low-cost mechanically intelligent robotic manipulators. This is important for democratizing robot manipulation and increasing accessibility in robotics. However, these robots generally have complex non-linear dynamics that are hard to model analytically, and even harder to learn numerically in the real world in a sample efficient manner. Towards these challenges, we propose a novel manipulator for exploring the capabilities of a complex multi-robot dexterous manipulation system and accessible hardware that can leverage these algorithms to accomplish a wide variety of tasks.

We present an array of 64 linear soft delta robots in an 8x8 hexagonal grid, for the development of new manipulation paradigms that can learn complex prehensile and non-prehensile skills in the real world. The 3D-printed soft TPU links provide mechanical compliance and allow collisions without harming the end-effector. We demonstrate dexterous manipulation capabilities of the delta array using reinforcement learning while leveraging the compliance to not break the end-effectors. Our evaluations show that the resulting 192 DoF-compliant robot is capable of performing various coordinated distributed manipulations of a variety of objects, including translation, alignment, prehensile squeezing, lifting, and grasping.

For more information, please contact [Sarvesh](https://servo97.github.io).

<!-- Check out our CHI 2020 [video presentation](https://youtu.be/ILgJDQSlgYI) to learn more. -->

<details>
<summary markdown="1" style="display: list-item;">
<h4 style="display: inline;">Relevant publications</h4>
</summary>
<div markdown="1">
{% include render_pub_list.liquid variable="projects" value="delta_robots" check="contains" %}
</div>
</details>