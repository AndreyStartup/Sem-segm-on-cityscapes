# Semantic segmentation on cityscapes dataset
## Task
> Make Semantic segmentation model on [cityscapes dataset](https://www.cityscapes-dataset.com/)<br></br>
> Performance metric - [IOU score](https://hasty.ai/docs/mp-wiki/metrics/iou-intersection-over-union#:~:text=To%20define%20the%20term%2C%20in,matches%20the%20ground%20truth%20data.)<br></br>
> Loss Function - [Dice loss](https://paperswithcode.com/method/dice-loss)<br></br>
> Results - I was able to reach an IOU score of 0.40. Results on images from test dataset looks not bad, but if you make predictions on video, then it looks like an epileptic nightmare, so there is a huge room for improvement.

## Results
### Results on images from test dataset
![image](https://github.com/AndreyStartup/Sem-segm-on-cityscapes/assets/114228619/7b638ab7-ceb9-4122-ba6f-b0836fc1c5a6)

![image](https://github.com/AndreyStartup/Sem-segm-on-cityscapes/assets/114228619/5305cf43-62bf-4ddc-9124-eb933586aaad)

![image](https://github.com/AndreyStartup/Sem-segm-on-cityscapes/assets/114228619/77e342cb-bbc6-4261-bcc0-d8cace72e1bd)

![image](https://github.com/AndreyStartup/Sem-segm-on-cityscapes/assets/114228619/35abdf9d-f418-4574-8197-8c25eff1b330)
### Results on video
https://github.com/AndreyStartup/Sem-segm-on-cityscapes/assets/114228619/cc02496e-be3d-4aab-9dd8-c9c1a4df5a7e

## What's next
>1. You can use higher quality models (ViT-Adapter, Hierarchical Multi-Scale Attention, etc.)<br></br>
>2. You can change the numerical markup for classes (change the license plate)<br></br>
>3. Learn from more epochs<br></br>
>4. Instead of the segmentation_models library, you can use mmseg and mmcv<br></br>
>5. Increase the number of layers and the dimension of the input images (512x512 instead of 256x256)
