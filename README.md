# ML-proj-1

This project focuses on the analysis of the census-income dataset,
which contains census information for individuals and their income
classification. The dataset includes 14 attributes, some of which have
missing values. The first task involves handling missing values using
appropriate techniques, such as imputation or removal.

The main objective of this project is to construct an optimal-sized
decision tree for predicting income class (>50K or <=50K) using the
census-income dataset. The construction of the decision tree will
involve applying the Reduced Error Pruning technique, which aims to
find the optimal balance between accuracy and complexity. To
evaluate the decision tree's performance, a graph depicting the
number of vertices (nodes) versus error will be plotted for the training,
validation, and testing datasets. In order to assess the robustness of
the decision tree model, the training and testing datasets will be
combined. Random selection will be used to allocate 67% of the data
points as the new training dataset, while the remaining points will be
used as the testing dataset. The decision tree will be built using the
same Reduced Error Pruning technique as before, and its
performance will be compared with the decision tree obtained using
the original split of the data.

To further explore classification performance, a Random Forest
classifier will be constructed using the combined training dataset. The
results of the Random Forest classifier will be compared with the
decision trees obtained in the previous steps to evaluate its
effectiveness in predicting income class.
