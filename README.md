## Codes for CPL attacks

This is the prototype code for ESORICS 2020 A Framework for Evaluating Gradient Leakage Attacks in Federated Learning. The talk can be found here:  <a href="https://www.youtube.com/watch?v=BNGpv4AW80g" target="_blank">talk</a>. Check out our [project page](https://git-disl.github.io/ESORICS20-CPL/)

### Examples

|  | ours | DLG |
|:---:|:---:|:---:|
| MNIST| ![mnist_ours](demo/mnist_ours.gif) | ![mnist_dlg](demo/mnist_dlg.gif) |
| CIFAR10| ![cifar10_ours](demo/cifar10_ours.gif) | ![cifar10_dlg](demo/cifar10_dlg.gif) |
| LFW| ![lfw_ours](demo/lfw_ours.gif) | ![lfw_dlg](demo/lfw_dlg.gif) |





### Here is a brief description of each file in the CPL folder.

LFW_enhanced_random_ASR.ipynb: CPL attack with geometric initialization

LFW_batch.ipynb: CPL attack in batch

LFW128_enhanced_random_ASR.ipynb: CPL attack with resolution 128*128. Same applies to LFW64_enhanced_random_ASR.ipynb

LFW_defense.ipynb: CPL attack under high-pass filter and additive noise


### Here is a brief description of each file in the DLG folder.

LFW_Deep_Leakage_from_Gradients.ipynb: lfw implementation for DLG attack in (NIPS2019) "Deep leakage from gradients."

### Here is a brief description of each file in the GradInversting folder.

Attack from NeurIPS 2020: Geiping, Jonas, Hartmut Bauermeister, Hannah Dröge, and Michael Moeller. "Inverting Gradients--How easy is it to break privacy in federated learning?." 
To run, you may find more details [here](https://github.com/JonasGeiping/invertinggradients)



If you use our code, please cite:

```
Wei, Wenqi, Ling Liu, Margaret Loper, Ka-Ho Chow, Mehmet Emre Gursoy, Stacey Truex, and Yanzhao Wu. "A Framework for Evaluating Client Privacy Leakages in Federated Learning." In European Symposium on Research in Computer Security, pp. 545-566. Springer, Cham, 2020.
...

