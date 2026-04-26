# Kannada-Flickr-Image-Captioning-Dataset
 
Flickr30K and Flickr8K Kannada language datasets created from the original Flickr30K and Flickr8K image captioning datasets.
 
## Overview
 
This repository contains two datasets for image captioning, computer vision, and machine learning research in Kannada.:
 
- **Flickr30K Kannada**: Kannada translations and corrections of the Flickr30K dataset
- **Flickr8K Kannada**: Kannada translations and corrections of the Flickr8K dataset

The datasets were created as part of a bachelor thesis on image caption generation using deep learning frameworks and are intended to facilitate academic research in South Indian languages, particularly Kannada.

This repository does not contain the images from the original datasets. All images belong to their respective copyright holders on Flickr. To use this dataset:
1. Download the original Flickr30K and/or Flickr8K datasets from their official sources
2. Use the provided annotations to replace or augment the original captions


## Citation
 
If you use these datasets in your research, please cite our [paper](https://ieeexplore.ieee.org/document/10170312):
 
```bibtex
@INPROCEEDINGS{10170312,
  author={Chethas, K and Ankita, V and Apoorva, B S and Sushma, H and Jayashree, R},
  booktitle={2023 International Conference on Advances in Electronics, Communication, Computing and Intelligent Information Systems (ICAECIS)}, 
  title={Image Caption Generation in Kannada using Deep Learning Frameworks}, 
  year={2023},
  pages={486-491},
  doi={10.1109/ICAECIS58353.2023.10170312}
}
```
 
**Additionally, please cite the original Flickr datasets:**
 
Flickr30K:
```bibtex
@article{young2014from,
  title={From image descriptions to visual denotations: New similarity metrics for semantic inference over event descriptions},
  author={Young, Peter and Lai, Alice and Hodosh, Micah and Hockenmaier, Julia},
  journal={TACL},
  volume={2},
  pages={67--78},
  year={2014}
}
```
 
Flickr8K:
```bibtex
@article{hodosh2013framing,
  title={Framing image description as a ranking task, data, models and evaluation metrics},
  author={Hodosh, Micah and Young, Peter and Hockenmaier, Julia},
  journal={Journal of Artificial Intelligence Research},
  volume={47},
  pages={853--899},
  year={2013}
}
```
 
## License and Usage Rights
 
### Image Attribution
This dataset includes images obtained from [Flickr](https://www.flickr.com/). The images are provided under the terms of their respective Creative Commons licenses as specified on Flickr.
 
**Important Notice**: We do not own the copyright of the images. Users must abide by the [Flickr Terms of Use](https://www.flickr.com/terms.goog) and respect the intellectual property rights of original image creators.
 
### Authorized Use
This dataset is provided exclusively for:
1. Non-commercial research purposes
2. Educational purposes
Commercial use of this dataset or the underlying images is strictly prohibited without appropriate licensing and permissions from the image copyright holders.

## Dataset Format
 
1. The flickr8k text file contains the image_id, caption in Kannada. Each image is associated with 5 captions.
2. The flick30k text file contains entries like so:- image_name | image_number | Kannada caption (image_number varies from 0 to 4, for the 5 captions associated with each image)

## Contact
 
For questions, issues, or clarifications regarding this dataset, please open an issue on this GitHub repository

## Disclaimer
 
The dataset was created using a combination of translation and manual correction. While care was taken to ensure quality, some inaccuracies or inconsistencies may remain. 
Users are encouraged to validate the data for their specific use cases.
Users are solely responsible for ensuring their use of this dataset complies with all applicable laws, regulations, and the terms specified herein.
 
## Acknowledgments

We express our gratitude to Dr. Jayashree R and the Department of Computer Science and Engineering, PES University.

---
 
**Version**: 1.0  
**Last Updated**: 26th April 2026
**Status**: Open Source
