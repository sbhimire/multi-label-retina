## Multi-label classification of retinal disorders

This is a midterm project from the deep learning course. The task is to develop a solution, using computer vision techniques, that can detect when images of a patient's eye contain evidence of specific medical pathologies. The setup is somewhat realistic in the sense that each image may have multiple pathologies.

The project involves several sub-tasks:

1. Build classification models
   -Use atleast two different model architectures
   -Explore transfer learning
2. GradCAM - Visualize regions of interest that contribute to Diabetic Retinopathy and Glaucoma
3. Using the unlabeled dataset, augment the training data (semi-supervised learning) and report the change in classification performance on your (labeled) validation data set

The notebook can be opened in google colab using the Open in Colab link inside the notebook.

Resources

- [Retinal image dataset](https://www.kaggle.com/c/vietai-advance-course-retinal-disease-detection/overview)

### Grad-CAM sample results

<img src=".github\readme\gradcam1.png" width=75% height=75%>
<img src=".github\readme\gradcam2.png" width=75% height=75%>