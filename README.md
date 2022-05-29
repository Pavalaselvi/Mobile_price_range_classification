# Mobile_price_range_classification

PROBLEM STATEMENT: Create a classification model to predict whether price range of
mobile based on certain specifications.

CONTEXT: An entrepreneur has started his own mobile company. He wants to give
tough fight to big companies like Apple, Samsung etc.
He does not know how to estimate price of mobiles his company creates. In this
competitive mobile phone market, one cannot simply assume things. To solve this
problem, he collects sales data of mobile phones of various companies.
He wants to find out some relation between features of a mobile phone (e.g., RAM,
Internal Memory etc) and its selling price. But he is not so good at Machine Learning.
So, he needs your help to solve this problem.
In this problem you do not have to predict actual price but a price range indicating
how high the price is

DETAILS OF FEATURES:
The columns are described as follows:
Dataset as 21 features and 2000 entries. The meanings of the features are given
below.
• battery_power: Total energy a battery can store in one time measured in mAh
• blue: Has bluetooth or not
• clock_speed: speed at which microprocessor executes instructions
• dual_sim: Has dual sim support or not
• fc: Front Camera mega pixels
• four_g: Has 4G or not
• int_memory: Internal Memory in Gigabytes
• m_dep: Mobile Depth in cm
• mobile_wt: Weight of mobile phone
• n_cores: Number of cores of processor
• pc: Primary Camera mega pixels
px_height: Pixel Resolution Height
• px_width: Pixel Resolution Width
• ram: Random Access Memory in Mega Bytes
• sc_h: Screen Height of mobile in cm
• sc_w: Screen Width of mobile in cm
• talk_time: longest time that a single battery charge will last when you are
• three_g: Has 3G or not
• touch_screen: Has touch screen or not
• wifi: Has wifi or not
• price_range: This is the target variable with value of 0(low cost), 1(medium cost),
2(high cost) and 3(very high cost).

BRIEF DESCRIPTION :
In this Project,I have coded in such a way that first handled the null values in the dataset and after removing it , splited the data into training and test data.Then applied the following models on the training dataset and generated the predicted value for the test dataset. a) Logistic Regression b) KNN Classification  c) SVM Classifier with linear and rbf kernel then predicted the price range for test data for the test data and computed the confusion matrix and classification report for each of these models and Finally Determining the Model with Best Accuracy.


