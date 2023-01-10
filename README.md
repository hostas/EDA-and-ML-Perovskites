# EDA and ML for Perovskites datasets

This work has been done as a part of AI4D project at University of Calgary

**Code contributors**: Jiri Hostas (Calgary/Canada) & Maicon Pierre Lourenco (Vitória/Brasil)

**Other collaborators**: John Garcia, Hatef Shahmohamadi, Amanda Ndubuisi, Bhavadharini Selvakumar, Thilini Boteju, Lizandra Barrios Herrera, Alain Tchagang, Patrizia Calaminici, Andreas Koster, Mosayeb Naseri, Dennis Salahub, Venkataraman Thangadurai, and Karthik Shankar.


### The repository contains several subprojects which are sorted into following sections:

First notebook:
1. [Data reading and cleaning](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/01-Data-reading-and-cleaning) (including a custom made script to read a xlsx human made database file)

Second notebook:
2. [Feature Engineering and EDA (Exploratory data Analysis)](https://github.com/hostas/EDA-and-ML-for-Perovskites/tree/master/02-Feature-engineering
)
3. [Regression and hyperparameter tunning](https://github.com/hostas/EDA-and-ML-for-Perovskites/tree/master/03-Regression)
4. [PCA (Principal Component Analysis) and Wasserstein Autoencoders (WAE)](https://github.com/hostas/EDA-and-ML-for-Perovskites/tree/master/04-PCA-and-WAE)

I will strive to provide a documentation that explains the code and key takeaways of the project. Data reading and cleaning has been done in a single jupyter notebook (01). The rest of the project is in another notebook (02-05).



![Abstract](https://github.com/hostas/EDA-and-ML-for-Perovskites/blob/master/Graphics/Abstract.jpg)

**Figure 1**: Principal component analysis (PCA) is often used to visualize data and reduce the number of features that are used in machine learning. Here, I have started with 176 compounds which contained 28 different elements. This resulted in a weight composition descriptor with 28 different features (using site and chemical formula information). Using PCA this very sparse descriptor can be reduced and visualized. We can see that principal component 1 is highly correlated with the oxygen content which seems to explain sizeable portion of variance in the data, however after closer inspection it is only 10% of variance (or information) in the data. This is important in the further development of descriptors.
