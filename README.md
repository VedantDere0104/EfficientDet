# EfficientDet: Scalable and Efficient Object Detection :- 

Pytorch implementation of EfficientDet .

## Abstract :- 
Model efficiency has become increasingly important in
computer vision. In this paper, we systematically study neural network architecture design choices for object detection
and propose several key optimizations to improve efficiency.
First, we propose a weighted bi-directional feature pyramid network (BiFPN), which allows easy and fast multiscale feature fusion; Second, we propose a compound scaling method that uniformly scales the resolution, depth, and
width for all backbone, feature network, and box/class prediction networks at the same time. Based on these optimizations and better backbones, we have developed a new family
of object detectors, called EfficientDet, which consistently
achieve much better efficiency than prior art across a wide
spectrum of resource constraints. In particular, with singlemodel and single-scale, our EfficientDet-D7 achieves stateof-the-art 55.1 AP on COCO test-dev with 77M parameters and 410B FLOPs1
, being 4x – 9x smaller and using
13x – 42x fewer FLOPs than previous detectors.

## Architecture :- 

### BiFPN Layer :- 
![image](https://user-images.githubusercontent.com/76057253/135388995-c12b2710-36f3-4bad-abf8-156c1eda2390.png)

### EfficientDet Model with EfficientNet as a backbone and BiFPN layer as a Neck .
![image](https://user-images.githubusercontent.com/76057253/135389059-6c6007b4-fcd0-4d43-ae0a-a4b1ba049422.png)

![image](https://user-images.githubusercontent.com/76057253/135389124-371eb159-8e08-420a-aed5-f6dcc7d5192f.png)


## Results :- 

![image](https://user-images.githubusercontent.com/76057253/135389154-bcd3df37-7395-457b-8478-3d2e426c9e17.png)

![image](https://user-images.githubusercontent.com/76057253/135389187-581f460a-3459-4545-8e23-1dfae08efda4.png)

```
@misc{tan2020efficientdet,
      title={EfficientDet: Scalable and Efficient Object Detection}, 
      author={Mingxing Tan and Ruoming Pang and Quoc V. Le},
      year={2020},
      eprint={1911.09070},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
