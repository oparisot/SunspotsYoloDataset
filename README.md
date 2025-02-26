# SunspotsYoloDataset

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11441091.svg)](https://doi.org/10.5281/zenodo.11441091)

## 📖 Description

SunspotsYoloDataset is a set of 1690+380+128 high-resolution RGB astronomical images captured with smart telescopes with specific solar filters and annotated with the positions of sunspots that are effectively in the images. 
Two instruments were used for several months from Luxembourg and France between January 2023 and May 2024: a Stellina smart telescope (https://vaonis.com/stellina) and a Vespera smart telescope (https://vaonis.com/vespera).

SunspotsYoloDataset can be used to train YOLO detection models on solar images, enabling the prediction of unexpected events such as Borealis Aurora with astronomical equipment accessible to the public.


## 📜 Dataset Structure

SunspotsYoloDataset is formatted with the YOLO standard, i.e., with separated files for images and annotations, usable by state-of-the-art training tools and graphical software like MakeSense (https://www.makesense.ai). 
More precisely, there is a ZIP file containing RGB images in JPEG format (minimal compression), and text files containing the positions of sunspots. 
Each RGB image has a resolution of 640 × 640 pixels.


## 📑 Examples

The dataset was used to train a YOLOv7 model -- allowing to obtain the following results.

AI-powered annotation of Sunspots with a Hestia portable telescope (11/2/2025)

[![AI-powered annotation of Sunspots with a Hestia portable telescope (11/2/2025)](https://img.youtube.com/vi/mAL11LlenAw/0.jpg)](https://www.youtube.com/watch?v=mAL11LlenAw)

AI-powered annotation of Sunspots with a Vespera smart telescope (6/8/2024)

[![AI-powered annotation of Sunspots with a Vespera smart telescope (6/8/2024)](https://img.youtube.com/vi/Wt6HzRm1uYk/0.jpg)](https://www.youtube.com/watch?v=Wt6HzRm1uYk)




## 📚 Research

The dataset can be found here:

- **[2024] SunspotsYoloDataset: annotated solar images captured with smart telescopes (January 2023 - May 2024)** – [DOI Link](https://doi.org/10.5281/zenodo.11441091) 

The following studies were based on this dataset:

- **[2024] Data and models for sunspots detection in solar images captured with smart telescopes** – [Link](https://www.doopyon.org/docs/publications/artiis2024-parisot.pdf)  
  
If you use this dataset in a publication, please notify us to include it in this list.


## 🎓 Citation

If you use **SunspotsYoloDataset** in your work, please cite it as follows:

```bibtex
@misc{parisot2024sunspotsyolodataset,
  author       = {Parisot, Olivier},
  title        = {SunspotsYoloDataset: annotated solar images captured with smart telescopes (January 2023 - May 2024)},
  month        = jun,
  year         = 2024,
  publisher    = {Zenodo},
  version      = {1.0.2},
  doi          = {10.5281/zenodo.11441091},
  url          = {https://doi.org/10.5281/zenodo.11441091},
}
```

## 📝 License

This dataset is released under the **CC Attribution-ShareAlike 4.0 International**. 

See [`LICENSE`](https://zenodo.org/records/11441091/files/license.txt?download=1) for details.


## ✉️ Contact

For questions or collaborations, please contact **Olivier Parisot** at **olivier.parisot@list.lu** or open an issue on **GitHub**.

Copyright 2021-2025 Luxembourg Institute of Science and Technology (LIST - http://www.list.lu/).
