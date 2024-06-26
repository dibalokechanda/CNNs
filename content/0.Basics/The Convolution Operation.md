Depending on your background you may have different interpretation of the convolution operation. However, the convolution operation is fundamentally different in convolutional neural networks which often causes confusion. Below I clarify some of these confusions:

### Convolution or Cross-Correlation ?

If you come from the signal processing world, you will know the kernel in the convolution operation is flipped before the convolution operation. If you do not flip the kernel it has a different name "Cross-Correlation". 

In convolutional neural network, we actually perform cross-correlation instead of convolution because the kernel is not flipped.

### Review of 1D convolution

>Note that, all convolution operation (actually cross-correlation) in this blog is discrete in nature. Also, rather than using the word "signal", the word "feature" is used which is the common terminology in the ML world.

-------------

In the following diagram each `cube` represents a single scalar value.  The input feature is shown in blue, the convolutional kernel is shown in orange and the resultant 1D output feature is shown in green.

![[Pasted image 20240626131134.png]]

Look at the following diagram which summarizes the main concept behind how convolution operation happens.

![[Pasted image 20240626123635.png]]

We take the 1D convolutional kernel (which is 1x3 dimensional and colored in orange ) and align it with a certain section of the 1D feature. For the ease of visualization I showed that certain section separately (colored in purple). Also, to explicitly intuit how the alignment works, a I used a darker color to indicate the center. The next step is performing an element-wise multiplication followed by a summation operation.







