# Hierarchical Uncertainty Aggregation and Emphasis Loss for Active Learning in Object Detection
This repository contains supplemental materials for the IEEE BigData 2023 special session Machine Learning paper: **[Hierarchical Uncertainty Aggregation and Emphasis Loss for Active Learning in Object Detection](https://www.researchgate.net/profile/Toan-Khoa-Nguyen/publication/377601669_Hierarchical_Uncertainty_Aggregation_and_Emphasis_Loss_for_Active_Learning_in_Object_Detection/links/65e72c94adf2362b637827e5/Hierarchical-Uncertainty-Aggregation-and-Emphasis-Loss-for-Active-Learning-in-Object-Detection.pdf)**

![huale](./materials/huale.png)

Object detection has achieved remarkable advancements through the utilization of deep neural networks; however, its heavy reliance on extensive labeled data remains a significant challenge. We first delve into active learning strategies that leverage the power of uncertainty estimation and detector resilience. Departing from approaches biased toward high-performing classes, we present an innovative solution known as Hierarchical Uncertainty Aggregation and Emphasis Loss (HUALE). This approach introduces hierarchical uncertainty aggregation, which effectively retrieves and ranks unlabeled images for precise image selection. Secondly, we introduce the Emphasis loss, a novel loss augmentation to object detection training, and combine it with the EIoU loss and Synchronic IoU-Localization loss to elevate the accuracy of bounding box localization and address non-convexity challenges. Our method, built upon the Faster R-CNN framework, consistently outperforms the baseline (random selection) with average mAP (%) improvements of 4.53/3.44/1.57 across the PASCAL VOC 2007, PASCAL VOC 2012, and MS COCO datasets.

## Table of Contents

- [Update](#update)
- [Results](#results)

## Update
- **June 2024**: We release 1st version supplementary.

## Results

![ablation](./materials/huale_results.png)

## Citation
Please cite this paper if it helps your research:
```bibtex
@inproceedings{nguyen2023hierarchical,
  title={Hierarchical Uncertainty Aggregation and Emphasis Loss for Active Learning in Object Detection},
  author={Nguyen, Tai and Nguyen, Khoa and Nguyen, Thanh and Nguyen, Tri and Nguyen, Anh and Kim, Karrman},
  booktitle={2023 IEEE International Conference on Big Data (BigData)},
  pages={5311--5320},
  year={2023},
  organization={IEEE}
}
```
