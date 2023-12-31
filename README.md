# A Diffusion-Based Reconstruction Technique for Single Pixel Camera

Single-pixel imaging enables high-resolution imaging through multiple coded measurements based on low-resolution snapshots. To reconstruct a high-resolution image from these coded measurements, an ill-posed inverse problem is solved. Despite the recent popularity of deep learning-based methods for single-pixel imaging reconstruction, they are insufficient in preserving spatial details and achieving stable reconstruction. Diffusion-based methods, which have gained attention in recent years, provide a solution to this problem. In this study, to the best of our knowledge, single-pixel image reconstruction is performed for the first time using a denoising diffusion probabilistic model. The proposed method reconstructs the image by conditioning it towards the least squares solution while preserving data consistency after unconditional training of the model. The proposed method is compared against existing single-pixel imaging methods, and ablation studies are conducted to demonstrate the individual model components. The proposed method outperforms competing methods in both quantitative measurements and visual quality.

## Proposed Architecture

<div align="center">
  <img src="https://github.com/baturalpguven/A-Diffusion-Based-Reconstruction-Technique-for-Single-Pixel-Camera/assets/77858949/dce051f0-b657-4769-a8e7-d5795f1bc690.png" alt="Figure 1: Proposed Architecture">
  <p><em>Figure 1: Proposed Architecture</em></p>
</div>

## Results

<div align="center">
  <img src="https://github.com/baturalpguven/A-Diffusion-Based-Reconstruction-Technique-for-Single-Pixel-Camera/assets/77858949/accfc9bf-3972-462c-82c5-4a2ef82619df.png" alt="Figure 2: Reconstruction Results">
  <p><em>Figure 2: (a) Original image, (b) LS, (c) TV, (d) TVFL1, (e) without additional refinement, and (f) images reconstructed using the proposed model.</em></p>
</div>

## Link

For more details, please refer to the [IEEE Xplore document](https://ieeexplore.ieee.org/document/10223811/keywords#keywords) on the A Diffusion-Based Reconstruction Technique for Single Pixel Camera.
