# 2023-Fall-CS284a-Project
AI in biology and medicine project

# Information on the Neural Network Regression 

The code to the neural network regression model is provided as a Jupyter notebook. All code is to be run in the sequence provided by the notebook. 

# Information on the two-tier models:

The TwoTierCode is a Quarto Markdown document that contains both R and Python code. Each chunk in the document can be run in an RStudio IDE as long as the necessary libraries are installed. You'll need to have the `reticulate` library in R in order to specify the Python virtual environment you need to run the code. You can see which virtual environments you have to use in R using the code: 
```
library(reticulate)

conda_list()
```

Unless you want to use the base Python environment, you need to select the virtual environment before running any of the Python chunks. 

```

# This code selects the fourth environment listed. 
use_condaenv(conda_list()[[1]][4], required = TRUE)

```

The code must be run in the order specified in this document and in the same session. Many models were created for this project. Only code for performing and validating the best-performing model(s) are provided. The model inputs for different models tested were sufficiently different that most models had their own validation function. To provide all models and validation functions would be excessive. 

You can technically knit/render the entire Quarto file, but it will take a while to run as it will run all cross-validation steps again. 


# Google Drive 

https://drive.google.com/drive/folders/1oJoa3BKeyOzz3bGGnJIzQu6-WoghP9cn?usp=sharing