contains all sort of regression model.
 In total 6 model :
- Simple linear regression
- mulitple linear regression
- polynomial regression
- support vector regression (SVR), macam svm
- Decision tree
- Random Forest


===============================

Kelebihan dan Kekurangan tiap models:
==Linear Regression==
+ Boleh digunakan kat apa2 jenis dataset, bagi maklumat kepada kita pasal relevance ke tak sesuatu features tu
- Linear regression assumption yang terlampau general

==Polynomial Regression==
+ Boleh guna kat mana2 dataset.
+ Bagus untuk non linear(x^2, dari graph) problem
- perlu pilih degree polynomial yang betul supaya dapata bias/variance tradeoff yang bagus. kuasa berapa

==SVR==
+ Senang adapt, dan sangat sesuai untuk masalah linear/nonlinear 
- Wajib apply featur scaling, x diguna sangat, susah nak faham

==Decision Tree Regression==
+ Interpretability(terbaik),  tak perlu feature scaling, 
+ bagus untuk linear atau non-linear punya masalah
- kalau dataset kecil result accuracy dia jadi teruk dan senang overfit

==Random Forest Regression==
+ Power dan tepat,performance dia baik tak kisah lah masalah apa, termasuk non linear 
- tak ada interpretability, overfiting senang jadi, kene pilih berapa banyak tree nak pakai.

===============================
Regularization : Cara Nak handle overfitting
- Lasso
- Ridge Regression
- Elastic Net.

Semua guna approach berbeza dari sudut mathematics, but for the reason of solving overfitting.