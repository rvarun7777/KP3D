# Self-Supervised 3D Keypoint Learning for Ego-motion Estimation
Code coming soon.

## Overview
![](https://raw.githubusercontent.com/TRI-ML/KP3D/master/media/imgs/teaser.png)
![](https://raw.githubusercontent.com/TRI-ML/KP3D/master/media/gifs/tracking.gif)
![](https://raw.githubusercontent.com/TRI-ML/KP3D/master/media/gifs/demo.gif)

- **Sparse mono-SfM:** A new framework for the simultaneous learning of keypoint detection, matching and 3D lifting by incorporating a differentiable pose estimation module.
- **Multi-view adaptation:**  A novel adaptation technique that exploits the temporal context in videos to further boost the repeatability and matching performance of the keypoint network. 
- **State-of-the-art performance:** We integrate the networks into a visual odometry framework, enabling robust and accurate ego-motion estimation results

[**[Full paper]**](https://arxiv.org/abs/1912.03426) [**[YouTube]**](https://www.youtube.com/watch?v=4hFhSD8QUPM)

## Trajectories
Trajectories of DS-DSO on KITTI odometry sequences 00-10: [ds_dso_kitti_00_10.zip](https://raw.githubusercontent.com/TRI-ML/KP3D/master/trajectories/ds_dso_kitti_00_10.zip?token=AFNBHBZSND3KKTPGUO3OKXC56SEBM).
We also include the results of our ablative analysis as well as our evaluation of [monodepth2](https://github.com/nianticlabs/monodepth2).

<p align="center">
  <img src="media/plots/seq05.png" alt="trajectory seq05" width="600" />
  <img src="media/plots/seq07.png" alt="trajectory seq07" width="600" />
</p>

## Citation
Please use the following citation when referencing our work:
```
@misc{selfsupkp3d2019,
  title = {{Self-Supervised 3D Keypoint Learning for Ego-motion Estimation}},
  author = {Jiexiong Tang and Rares Ambrus and Vitor Guizilini and Sudeep Pillai and Hanme Kim and Adrien Gaidon},
    year={2019},
    eprint={1912.03426},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}
```