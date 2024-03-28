EGBE601/602 Signal Processing Final Project:
Image processing with segmentation and classification of White Blood Cell image from Microscope

- Firstly, We segment the image by using SAM model. The source code is in "Segmentation.ipynb"

- We use FFT, DWT for image processing and create the huggingface datasets. The source code is in "Image Processing.ipynb"

- We fine tune the image classification model from ViT-based model.The source code is in "Classification.ipynb"

Model uploaded to Huggingface: https://huggingface.co/Boom4869

References:
@misc{wu2020visual,
      title={Visual Transformers: Token-based Image Representation and Processing for Computer Vision}, 
      author={Bichen Wu and Chenfeng Xu and Xiaoliang Dai and Alvin Wan and Peizhao Zhang and Zhicheng Yan and Masayoshi Tomizuka and Joseph Gonzalez and Kurt Keutzer and Peter Vajda},
      year={2020},
      eprint={2006.03677},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
@article{kirillov2023segany,
  title={Segment Anything},
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C. and Lo, Wan-Yen and Doll{\'a}r, Piotr and Girshick, Ross},
  journal={arXiv:2304.02643},
  year={2023}
}
