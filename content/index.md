---
title: CNNs from Scratch in Pytorch
---


-------------------
![[Pasted image 20240703002824.png]]


> This my blog where I discuss the CNN architectures and their implementation in Pytorch. Note that, this is not a beginner friendly introduction to CNNs, rather a reference guide for advanced Pytorch users.

----

- To see all the topics use the **Explorer** on the left. I also listed out the the topics in the following section.
- The site is optimized for **light mode**. Use the **toggle button** on top of the Explorer to switch between light mode and dark mode.
---

## Contents

#### Basics

- [[0.1 The Convolution Operation]] : Basic introduction to the convolution operation, distinction between 1D, 2D and 3D convolution
- [[0.2 Filter Bank]]: How multiple filters is used to create a filter bank 
- [[0.3 Batch Dimension]]: The batch dimension in convolution operation and how the input and output feature volume shape changes because of the batch dimension
- [[0.4 Point-Wise Convolution (1x1 Convolution)]] : Introduction to $1\times1$ convolution and how it is used to change the number of channels in output feature volume
- [[0.5 Depth-Wise Separable Convolution]]: Combination of separable convolution and pointwise convolution
- [[0.6 Terminologies]]: Additional Terminologies used in CNN related literature
## Using content from the blog

You are welcome to use any content from the blog. However, as an academic courtesy I would appreciate if you cite it.

```text
@article{chanda2024cnnpytorch,
  title   = "CNNs from Scratch in Pytorch.",
  author  = "Chanda, Dibaloke",
  journal = "https://dibalokechanda.github.io",
  year    = "2024",
  url     = "https://dibalokechanda.github.io/CNNs/"
}
```
---
## References

- https://animatedai.github.io/
- [Lecture Series](https://www.youtube.com/watch?v=dJYGatp4SvA&list=PL5-TkQAfAZFbzxjBHtzdVCWE0Zbhomg7r) by Justin Johnson from University of Michigan

> All Additional references are cited in the corresponding pages.



