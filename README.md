## Introduction

In line with Singapore's "30 by 30" goal, farmers have been incentivised to adopt agricultural technology. Image segmentation is a computer vision task and is the basis of many applications like crop yield estimation and disease/weed detection. This allows farmers to make data-driven decisions to optimise yield and is crucial to ensuring Singapore's food security.

---

## Objective

This study aims to optimize the feasibility and efficiency of integrating precision agricultural techniques through 2 goals:

1. **Evaluate performance of image segmentation algorithms.**  
2. **Identify the best algorithm for implementation.**


### Evaluation with F-score  
Individual performance was calculated by comparing each pixel in the predicted mask to the ground truth.

\[
F_{score} = \frac{True Positive}{True Positive + 0.5(False Positive + False Negative)}
\]

The results were plotted against each other and evaluated. Overall, all 3 approaches achieved optimal results, with high overall accuracy and recall. But as the plants grew larger, the performance of classical algorithms and Mask-RCNN dropped exponentially, while STCN maintained a linear loss.

**Figure 1:** Result comparison of the different techniques.

---

## Conclusion

STCN performed better than classical and Mask-RCNN approaches. It has potential applications in real-world agricultural fields.

---

## Future Research

- Additional Data: Supplement the dataset to expand the scope of the study.  
- Examining performance under varying conditions and increasing the diversity of crops.

---
