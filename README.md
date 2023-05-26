# STR_benchmark_cleansed

## Six Popular Benchmark Datasets

Download cleansed lmdb datasets for the six benchmarks from [BaiduCloud](https://pan.baidu.com/s/1VGJR43eBbxpk-hZ9MVf62A)(psw:rnso) or [GoogleDrive](https://drive.google.com/file/d/1xFYOGCNUdUwHdnDWk2fQVHmlSBcEV3zG/view?usp=sharing).

Despite the widespread use of the six benchmarks (IIIT5k[1], SVT[2], IC13[3], IC15[4], SVTP[5] and CUTE[6]) for scene text recognition, we have noticed that there are mislabeled images in the benchmark. Baek et al.[7] provided a version of cleansed labels for benchmark datasets. However, there are still several mislabeled images. We conduct further verification of these labels. The mislabeled examples can be classified into three types: missing character, alphabetic error, and completely wrong. Hope the cleansed benchmark datasets to ensure a more accurate evaluation of scene text recognition models. If you notice that there are still mistakes, please point out that and we can update the labels of the benchmarks.

## Other Datasets

Total-text[8] and CTW-1500[9] are supplemental datasets that are often employed due to their substantial inclusion of rotated or curved texts, consisting of 2201 and 1572 evaluation images respectively. In our review of these two datasets, we identified and corrected 43 mislabeled images in Total-Text and 115 in CTW-1500. Download the rechecked lmdb datasets for Total-Text and CTW1500 from [BaiduCloud](https://pan.baidu.com/s/1lDuEXguSF9njS7Ddz769ug)(psw:sd7f) or [GoogleDrive](https://drive.google.com/file/d/1L-9BoUQ8PRO4_3qhqQBCSlYILyPOOQmz/view?usp=sharing).

## Reference
[1] A. Mishra, K. Alahari, and C. Jawahar. Scene text recognition using higher order language priors. In BMVC, 2012.

[2] K. Wang, B. Babenko, and S. Belongie. End-to-end scenetext recognition. In ICCV, pages 1457–1464, 2011.

[3] D. Karatzas, F. Shafait, S. Uchida, M. Iwamura, L. G. i Big-orda, S. R. Mestre, J. Mas, D. F. Mota, J. A. Almazan, andL. P. De Las Heras. ICDAR 2013 robust reading competition. In ICDAR, pages 1484–1493, 2013.

[4] D. Karatzas, L. Gomez-Bigorda, A. Nicolaou, S. Ghosh, A. Bagdanov, M. Iwamura, J. Matas, L. Neumann, V. R.Chandrasekhar, S. Lu, et al. ICDAR 2015 competition on ro-bust reading. In ICDAR, pages 1156–1160, 2015.

[5] T. Q. Phan, P. Shivakumara, S. Tian, and C. L. Tan. Recognizing text with perspective distortion in natural scenes. In ICCV, pages 569–576, 2013.

[6] A. Risnumawan, P. Shivakumara, C. S. Chan, and C. L. Tan. A robust arbitrary text detection system for natural scene images. In ESWA, volume 41, pages 8027–8048, 2014.

[7] J. Baek, G. Kim, J. Lee, S. Park, D. Han, S. Yun, S. J. Oh, and H. Lee. 2019. What is wrong with scene text recognition model comparisons? dataset and model analysis. In CVPR, pages 4715–4723, 2019.

[8] C.-K. Cj'ng, C. S. Chan, and C.-L. Liu. Total-text: toward orientation robustness in scene text detection. In IJDAR, pages 1–22, 2019.

[9] Y. Liu, L. Jin, S. Zhang, C. Luo, and S. Zhang. Curved scene text detection via transverse and longitudinal sequence connection. In Pattern Recognition, 90:337–345, 2019.
