# HumanAI GSoC AI-Generated Choreography Test:

### Contents of Repository

`derek_li_gsoc_test.ipynb` is the deliverable Jupyter notebook described in the test section for this task. It contains 3D plotting function for provided motion capture data, training of model, and evaluation of model. Additionally, I provide brief justification, observations, and explanations. I also provide an interest statement for the project at the end. 

The `Data` folder contains the recomended dataset for the task. These are numpy files with shape $(55, t, 3)$ denoting (joints, timesteps, dimensions), respectively. 

The `Animations` folder contains gifs rendered by the 3D visualization function in the notebook. It is seperated into the following subfolders:
- `Raw` contains full visualizations of the original datasets.
- `Reproduced` contains visualizations of a short dance sequence from the test set that the model reproduced. Visualizations for 200, 300 and 400 epochs of training are included.  
- `Generated` contains visualizatoins of short dance sequences that were randomly generated. Visualizations here are similarly produced for those above three training lengths.

The `Parameters` folder contains saved PyTorch parameters for the model when trained for 200, 300, and 400 epochs.

### Running the Contents of this Repository

Ensure the necessary imports are installed. They are listed in the first cell under each task section. The remaining code should be able to be run once the imports are made. If training or retraining the model, I recommend utilizing a CUDA enabled GPU. Model parameters are available to play with dance sequence generation and reproduction.



