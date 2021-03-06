A parallelized motion detection implementation of Yi et al.’s dual-mode SGM background subtraction model. 

If you use our implementation please cite:

@article{henderson2017analysis,
  title={An Analysis of Parallelized Motion Masking Using Dual-Mode Single Gaussian Models},
  author={Henderson, Peter and Vertescher, Matthew},
  journal={arXiv preprint arXiv:1702.05156},
  year={2017}
}


Main Paper Citation Dual-Mode Single Gaussian Models:

@inproceedings{yi2013detection,
  title={Detection of Moving Objects with Non-stationary Cameras in 5.8 ms: Bringing Motion Detection to Your Mobile Device},
  author={Yi, Kwang Moo and Yun, Kimin and Kim, Soo Wan and Chang, Hyung Jin and Choi, Jin Young},
  booktitle={Computer Vision and Pattern Recognition Workshops (CVPRW), 2013 IEEE Conference on},
  pages={27--34},
  year={2013},
  organization={IEEE}
}


The CUDA implementation of our code is in the cuda folder. Both the serial and parallelized tbb versions of our code reside in the same folder: serial_and_tbb. They can both be seen in the main.cpp and DualSGM.cpp files.


