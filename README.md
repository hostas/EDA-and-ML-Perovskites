# EDA and ML for Perovskites datasets

This work has been done as a part of AI4D project at University of Calgary

**Code contributors**: Jiri Hostas (Calgary/Canada) & Maicon Pierre Lourenco (Vitória/Brasil)

**Other collaborators**: John Garcia, Hatef Shahmohamadi, Amanda Ndubuisi, Bhavadharini Selvakumar, Thilini Boteju, Lizandra Barrios Herrera, Alain Tchagang, Patrizia Calaminici, Andreas Koster, Mosayeb Naseri, Dennis Salahub, Venkataraman Thangadurai, and Karthik Shankar.


## The repository contains several subprojects which are sorted into following sections:

1. [Data reading and cleaning](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/README.md) (including a custom made script to read a xlsx human made database file)
2. [EDA (Exploratory data Analysis)](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/README.md)
3. [Feature engineering](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/README.md)
4. [Principal Component Analysis](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/README.md)
5. [Wasserstein Autoencoders](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/README.md) (large portion of this code was forked from [ Ziyuan Rao's](https://github.com/ziyuanrao11/Machine-learning-enabled-high-entropy-alloy-discovery) repository, please cite his [work](https://doi.org/10.1126/science.abo4940)
7. [Prediction (Regression)](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/README.md)
8. [Hyperparameter tunning](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/README.md)

I will provide a documentation that explains the code and key takeaways of the project.




![Abstract](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/Graphics/Abstract.jpg)

**Figure 1**: Principal component analysis (PCA) is often used to visualize data and reduce the number of features that are used in machine learning. Here, I have started with 176 compounds which contained 28 different elements. This resulted in a weight composition descriptor with 28 different features (using site and chemical formula information). Using PCA this very sparse descriptor can be reduced and visualized. We can see that principal component 1 is highly correlated with the oxygen content which seems to explain sizeable portion of variance in the data, however after closer inspection it is only 10% if variance. This information is important in the further development of descriptors.
