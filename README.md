# Funding_and-Deep-Learning

### Description:
The purpose of this analysis is to create a tool that will assist a nonprofit organization in selecting applicants for funding with the best chance of success. The tool is a binary classifier that can predict an applicant’s success or not, if funded by the nonprofit organization.
The label column is the column indicating if the applicant was successful or not, 'IS_SUCCESSFUL'.
The remaining columns are features utilized in the model that would assist in the learning. They provide insight into the data for the model to learn how to predict new data. 
However, columns that serve the purpose of identification, should be removed as they don’t serve a relevant purpose in the model’s learning. 

The model utilizes ‘relu’ as the activation with the first hidden layer having 8 neurons and the second layer having 5 neurons. The output layer is expected to classify 2 classes with activation using ‘sigmoid’. The model is set to binary classification using  ‘adam’ as optimizer and ‘accuracy ’ as metrics. The model was able to attain an accuracy score of 1 and a loss score of 0.5544 with 100 epochs. The model started with 2 layers each having 1 neuron. Neurons were incrementally increased after each run trial to find out how many neurons were needed to attain an accuracy score of 75% or more. It was concluded that 8 neurons in the first layer and 5 neurons in the second layer were acceptable in building the model. 

### Language:
Python (with Tensor Flow)

### Data Source:
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/

### Details:
- [model code](https://github.com/cindyd97/Funding_with-Deep-Learning/blob/main/Starter_Code.ipynb)
