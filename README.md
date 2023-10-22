# 우학연 Result Comparison(Ablation study)

## **Neck**

### **Yolo-ResNet**

- Augmentation

- Image Patching

- Image Patching & Augmentation

### **Yolo-Swin**

- Augmentation
    
    *factor: 20
    
    - 성능
    
    mAP30 = 0.61
    
    mAP50 = 0.40
    
    - 학습추이
    
    [https://wandb.ai/urp/yolo_swin_neck?workspace=user-gomduribo](https://wandb.ai/urp/yolo_swin_neck?workspace=user-gomduribo)
    
    → YOLO_SWIN_T_neck_LR0.0001_AUG20 참조
    
    - 결과 이미지
    
    /workspace/Plastic_Bottle_defect_detection/results/boxed_images/YOLO_SWIN_T_neck_LR0.0001_AUG20/
    
    파란색: annotation
    
    형광초록색: prediction
    
    ![Untitled](/workspace/Plastic_Bottle_defect_detection/results/boxed_images/YOLO_SWIN_T_neck_LR0.0001_AUG20/shape1_148.jpg)
    
    ![Untitled](/workspace/Plastic_Bottle_defect_detection/results/boxed_images/YOLO_SWIN_T_neck_LR0.0001_AUG20/shape2_14.jpg)
    

- Image Patching
    
    -성능
    
    mAP30 = 0.57
    
    mAP50 = 0.42 
    
    - 학습추이
    
    [https://wandb.ai/urp/yolo_swin_neck_IMAGE_PATCH?workspace=user-gomduribo](https://wandb.ai/urp/yolo_swin_neck_IMAGE_PATCH?workspace=user-gomduribo) 
    
    → YOLO_SWIN_T_neck_LR0.0001_Image_Patch50 참조
    
    - 결과 이미지
    
    /workspace/Plastic_Bottle_defect_detection/results/boxed_images/YOLO_SWIN_T_neck_LR0.0001_Image_Patch50/
    
    파란색: annotation
    
    형광초록색: prediction
    
    ![Untitled](%E1%84%8B%E1%85%AE%E1%84%92%E1%85%A1%E1%86%A8%E1%84%8B%E1%85%A7%E1%86%AB%20Result%20Comparison(Ablation%20study)%20d0da20a7b7984179a9e5f028a4bf8e9c/Untitled%202.png)
    
    ![Untitled](%E1%84%8B%E1%85%AE%E1%84%92%E1%85%A1%E1%86%A8%E1%84%8B%E1%85%A7%E1%86%AB%20Result%20Comparison(Ablation%20study)%20d0da20a7b7984179a9e5f028a4bf8e9c/Untitled%203.png)
    

- Image Patching & Augmentation

### Yolo-CBAM

- Augmentation

- Image Patching

- Image Patching & Augmentation

## Body

### Yolo-ResNet

- Augmentation

- Image Patching

- Image Patching & Augmentation

### Yolo-Swin

- Augmentation

- Image Patching

- Image Patching & Augmentation

### Yolo-CBAM

- Augmentation

- Image Patching

- Image Patching & Augmentation
