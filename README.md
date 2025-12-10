# 🧢 CAP-VTON
> Clothing agnostic Pre-inpainting Virtual Try-ON

-----------
[📖Paper](https://www.mdpi.com/3612740) -- [📖Paper arxiv](https://arxiv.org/abs/2509.17654) -- [💾Code](https://github.com/DevChoco/CAP-VTON) -- [🕹️Colab_Demo](https://colab.research.google.com/drive/14cP_1sOckUrykGyg5PVZX2BoQWZ9eu34?usp=sharing)

# Abstract
With the development of deep learning technology, virtual try-on technology has developed important application value in the fields of e-commerce, fashion, and entertainment. The recently proposed Leffa technology has addressed the texture distortion problem of diffusion-based models, but there are limitations in that the bottom detection inaccuracy and the existing clothing silhouette persist in the synthesis results. To solve this problem, this study proposes CaP-VTON (Clothing-Agnostic Pre-Inpainting Virtual Try-On). CaP-VTON integrates DressCode-based multi-category masking and Stable Diffusion-based skin inflation preprocessing; in particular, a generated skin module was introduced to solve skin restoration problems that occur when long-sleeved images are converted to short-sleeved or sleeveless ones, introducing a preprocessing structure that improves the naturalness and consistency of full-body clothing synthesis and allowing the implementation of high-quality restoration considering human posture and color. As a result, CaP-VTON achieved 92.5%, which is 15.4% better than Leffa, in short-sleeved synthesis accuracy and consistently reproduced the style and shape of the reference clothing in visual evaluation. These structures maintain model-agnostic properties and are applicable to various diffusion-based virtual inspection systems; they can also contribute to applications that require high-precision virtual wearing, such as e-commerce, custom styling, and avatar creation.

# Visualization
![img](https://github.com/DevChoco/CAP-VTON/blob/main/git_img/im.png)
![img](https://github.com/DevChoco/CAP-VTON/blob/main/git_img/main.png)

# Installation
> Create a Conda Python environment and install requirements.
>> It runs on Linux (Ubuntu) environment...!
```
conda create -n capvton python==3.10
conda activate capvton
cd CAP-VTON
pip install -r requirements.txt

"Run Start_CaP_VTON.ipynb"
```

# Specifications
- Capacity: 34.3GB
- RAM: 24GB more
- GPU: (Tested: RTX4080 and A100)

# Acknowledgement
This work was developed by extending [Leffa](https://github.com/franciszzj/LEFFA).  
We would like to acknowledge the contributions of the original authors.  
For in-depth technical details, please see the [Leffa Paper](https://arxiv.org/pdf/2412.08486).


# Citation
If you find CAP-VTON helpful for your research, please cite our work:
```
@article{DevChoco_CAP-VTON_2025,
  author        = {Sehyun, Kim. Hye Jun, Lee. Jiwoo, Lee. Taemin, Lee.},
  title         = {Clothing-Agnostic Pre-Inpainting Virtual Try-On},
  journal       = {Electronics},
  year          = {2025},
  volume        = {14},
  number        = {23},
  article-number= {4710},
  pages         = {4710},
  doi           = {10.3390/electronics14234710},
  url           = {https://www.mdpi.com/2079-9292/14/23/4710},
  publisher     = {MDPI}
}
```






















