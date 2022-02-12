# Diagnosis-of-Lung-Cancer-Using-Machine-Learning

# Project 1 :
Dataset:  61
   S.No Patient Id  Age  Smokes  AreaQ  Alcohol  Result
0     1      pt001   35       3      5        4       1
1     2      pt002   27      20      2        5       1
2     3      pt003   30       0      5        2       0
3     4      pt004   28       0      8        1       0
4     5      pt005   68       4      5        6       1
![Figure_1](https://user-images.githubusercontent.com/88590516/153700948-2d1681df-a728-4afb-91d4-6b97c01d0ebc.png)
![Figure_2](https://user-images.githubusercontent.com/88590516/153700950-b2e8e98d-4b20-465d-bcd2-c8fb1f00daad.png)
![Figure_3](https://user-images.githubusercontent.com/88590516/153700951-f739a9e0-3665-428b-9d30-9ca2326562ca.png)
![Figure_4](https://user-images.githubusercontent.com/88590516/153700952-77475e9b-84f9-403d-8e08-a8869ddbaf49.png)

--------------------Using KNN Algorithm--------------------
6.928203230275509
[0 0 0 1 0 0 0 0 1 1 0 0 0]

Confusion Matrix: 
[[8 1]
 [2 2]]
In Confusion Matrix:----
Position 1.1 shows the patients that don't have Cancer, In this case = 8
Position 1.2 shows the patients that have higher risk of Cancer, In this case = 1
Position 2.1 shows the Incorrect value, In this case = 2
Position 2.2 shows the Correct number of patients that have Cancer, In this case = 2
F1 Score :  57.14285714285715
Accuracy :  76.92307692307693

---------------Using Decision Tree Algorithm---------------
Classification accuracy on train 95.83333333333334
Classification accuracy on test 69.23076923076923
