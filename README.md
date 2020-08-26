# Breast-cancer-classification-project
Problem Statement-Breast cancer is an uncontrolled growth of breast cells. To better understand breast
cancer, it helps to understand how any cancer can develop.
Cancer occurs as a result of mutations, or abnormal changes, in the genes responsible
for regulating the growth of cells and keeping them healthy. The genes are in each
cell’s nucleus, which acts as the “control room” of each cell. Normally, the cells in our
bodies replace themselves through an orderly process of cell growth: healthy new cells
take over as old ones die out. But over time, mutations can “turn on” certain genes and
“turn off” others in a cell. That changed cell gains the ability to keep dividing without
control or order, producing more cells just like it and forming a tumor.
A tumor can be Benign (not dangerous to health) or Malignant (has the potential to be
dangerous). Benign tumors are not considered cancerous: their cells are close to
normal in appearance, they grow slowly, and they do not invade nearby tissues or
spread to other parts of the body. Malignant tumors are cancerous. Left unchecked,
malignant cells eventually can spread beyond the original tumor to other parts of the
body.
The term “Breast Cancer” refers to a malignant tumor that has developed from cells
in the breast. A sample of data is provided with medical conditions of different
patients, indicating whether their tumor is Benign(B) or Malignant(M). The objective is
to predict the outcome of the test with the help of Machine Learning.

Dataset- The training dataset is the data on which we will train our data, in order to be used in
future for new datasets on breast cancer. Ten real-valued features are computed for
each cell nucleus:
 radius (mean of distances from center to points on the perimeter)
 texture (standard deviation of gray-scale values)
 perimeter
 area
 smoothness (local variation in radius lengths)
 compactness (perimeter^2 / area - 1.0)
 concavity (severity of concave portions of the contour)
 concave points (number of concave portions of the contour)
 symmetry
 fractal dimension ("coastline approximation" - 1)
The mean, standard error and "worst" or largest (mean of the three largest values) of
these features were computed for each image, resulting in 30 features.
