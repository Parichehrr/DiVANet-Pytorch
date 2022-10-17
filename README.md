# DiVANet-PyTorch
### This is repository is an official PyTorch implementation of the paper "Single image super-resolution based on directional variance attention network".
Pattern Recognition, 2022. [[Paper](https://www.sciencedirect.com/science/article/pii/S0031320322004770?dgcid=author)] 

### Abstract 
Recent advances in single image super-resolution (SISR) explore the power of deep convolutional neural networks (CNNs) to achieve better performance. However, most of the progress has been made by scaling CNN architectures, which usually raise computational demands and memory consumption. This
makes modern architectures less applicable in practice. In addition, most CNN-based SR methods do not fully utilize the informative hierarchical features that are helpful for ﬁnal image recovery. In order to address these issues, we propose a directional variance attention network (DiVANet), a computationally eﬃcient yet accurate network for SISR. Speciﬁcally, we introduce a novel directional variance attention (DiVA) mechanism to capture long-range spatial dependencies and exploit inter-channel dependencies simultaneously for more discriminative representations. Furthermore, we propose a residual attention feature group (RAFG) for parallelizing attention and residual block computation. The output of each residual block is linearly fused at the RAFG output to provide access to the whole feature hierarchy. In parallel, DiVA extracts most relevant features from the network for improving the ﬁnal output and preventing information loss along the successive operations inside the network. Experimental results demonstrate the superiority of DiVANet over the state of the art in several datasets, while maintaining relatively low computation and memory footprint.

<img src="assets/Main_Figure.pdf">
