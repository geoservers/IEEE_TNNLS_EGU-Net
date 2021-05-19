# Endmember-Guided Unmixing Network (EGU-Net): A General Deep Learning Framework for Self-Supervised Hyperspectral Unmixing

[Danfeng Hong](https://sites.google.com/view/danfeng-hong), [Lianru Gao](https://scholar.google.com/citations?hl=en&user=f6OnhtcAAAAJ), [Jing Yao](https://scholar.google.com/citations?user=1SHd5ygAAAAJ&hl=en), [Naoto Yokoya](https://naotoyokoya.com/), [Jocelyn Chanussot](http://jocelyn-chanussot.net/), [Uta Heiden](https://scholar.google.de/citations?user=xgKwyocAAAAJ&hl=de), [Bing Zhang](http://english.radi.cas.cn/Education/PhDS/201401/t20140109_115415.html)

___________

The code in this toolbox implements the ["Endmember-Guided Unmixing Network (EGU-Net): A General Deep Learning Framework for Self-Supervised Hyperspectral Unmixing"](https://ieeexplore.ieee.org/document/9174822). More specifically, it is detailed as follow.

![alt text](./Motivation.png)


Citation
---------------------

**Please kindly cite the papers if this code is useful and helpful for your research.**

Danfeng Hong, Lianru Gao, Jing Yao, Naoto Yokoya, Jocelyn Chanussot, Uta Heiden, Bing Zhang. Endmember-Guided Unmixing Network (EGU-Net): A General Deep Learning Framework for Self-Supervised Hyperspectral Unmixing, IEEE Transactions on Neural Networks and Learning Systems, 2020, DOI: 10.1109/TNNLS.2021.3082289. 

     @article{hong2021endmember,
      title     = {Endmember-Guided Unmixing Network (EGU-Net): A General Deep Learning Framework for Self-Supervised Hyperspectral Unmixing},
      author    = {D. Hong and L. Gao and J. Yao and N. Yokoya and J. Chanussot and U. Heiden and B. Zhang},
      journal   = {IEEE Trans. Neural Netw. Learn. Syst.}, 
      year      = {2021},
      note      = {DOI: 10.1109/TNNLS.2021.3082289},
      publisher = {IEEE}
     }

System-specific notes
---------------------
The data were generated by Matlab R2016a or higher versions, and the codes of various networks were tested in Tensorflow 1.14 version in Python 3.7 on Windows 10 machines.

How to use it?
---------------------
This toolbox consists of two different network architectures, i.e., fully-connected networks (FC-Nets), convolutional neural networks (CNNs). Each of network architectures also includes different fusion networks. For more details, please refer to the paper.

Google drive: https://drive.google.com/file/d/1vno8vQxCXgr7xk-Nez9CVbJmjkDMBCbe/view?usp=sharing

Baiduyun: https://pan.baidu.com/s/1ug_tKyrbwg_CzHGpB2YK2A (access code: hfw3)


**If you are interested in LCZ classification datasets, please download them from here: [Baiduyun](https://pan.baidu.com/s/1dYkaUm4JTjOWdtx79RsB6w) with access code (gkli)!**

**The images are normalized (0-1) in a band-wise fashion. In our case, we use the matlab function: mat2gray.**

**The multimodal image resolution might be different, e.g., in LCZ. We use the matlab function: imresize.**

If you want to run the code in your own data, you can accordingly change the input (e.g., data, labels) and tune the parameters.

If you encounter the bugs while using this code, please do not hesitate to contact us.

Licensing
---------

Copyright (C) 2020 Danfeng Hong

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.

Contact Information:
--------------------

Danfeng Hong: hongdanfeng1989@gmail.com<br>
Danfeng Hong is with the Univ. Grenoble Alpes, CNRS, Grenoble INP, GIPSA-lab, 38000 Grenoble, France.

If emergency, you can also add my QQ: 345088114.
