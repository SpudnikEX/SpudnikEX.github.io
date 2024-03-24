---
title: "Raymarching in Rust"
last_modified_at: 2024-03-23T16:20:02-05:00
categories:
  - Blog
tags:
  - Rust
---

# Raymarching in Rust
As an exercise to better learn the fundamentals of [Rust](https://www.rust-lang.org/), what better project to get started than a raymarcher/
Rust in an embedded systems language, promising the speed of C++ while offering memory safety.

Rather than outputting , I opted to run my code through a fragment shader on the gpu using [Vulkano](https://vulkano.rs/).
Vulkano is an abstraction library that simplifies the process of window creation and rendering images through shaders. 

I will skip the details of window creation, swapchains, and buffers, as there are plenty of guides.

![](/assets/images/raymarch1.png)
![](/assets/images/raymarch2.png)
![](/assets/images/raymarch3.png)
![](/assets/images/raymarch4.gif)
![](/assets/images/raymarch5.png)

## References
[https://michaelwalczyk.com/blog-ray-marching.html](https://michaelwalczyk.com/blog-ray-marching.html)
