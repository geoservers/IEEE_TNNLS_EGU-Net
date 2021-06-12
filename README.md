# Endmember-Guided Unmixing Network (EGU-Net): A General Deep Learning Framework for Self-Supervised Hyperspectral Unmixing

[Danfeng Hong](https://sites.google.com/view/danfeng-hong), [Lianru Gao](https://scholar.google.com/citations?hl=en&user=f6OnhtcAAAAJ), [Jing Yao](https://scholar.google.com/citations?user=1SHd5ygAAAAJ&hl=en), [Naoto Yokoya](https://naotoyokoya.com/), [Jocelyn Chanussot](http://jocelyn-chanussot.net/), [Uta Heiden](https://scholar.google.de/citations?user=xgKwyocAAAAJ&hl=de), [Bing Zhang](http://english.radi.cas.cn/Education/PhDS/201401/t20140109_115415.html)

___________

The code in this toolbox implements the ["Endmember-Guided Unmixing Network (EGU-Net): A General Deep Learning Framework for Self-Supervised Hyperspectral Unmixing"](https://ieeexplore.ieee.org/abstract/document/9444141). More specifically, it is detailed as follows.

![alt text](./networks.png)


Citation
---------------------

**Please kindly cite the papers if this code is useful and helpful for your research.**

Danfeng Hong, Lianru Gao, Jing Yao, Naoto Yokoya, Jocelyn Chanussot, Uta Heiden, Bing Zhang. Endmember-Guided Unmixing Network (EGU-Net): A General Deep Learning Framework for Self-Supervised Hyperspectral Unmixing, IEEE Transactions on Neural Networks and Learning Systems, 2021, DOI: 10.1109/TNNLS.2021.3082289. 

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
This toolbox consists of two self-supervised unmixing network architectures, i.e., pixel-wise EGU-Net using fully-connected networks (EGU-Net-pw), spatial-spectral EGU-Net using convolutional neural networks (EGU-Net-ss). For more details, please refer to the paper.

The used data (named TNNLS_Data) for the network input, including the original hyperspectral image, the extracted endmembers (spectral bundles), and the corresponding pseudo abundances, can be downloaded from 

Google Drive: https://drive.google.com/file/d/1n6PfPIYlq5nfCWbfy274oAgKrZ47ytTo/view?usp=sharing

Baiduyun: https://pan.baidu.com/s/1qlwPWS1je-o-za60jR6ohQ (access code: wkm9).

PS: the endmembers (spectral bundles) can be extracted from the original hyperspectral image using the provided Pseudo_endmembers_generation.m function.

More specifically, for using the proposed network, you first need to download the data from the given link and copy them to "TNNLS_Data". If you wanna run the codes in your own data, you need to first extract the endmembers using the provided Pseudo_endmembers_generation.m function and meanwhile generate the corresponding abundances. Then, you can further copy and use them in your proposed networks.

If you encounter bugs while using this code, please do not hesitate to contact us.

Licensing
---------

Copyright (C) 2021 Danfeng Hong

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.

Contact Information:
--------------------

Danfeng Hong: hongdanfeng1989@gmail.com<br>
Danfeng Hong is with the Univ. Grenoble Alpes, CNRS, Grenoble INP, GIPSA-lab, 38000 Grenoble, France.<br>
                with the Remote Sensing Technology Institute (IMF), German Aerospace Center (DLR), 82234 Wessling, Germany

If an emergency, you can also add my QQ: 345088114.
