# HeartSeg-Dataset

The medaka (Oryzias latipes) and the zebrafish (Danio rerio) are used as a model organism for a variety of subjects in biomedical research the here presented work aims to study the potential of automated ventricular dimension estimation through heart segmentation in medaka. 
For more on this, it's time for a closer look on our paper and the supplementary materials.

![Automated quantification of ventricular dimensions][1] Add image here.

See our paper here:
https://www.liebertpub.com/doi/10.1089/zeb.2019.1754

See our codebase here:
https://osf.io/snb6p/

See demonstration of our algorithm and framework on the test set data:  
https://youtu.be/i5bX_XbwXq0



## Dataset Structure

```
|- data
	| test_images (200 annotated image sequences for testing)
	|- test_videos 
		- example_R0004.avi
    - ...
		|- frames (colorframes of the testset)
		|- label_masks (annotation of the testset)
	|- train_images(550 annotated image segmentation data)
			|- ventral_mask (heart groundtruth masks)
			|- ventral_samples (color images related to the masks)
			|- ventral_sample_gray (grayscale images related to the masks)
```


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
  publisher={Mary Ann Liebert, Inc., publishers 140 Huguenot Street, 3rd Floor New~…}
}
```

Contact: mark.schutera@kit.edu and pylatiuk@kit.edu 

