# image_forgery_detection_papers
A collection of traditional and deep learning approaches for image forgery detection

## Deep Learning Approaches

**2015**

* J. Chen, X. Kang, Y. Liu and Z. J. Wang, "Median Filtering Forensics Based on Convolutional Neural Networks," in IEEE Signal Processing Letters, vol. 22, no. 11, pp. 1849-1853, Nov. 2015. doi: 10.1109/LSP.2015.2438008. [[Paper]](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7113799&isnumber=7118269)

**2016**

* Belhassen Bayar and Matthew C. Stamm. 2016. A Deep Learning Approach to Universal Image Manipulation Detection Using a New Convolutional Layer. In Proceedings of the 4th ACM Workshop on Information Hiding and Multimedia Security (IH&MMSec '16). ACM, New York, NY, USA, 5-10. DOI: 10.1145/2909827.2930786. [[Paper]](http://delivery.acm.org/10.1145/2940000/2930786/p5-bayar.pdf?ip=14.139.34.2&id=2930786&acc=ACTIVE%20SERVICE&key=045416EF4DDA69D9%2EADC2B0C5AAB15171%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1561014278_587f5e89629a4981558dcb024f527a2d)

* Zhang, Y., Goh, J., Win, L.L., & Thing, V.L. (2016). Image Region Forgery Detection: A Deep Learning Approach. SG-CRC.[[Paper]](https://pdfs.semanticscholar.org/613c/63818e03bbb56cbcef1d3f0061d0d37e5966.pdf)

* P. Rota, E. Sangineto, V. Conotter and C. Pramerdorfer, "Bad teacher or unruly student: Can deep learning say something in Image Forensics analysis?," 2016 23rd International Conference on Pattern Recognition (ICPR), Cancun, 2016, pp. 2503-2508. doi: 10.1109/ICPR.2016.7900012. [[Paper]](https://ieeexplore.ieee.org/abstract/document/7900012)

* Rao, Yuan and Jiangqun Ni. “A deep learning approach to detection of splicing and copy-move forgeries in images.” 2016 IEEE International Workshop on Information Forensics and Security (WIFS) (2016): 1-6. [[Paper]](https://ieeexplore.ieee.org/document/7823911)

**2017**

* Salloum, Ronald, Yuzhuo Ren and C.-C. Jay Kuo. “Image Splicing Localization Using A Multi-Task Fully Convolutional Network (MFCN).” J. Visual Communication and Image Representation 51 (2018): 201-209.[[Paper]](https://arxiv.org/abs/1709.02016)

* Fabio Carrara, Fabrizio Falchi, Roberto Caldelli, Giuseppe Amato, Roberta Fumarola, and Rudy Becarelli. 2017. Detecting adversarial example attacks to deep neural networks. In Proceedings of the 15th International Workshop on Content-Based Multimedia Indexing (CBMI '17). ACM, New York, NY, USA, Article 38, 7 pages. DOI: 10.1145/3095713.3095753. [[Paper]](https://dl.acm.org/citation.cfm?id=3095713.3095753)

* J. Ouyang, Y. Liu and M. Liao, "Copy-move forgery detection based on deep learning," 2017 10th International Congress on Image and Signal Processing, BioMedical Engineering and Informatics (CISP-BMEI), Shanghai, 2017, pp. 1-5. doi: 10.1109/CISP-BMEI.2017.8301940. [[paper]](https://ieeexplore.ieee.org/document/8301940)

* Yaqi Liu, Qingxiao Guan, and Xianfeng Zhao. 2018. Copy-move forgery detection based on convolutional kernel network. Multimedia Tools Appl. 77, 14 (July 2018), 18269-18293. DOI: 10.1007/s11042-017-5374-6 [[Paper]](https://arxiv.org/pdf/1707.01221)

**2018**

* Y. Wu, W. Abd-Almageed, and P. Natarajan. Image copymove forgery detection via an end-to-end deep neural network. In WACV, pages 1907–1915. IEEE, 2018. [[Paper]](https://www.researchgate.net/publication/324997846_Image_Copy-Move_Forgery_Detection_via_an_End-to-End_Deep_Neural_Network/citations)
* Wu, Yue, Wael Abd-Almageed and Premkumar Natarajan. “BusterNet: Detecting Copy-Move Image Forgery with Source/Target Localization.” ECCV (2018). [[Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Rex_Yue_Wu_BusterNet_Detecting_Copy-Move_ECCV_2018_paper.pdf) [[Code]](https://github.com/isi-vista/BusterNet)
* Capsule-Forensics: Using Capsule Networks to Detect Forged Images and Videos. Huy H. Nguyen, Junichi Yamagishi, Isao Echizen. [[Paper]](https://arxiv.org/abs/1810.11215)
* MesoNet: a Compact Facial Video Forgery Detection Network. Darius Afchar, Vincent Nozick, Junichi Yamagishi, Isao Echizen. [[Paper]](https://arxiv.org/pdf/1809.00888) [[Code]](https://github.com/DariusAf/MesoNet)
* Annadani, Yashas and C. V. Jawahar. Augment and Adapt: A Simple Approach to Image Tampering Detection. [[Paper]](http://yashasannadani.com/assets/publications/2018_icpr/paper.pdf)

**2019**

* Seunghoon Hong, Tackgeun You, Suha Kwak, Bohyung Han, Online Tracking by Learning Discriminative Saliency Map with Convolutional Neural Network, arXiv:1502.06796. [[Paper]](http://arxiv.org/pdf/1502.06796)


# Datasets Available

## Image Forgery
* [CASIA V1 & V2 Dataset](https://www.kaggle.com/sophatvathana/casia-dataset)
* [CoMoFoD](http://www.vcl.fer.hr/comofod/comofod.html)
* [GRIP](http://www.grip.unina.it/research/83-image-forensics/88-copy-of-mdka-843.html)
* [Columbia Image-Splicing](http://www.ee.columbia.edu/ln/dvmm/downloads/AuthSplicedDataSet/AuthSplicedDataSet.htm)
* [Face Forensics](https://github.com/ondyari/FaceForensics) [[Paper]](https://arxiv.org/pdf/1901.08971.pdf) 

## Deepfakes

| dataset | manipulations | # pristine/forged| frame size | format |
| :---         |     :---     |       :---: | :---: | :---: |
| DF-TIMIT | deepfake |  -/620 | 64x64 - 128x128 | JPG |
| FFW    |deepfake, splicing, CG | -/150 | 480p, 720p, 1080p | H.264 |  
| FaceForensics++ | deepfake, CG-manipulations | 1000/4000 | 480p, 720p, 1080p | H.264, CRF=0, 23, 40 |
| Celeb-DF | deepfake | 529/5639 | various | MPEG4 |
| DFDC | deepfake | 19154/100,000|  240p - 2160p |H.264 |
