# Geometric Constrained Joint Lane Segmentation and Lane Boundary Detection

To further demonstrate the benefits of our network structure, we upload a demo video in the supplement material. The demo video consists of two parts.

  - Three clips of lane segmentation videos (ours and a baseline)
  - several segmentation images (general cases and hard cases)

## Lane Segmentation Videos

To show the robustness of our approach, three clips of videos contains different scenes: normal scene and rainy scene. The segmentation results are marked as green areas. We compare our method with the baseline approach, and our method significantly outperfoms the baseline.

## Segmentation Images
Several segmentation images are also shown in our demo. We present general cases and hard cases in our demo. The true positives (TP) are shown in green areas, while false positives (FP) are in blue and false negatives (FN) are in red. 
### General Cases
We present four general cases in our demo. These cases have good illumination condition and recognizable lane boundaries. Because different methods do not have obvious different, we only present our network outputs.
### Hard Cases
The significant improvement is shown in hard cases, most of which have illumination problem or boundary missing problem. State-of-the-art approaches can not segment these cases correctly, while our approach still maintains high accuracy.
