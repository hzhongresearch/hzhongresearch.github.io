## Henry Zhong Research

I am always on the lookout for interesting projects. If you would like to collaborate on research or work, contact me using: hhcz728 (at) gmail (dot) com .

Research Interests:

* Ubiquitous Computing
* Computer Vision

## Publications

Google Scholar [Link](https://scholar.google.com/citations?user=GSA0YwsAAAAJ&hl=en)
ResearchGate [Link](https://www.researchgate.net/profile/Henry_Zhong)

* Zhong, Henry. "Lightweight Algorithms for Depth Sensor Equipped Embedded Devices." School of Computer Science & Engineering, Faculty of Engineering, UNSW, 2017. [PDF](https://www.researchgate.net/profile/Henry-Zhong/publication/330383222_Lightweight_Algorithms_for_Depth_Sensor_Equipped_Embedded_Devices/links/5c3d595992851c22a375cbb3/Lightweight-Algorithms-for-Depth-Sensor-Equipped-Embedded-Devices.pdf)
* Zhong, Henry, Salil S. Kanhere, and Chun Tung Chou. "VeinDeep: Smartphone unlock using vein patterns." Pervasive Computing and Communications (PerCom), 2017 IEEE International Conference on. IEEE, 2017. [PDF](https://www.researchgate.net/profile/Henry-Zhong/publication/316733062_VeinDeep_Smartphone_unlock_using_vein_patterns/links/59d8733faca272e609644c07/VeinDeep-Smartphone-unlock-using-vein-patterns.pdf)
* Zhong, Henry, Salil S. Kanhere, and Chun Tung Chou. "WashInDepth: Lightweight Hand Wash Monitor Using Depth Sensor." Proceedings of the 13th International Conference on Mobile and Ubiquitous Systems: Computing, Networking and Services. ACM, 2016. [PDF](https://www.researchgate.net/profile/Henry-Zhong/publication/310742284_WashInDepth_Lightweight_Hand_Wash_Monitor_Using_Depth_Sensor/links/59d87365aca272e6096451a8/WashInDepth-Lightweight-Hand-Wash-Monitor-Using-Depth-Sensor.pdf)
* Zhong, Henry, Salil S. Kanhere, and Chun Tung Chou. "QuickFind: Fast and contact-free object detection using a depth sensor." Pervasive Computing and Communication Workshops (PerCom Workshops), 2016 IEEE International Conference on. IEEE, 2016. [PDF](https://www.researchgate.net/profile/Henry-Zhong/publication/301583832_QuickFind_Fast_and_contact-free_object_detection_using_a_depth_sensor/links/59d87384a6fdcc2aad0b1658/QuickFind-Fast-and-contact-free-object-detection-using-a-depth-sensor.pdf)

## Code/Data Samples

### VeinDeep
<img src="https://hzhongresearch.github.io/veindeep_image.png" width="400">

VeinDeep is a system which uses an infrared (IR) depth sensor to extract vein patterns from a person's hand. The idea is in the future smartphones will be equipped with Kinect V2 like IR depth sensors. Such sensors can be used to identify the smartphone owner using vein patterns and provide a way to unlock the phone.

This project was created during my PhD. The associated research paper was presented at PerCom 2017. My research is in Ubiquitous Computing and Computer Vision. If you use this work please consider citing our paper.

```
@inproceedings{zhong2017veindeep,
	title={VeinDeep: Smartphone unlock using vein patterns},
	author={Zhong, Henry and Kanhere, Salil S and Chou, Chun Tung},
	booktitle={Pervasive Computing and Communications (PerCom), 2017 IEEE International Conference on},
	pages={2--10},
	year={2017},
	organization={IEEE}
}
```

### QuickFind
<img src="https://hzhongresearch.github.io/quickfind_image.png" width="400">

QuickFind is a fast segmentation and object detection algorithm using only depth maps. Depth maps are images captured from depth sensors like Kinect. The idea is in the future depth sensors will be common so such an algorithm will be useful.

The data contains amended ground truth of the RGB-D Scenes dataset used in the QuickFind paper. The ground truth in the original RGB-D scenes dataset had many errors so I manually traced out the location of each object. Credit for RGB-D Scenes goes to Lai et al. Please visit their [site](https://rgbd-dataset.cs.washington.edu/dataset.html) and credit them if you use my amended data in conjunction with their RGB-D Scenes dataset.


This project was created during my PhD. The associated research paper was presented at PerCom Workshops 2016. My research is in Ubiquitous Computing and Computer Vision. If you use this work please consider citing our paper.

```
@inproceedings{zhong2016quickfind,
	title={Quickfind: Fast and contact-free object detection using a depth sensor},
	author={Zhong, Henry and Kanhere, Salil S and Chou, Chun Tung},
	booktitle={Pervasive Computing and Communication Workshops (PerCom Workshops), 2016 IEEE International Conference on},
	pages={1--6},
	year={2016},
	organization={IEEE}
}
```
