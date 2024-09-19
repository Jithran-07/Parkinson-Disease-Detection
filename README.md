# Parkinson-Disease-Detection

Parkinson's disease (PD) is a progressive neurodegenerative disorder that primarily affects movement. It occurs due to the gradual loss of dopamine-producing neurons in the brain, which leads to symptoms like tremors, stiffness, slow movement, and difficulty with balance. In addition to motor symptoms, PD can also cause non-motor issues such as sleep disturbances, cognitive decline, and mood disorders.

While the exact cause of Parkinson’s is not fully understood, both genetic and environmental factors are thought to play a role. There is currently no cure, but treatments like medication, physical therapy, and, in some cases, surgery can help manage symptoms and improve quality of life. Early detection is crucial for better management of the disease.




## Models Used

### 1. **EfficientNet**
- Used for: **Image classification** of handwritten data.
- Why EfficientNet? 
  - It’s a highly efficient convolutional neural network that handles complex image data with less computational cost.
  
### 2. **CatBoost**
- Used for: **Voice classification** of Parkinson’s Disease-related voice data.
- Why CatBoost? 
  - It excels in processing categorical data and offers faster training with high accuracy, making it suitable for voice data classification.

### 3. **Voting Mechanism**
- To combine the strengths of both models, we implement a voting method to fuse the outputs of EfficientNet and CatBoost, leveraging the complementary information of both modalities to enhance overall detection performance.

## Dataset

- **Handwritten Image Dataset**: Contains handwritten samples, focusing on specific motor issues common in PD patients.
- **Voice Dataset**: Consists of voice recordings capturing speech-related symptoms of Parkinson's Disease.
  

## Results

The proposed multi-modal approach demonstrated superior performance in detecting Parkinson's Disease by leveraging both handwritten image and voice datasets. Extensive testing on standard datasets resulted in improved accuracy over traditional single-modality methods. 

## Conclusion

This project highlights the potential of using multi-modal deep learning techniques for early detection of Parkinson’s Disease. By combining visual and voice-based features, the system achieves higher detection accuracy, offering a promising tool for aiding medical diagnosis and intervention.

## Future Work

- **Expand the dataset**: Further data collection to include more diverse samples.
- **Real-time PD detection**: Implement real-time prediction systems for clinical use.
- **Model optimization**: Improve the model's efficiency and reduce computational requirements.


This `README.md` provides a clear structure and documentation for your project, ensuring that others can understand and contribute to it easily. Let me know if you need any adjustments!
