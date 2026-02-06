# From Offline to Periodic Adaptation for Pose-Based Shoplifting Detection in Real-world Retail Security
## Overview
This Github repository contains the official implementation and dataset details for the paper:
"From Offline to Periodic Adaptation for Pose-Based Shoplifting Detection in Real-world Retail Security" published in [IEEE Internet of Things Journal](https://www.researchgate.net/publication/400393842_From_Offline_to_Periodic_Adaptation_for_Pose-Based_Shoplifting_Detection_in_Real-world_Retail_Security).  
We present a privacy-preserving, pose-based framework for shoplifting detection designed for on-site IoT deployment. Our pipeline enables edge devices to adapt from streaming, unlabeled data through continual unsupervised learning, overcoming environmental drift and changing shopper behaviors.


## Key Features

- Privacy-Preserving: Represents human activity through anonymized pose sequences (COCO17 format), removing raw pixel information.
- RetailS Dataset: A large-scale, multi-camera dataset featuring nearly 20M normal frames and both staged and authentic shoplifting incidents
- Continual Learning Pipeline: A three-stage framework (Filtering, Collection, Training) that allows for periodic model updates in under 30 minutes on edge hardware.
- $H_{PRS}$ Metric: A new evaluation criterion that balances Precision, Recall, and Specificity to minimize false alarms in real-world retail settings.

## Dataset Statistics: RetailS

RetailS is significantly larger and more diverse than previous retail security datasets.

<sub> Table 1: 
| Subsets         | Normal Frames | Shoplifting Events| Shoplifting Frames | Camera Views |
|------------------|---------|-------|-----|
| RetailS Train         |   19,971,589   | 0        | 0   | 6 |
|Real-world Test          |   2,432    |  1,933       | 53    | 6 | 
| Staged Test          |   20,578    |  20,335       | 898  | 6 |



