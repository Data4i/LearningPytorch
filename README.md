# LearningPytorch

## 00 Files
  - *Learn Pytorch Fundamentals*
  - Learned how to create a tensor
  - Learned how to create reproducible randomized tensors with `torch.manual_seed(number)`*Note number can be changed to any integer value*
  - Check if we have GpU or not with `device = 'cuda' if torch.cuda.is_available() else 'cpu'`
  - Learned how to put tensors on GPU with `tensor.to(device)`
  - Learned How to put them back on the CPU with `tensor.`

## 01 Files
  - Created a linear data with X and y 
  - Learn Gradient Descent from the ground up
  - Learn how to perform gradient descent with PyTorch
  - Used Gpu
  - Create a PyTorch model using `nn.Parameter()`
  - Create a PyTorch model using `nn.Linear()`
  - Learned how to save our models' learned Parameters with `torch.save(obj = model.state_dict(), f='path/name_of_model.pth')`
  - Learned how to load the Parameters with `torch.load(path)`

## 02 Files
  - Apply Gradient Descent with PyTorch to a more concise dataset
  - Used the make_circles data set from `sklearn.datasets.make_circles`
  - Built a Binary Classifier model and trained it on the circle dataset
  - Used ReLU activation function to fit the non-linear data(*make_circles*)
  - Visualized the models capability to predict on both the test and train sets for the *make_circles* dataset
  - Used the Blob dataset from `sklearn.datasets.make_blobs`
  - Built a MultiClass Classifier model and trained it on the blob dataset
  - Visualized the models capability to predict on both the test and train sets for the *make_blobs* dataset
  - Used the moon dataset from `sklearn.datasets.make_moons`
  - Built a Binary Classifier model and trained it on the moon dataset
  -  Achieved a 100% *F1Score* on the predictions on the test set of the moon dataset
  -  Visualized the model on both the test and train sets of the moon dataset
  -  Saved the models' state dict through `torch.save()`
  -  Generated a spiral Dataset from <a href=https://cs231n.github.io/neural-networks-case-study/ target="_blank">spirals data creation function from CS231n</a>
  - Built a MultiClass Classifier model and trained it on the spiral dataset
  - Achieved a 100% *F1Score* on the predictions on the test set of the spiral dataset
  - Visualized the model on both the test and train sets of the spiral dataset
  -  Saved the models' state dict through `torch.save()`

## *Happy Learning 😁😉👌. Don't give up💪👍*
