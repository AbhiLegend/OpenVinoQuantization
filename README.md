# OpenVinoQuantization
Of course! Let's summarize the steps in the provided code:

1. **Setup**: The necessary libraries are imported. The possible labels for the STL10 dataset are defined, and the data directory is set.

2. **Data Preparation**:
   - Data transformations, which convert images to tensors and normalize them using a previously computed mean and standard deviation, are set up.
   - The STL10 dataset's 'test' split is loaded using these transformations, and a DataLoader is created.

3. **Image and Label Collection**: All images and labels from the DataLoader are collected into separate lists for easy access.

4. **Visualization & Inference**:
   - A function is created to plot images given their indices.
   - Another function performs inference on given images using a specified model and returns predicted labels.
   - Four specific images are selected and displayed.
   - Inference is run on these images using two different models (a float model and a quantized model), and the results are printed out.

In summary, the code prepares and visualizes a subset of the STL10 dataset, and then it demonstrates inference on this subset using two different models, showing the predicted labels for each.
