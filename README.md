
# Approach and summary

In this assignment, I have trained a GNN to do link prediction (classification) of drug-disease edges using the Pytorch Geometric library.
I was unfortunately unable to test against the ground truth provided in this occasion as I ran out of time. But with the model trained on the whole dataset, I get an AUC score of 0.7, which is not too bad, given how imbalanced the dataset is. There are comments on what could be done to improve performance in the *Conclusions section of the `attempt_pytorch_geometric_full_data.ipynb` notebook.

 There are two notebooks in this assessment, the first one `attempt_pytorch_geometric.ipynb` uses a small sample of the data as a starting point to make sure I could run the model locally first, and the second one, `attempt_pytorch_geometric_full_data.ipynb` uses the whole dataset. The model which uses the whole dataset is much better than the model trained with the sample data.
 
 In both notebooks, I decided to convert the dataset to a homogenous dataset in the interest of simplicity and time.

# How to run the notebooks

To run the notebooks, a python3.9 virtualenvironment needs to be used, and the libraries in `requirements.txt` need to be installed as so:

`pip install -r requirements.txt`

