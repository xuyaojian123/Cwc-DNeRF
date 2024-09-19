## :book: Cwc-DNeRF: Compact Dynamic Neural Radiance Field via Discrete Wavelet Transform and Learnable Codebooks
<img src=".\images\framework.jpg" style="zoom:60%;" />

<p align="center">
  <small>:fire: If you found the Cwc-DNeRF is useful, please help to :star: it or recommend it to your friends. Thanks:fire:</small>
</p>



# Abstract
The emergence of Neural Radiance Field (NeRF) has significantly impacted dynamic scene reconstruction and photorealistic novel view synthesis rendering. However, using multiple implicit multi-layer perceptrons (MLPs) to represent dynamic scenes requires significant computational resources and time. Recent studies have explored reducing the computation times by introducing explicit data structures such as voxel meshes or feature planes. Despite promising performance gains, the explicit data structure leads to a model that requires many storage requirements, which is not conducive to network transmission. Therefore, we propose Cwc-DNeRF, a compact dynamic NeRF representation via discrete wavelet transform (DWT) and learnable codebooks, which achieves competitive rendering quality and higher storage efficiency compared to the baseline K-Planes through a two-stage training process and a compression pipeline. In Stage I, we apply the DWT and trainable masks to maximize parameter efficiency and obtain highly sparse space planes. Then, in Stage II, we build on the optimized space-time planes, introducing a novel training scheme for learnable codebooks to merge similar latent codes, effectively address spatiotemporal feature redundancy, and further reduce storage overhead. Finally, we demonstrate how to compress the sparse space plane parameters and codebooks using a data compression pipeline. Experimental results on the D-NeRF and DyNeRF datasets demonstrate that without compromising the advantages of explicit feature plane data structure, our method achieves state-of-the-art dynamic scene rendering quality within a 10MB storage budget.

# News

:fire: The code will be made publicly available soon. Thanks  for your attention.

