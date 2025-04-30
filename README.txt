Creator: Sahar Shah and Brent Yoon

Packages Used
pandas
sklearn


Instructions to reproduce results:

The wine dataset is found at this link: https://archive.ics.uci.edu/ml/datasets/Wine+Quality

For implementing the models:

Random Forest:

Use sklearn.ensemble import RandomForestClassifier; use all default settings

SVM: 

Use sklearn.svm import SVC; use SVC(kernel='linear',probability=True)

KNN:

Use sklearn.neighbors import KNeighborsClassifier; use KNeighborsClassifier(n_neighbors=1,weights='distance',metric='euclidean')

For evaluations:

For cross validation use sklearn.model_selection import cross_validate
For the cv parameter of cross_validate() use kfold = StratifiedKFold(n_splits=10, shuffle=True, random_state=0) from sklearn.model_selection import StratifiedKFold

For percentage split use sklearn.model_selection import train_test_split with a 80% training set split and for metric use sklearn.metrics import precision_score, recall_score, f1_score, roc_auc_score, roc_curve

The StandardScaler and PCA are import and used from:
sklearn.preprocessing import StandardScaler
sklearn.decomposition import PCA

If you have access to the notebook by us just run it in sequential order to obtain results.\
