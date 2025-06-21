# Indoor Panoramic Depth Estimation via Dual-Projection Feature Fusion and Structural Refinement

## INTRODUCTION

Accurate depth estimation from indoor panoramic images is crucial for virtual reality and robotic perception. However, existing methods suffer from distortion near the poles due to equirectangular mapping and spatial discontinuities at the boundaries when using cube mapping. These issues lead to inaccuracies in the predicted indoor panoramic depth maps. This study proposes a novel multi-feature fusion framework that innovatively incorporates room structure features alongside image-based depth prediction. The framework focuses on efficiently fusing room structure information with previously extracted features to obtain more accurate depth estimates. Experimental results in the Joint 2D-3D-Semantic and Structured3D datasets demonstrate that the proposed approach outperforms the state-of-the-art methods, reducing the absolute error by 8\% and the absolute relative difference by 11.7\% on the Joint 2D-3D-Semantic dataset, and get better subjective depth images on the Structured3D dataset.

## Experimental results

Analyzing the two datasets together, we observe that our network performs more robustly on complex real-world indoor environments, where room geometry is more irregular. While methods like ACDNet perform slightly better in synthetic or more structured scenes, our method extracts more informative cues from cluttered environments and distorted regions. As shown in the result, we can see that our network can get the depth information of the vertical wall better, while other networks may have some pixel errors. 
