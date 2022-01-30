# HeartSeg-Dataset

[ [ D O W N L O A D ] ](https://osf.io/6svkf/download)

The medaka (Oryzias latipes) and the zebrafish (Danio rerio) are used as a model organism for a variety of subjects in biomedical research the here presented work aims to study the potential of automated ventricular dimension estimation through heart segmentation in medaka. 
For more on this, it's time for a closer look on our paper and the supplementary materials.

See our paper:  
On [Liebertpub](https://www.liebertpub.com/doi/10.1089/zeb.2019.1754)

See our codebase:  
On [OSF](https://osf.io/snb6p/)

See demonstration of our algorithm and framework on the test set data:   
On [youtube](https://youtu.be/i5bX_XbwXq0)

## Data Samples

Exemplary [sample of the dataset](https://github.com/schutera/HeartSeg-Dataset/tree/master/Graphics/color_frame_1.tif) and the provided [binary ground truth mask for the ventricle](https://github.com/schutera/HeartSeg-Dataset/tree/master/Graphics/0001.tiff)


## Dataset Structure

```
|- Dataset
	|- train_images
		|- lateral_mask
		|- lateral_sample_gray
		|- ventral_mask
		|- ventral_sample_gray
		|- ventral_samples
	|- test_images
		|- frames_N0092
		|- frames_R0004
		|- label_masks_N0092
		|- label_masks_R0004
		|- lateral_mask
		|- lateral_sample_gray
		|- ventral_mask
		|- ventral_sample_gray
```
Download the dataset: train images, test images and full videos [here](https://osf.io/6svkf/)

## Data Origin

The raw data was provided by:   

Dr. Jakob Gierten  

Affiliated with:  
1. Department of Pediatric Cardiology, University Hospital Heidelberg, Im Neuenheimer Feld 430, 69120 Heidelberg, Germany
2. Centre for Organismal Studies, Heidelberg University, Im Neuenheimer Feld 230, 69120 Heidelberg, Germany


## Contributing and Citing

We hope this work sparks additional research in the direction of biomedical image processing. Either by contributing to the annotated groundtruth data or deploying further models.  
In any case feel free to reach out and spread the work.

```
@article{schutera2019heartseg,
  title={Machine Learning Methods for Automated Quantification of Ventricular Dimensions},
  author={Schutera, Mark and Just, Steffen and Gierten, Jakob and Mikut, Ralf and Reischl, Markus and Pylatiuk, Christian},
  journal={Zebrafish},
  volume={16},
  number={6},
  pages={542--545},
  year={2019},
  publisher={Mary Ann Liebert}
}
```

Contact: mark.schutera@kit.edu and pylatiuk@kit.edu 

