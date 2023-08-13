# Enhanced Visualization of Pneumonia Chest X-Ray Dataset for Classification

In this project, we have developed an insightful visualization of the Pneumonia Chest X-Ray dataset to facilitate accurate classification. The dataset can be accessed here https://www.kaggle.com/datasets/lasaljaywardena/pneumonia-chest-x-ray-dataset.

## Key Highlights:
  - Data Distribution Analysis:
    We conducted a comprehensive analysis of the distribution of images within the Training, Test, and Validation sets. This enabled us to understand the balance between Normal and Pneumonia images in each subset.
  - Random Image Sampling:
    To provide a representative view, we randomly selected and displayed five chest X-ray images from each of the Test, Training, and Validation sets. This offers a visual overview of the data.
  -  Ben Graham's Enhancement:
    We employed Ben Graham's enhancement technique to optimize the visualization of the selected images. This method enhances the contrast of the images, aiding in better feature identification.
  -  Background Subtraction:
    For the chosen five images from each subset, we applied background subtraction. This technique isolates the foreground from the background, accentuating the key details in the X-ray images.
  -   Augmentation Insight:
    A single image from each class within the Test, Training, and Validation sets was subjected to augmentation techniques. By showcasing the original and augmented images side by side, we highlighted the impact of these transformations.
  -   Image Erosion Visualization:
    We employed Image Erosion to emphasize boundaries in the Test, Training, and Validation sets. This technique contributes to better edge detection and finer feature understanding.
  -   Canny Edge Detection:
    By implementing the Canny Edge Detection algorithm on the X-ray images, we revealed edges and contours. This provides a clearer perception of the structures within the images.
 -    Hstogram Analysis:
    Histograms were plotted for both Normal and Pneumonia images within the Test, Training, and Validation subsets. This allowed us to observe the distribution of pixel intensity values and detect any discernible patterns.
 -    Cumulative Distribution Function (CDF):
    CDF was employed to showcase the cumulative distribution of pixel intensity values in the Test, Training, and Validation set images. This technique provides insights into the overall distribution characteristics.

## Further Potential:

As a next step, considering the visualizations provided, one could proceed to implement a classification model trained on the preprocessed images. Additionally, exploring advanced medical image processing techniques and evaluating the model's performance metrics could enhance the project's depth.

In sharing this work, we emphasize ethical considerations such as patient privacy and dataset bias. The project's full code implementation can be accessed on platforms like GitHub, making it accessible for collaborative learning and engagement.

By presenting this project, we aim to provide an insightful demonstration of the steps undertaken to visualize and understand the Pneumonia Chest X-Ray dataset for classification purposes.

Feel free to refine this notebook for your usage.



