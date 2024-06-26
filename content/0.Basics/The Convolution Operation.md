Depending on your background you may have different interpretation of the convolution operation. However, the convolution operation is fundamentally different in convolutional neural networks which often causes confusion. Below I clarify some of these confusions:

### Convolution or Cross-Correlation ?

If you come from the signal processing world, you will know the kernel in the convolution operation is flipped before the convolution operation. If you do not flip the kernel it has a different name "Cross-Correlation". 

In convolutional neural network, we actually perform cross-correlation instead of convolution because the kernel is not flipped.

### Why Conv2D ?


![[Pasted image 20240626123635.png]]





