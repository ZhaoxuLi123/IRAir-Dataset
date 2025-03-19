# IRAir Dataset
This is the official repository for IRAir dataset in ["A lightweight dark object detection network for infrared images"](http://journal.sitp.ac.cn/hwyhmb/hwyhmben/article/abstract/2024116?st=article_issue).

## Abstract
Small target detection has been a classic research topic in the field of infrared image processing， and the objects are usually brighter than the local background. However， in some scenarios， the target brightness may be lower than the background brightness. For example， the civil airplanes usually have low-temperature skin when cruising， appearing as dark points on medium spatial resolution thermal infrared satellite images. There are few features of these objects， so the current detection networks are redundant. Hence， we proposed a lightweight dark object detection network， AirFormer. It only has 37.1 K parameters and 46.2 M floating-point operations on a 256×256 image. Considering the lack of infrared dark object detection dataset， the authors analyzed the characteristics of airplanes on thermal infrared satellite images， and then developed a simple simulation method for medium spatial resolution thermal infrared satellite images of civil aviation aircrafta， and constructed an infrared image weak target detection dataset IRAir using civil aviation aircraft as the simulation object. AirFormer achieves 71.0% at recall and 82.6% at detection precision on the IRAir dataset. In addition， after training on simulated data， AirFormer has achieved detection of real flying airplanes on the thermal infrared satellite images.


## Contact

If you need the IRAir dataset, please directly reach out to lizhaoxu@nudt.edu.cn.

## Citation

If the work or the code is helpful, please cite the paper:
```
@article{li2024specdetr,
  title = {A lightweight dark object detection network for infrared images},
  author ={Li, Zhaoxu and Xu, Qingxu and An, Wei and He, Xu and Guo, Gaowei and Li, Miao and Ling, Qiang and Wang, Longguang and Xiao, Chao and Lin, Zaiping}
 journal = {Journal of Infrared and Millimeter Waves},
 volume = {44},
 number = {2},
 pages = {285},
 numpages = {12},
 year = {2025},
 month = {04},
 doi = {10.11972/j.issn.1001-9014.2025.02.016},
}


```
