# EDMNet
Deblurring Network Using Edge Module, Deformable Convolution-Channel Attention Blocks and Multi-Stage Network

This is a PyTorch implementation of the my master's graduation paper. It is not yet complete. I will continue to update.

## Abstract
In this paper, we propse Deblurring Network Using Edge Module, Deformable Convolution-Channel Attention Blocks and Multi-Stage Network. The proposed network efficiently restores blurring objects using edge and deformable convolution. In addition, a total of three stages of learning perform using the multi-stage network. The sub-network of the multi-stage network consists of a U-net using the proposed DC-CAB. Also, we proposed RDFB(Residual Dense Feature Block) that learns about the original resolution not devided. The proposed network gets 31.52 dB of PSNR from the gopro test set and uses YOLO v3 to confirm object detection accuracy improvement. In addition, we perform an ablation study by removing the Edge Module and RDFB.

## Proposed Network
- Network Architecture
![EDMNet_rfa](https://user-images.githubusercontent.com/59470033/136790972-9984d09f-f93d-41ee-9edd-bd1f143ba685.png)

- Sub-Network
![subnet](https://user-images.githubusercontent.com/59470033/136791164-efc7f952-fd81-41ac-8075-2d1857b9ddef.png)


- Deformable Convolution Attention Block
![DAB](https://user-images.githubusercontent.com/59470033/136791190-9cb25267-910f-4896-8371-89ea9eeeb9fc.png)


## Experimental Results

