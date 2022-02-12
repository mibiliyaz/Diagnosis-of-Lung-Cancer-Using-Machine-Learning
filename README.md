# Diagnosis-of-Lung-Cancer-Using-Machine-Learning

# Project 1 : 
<p>
Dataset:  61 <br>
   <table>
      <th>
         <td>S.No.</td>
         <td>Patient Id</td>
         <td>Age</td>
         <td>Smokes</td>
         <td>AreaQ</td>
         <td>Alcohol</td>
         <td>Result</td>
      </th>
      <tr>
         <td>0</td>
         <td>1</td>
         <td>pt001</td>
         <td>35</td>
         <td>3</td>
         <td>5</td>
         <td>4</td>
         <td>1</td>
      </tr>
      <tr>
         <td>1</td>
         <td>2</td>
         <td>pt002</td>
         <td>27</td>
         <td>20</td>
         <td>2</td>
         <td>5</td>
         <td>1</td>
      </tr>
      <tr>
         <td>2</td>
         <td>3</td>
         <td>pt003</td>
         <td>30</td>
         <td>0</td>
         <td>5</td>
         <td>2</td>
         <td>0</td>
      </tr>
      <tr>
         <td>3</td>
         <td>4</td>
         <td>pt004</td>
         <td>28</td>
         <td>0</td>
         <td>8</td>
         <td>1</td>
         <td>0</td>
      </tr>
      <tr>
         <td>4</td>
         <td>5</td>
         <td>pt005</td>
         <td>68</td>
         <td>4</td>
         <td>5</td>
         <td>6</td>
         <td>1</td>
      </tr>
   </table>
 <br>
   
   
![Figure_1](https://user-images.githubusercontent.com/88590516/153700984-b6428e2d-f60e-48d5-b9c0-d0ceb0fb44e7.png)
![Figure_2](https://user-images.githubusercontent.com/88590516/153700991-d42a41fa-79a7-412d-b7b1-31e7291831f3.png)
![Figure_3](https://user-images.githubusercontent.com/88590516/153700992-d9e1b24a-7862-4559-ae4a-45fa2c890ed3.png)
![Figure_4](https://user-images.githubusercontent.com/88590516/153700995-4ba17f5b-c14e-4aa9-8ddc-f1fe2481aa61.png)

   
<br>
--------------------Using KNN Algorithm-------------------- <br>
6.928203230275509 <br>
[0 0 0 1 0 0 0 0 1 1 0 0 0]   <br>
   <br>
Confusion Matrix: <br>
[[8 1]   <br>
 [2 2]]   <br>
In Confusion Matrix:----   <br>
Position 1.1 shows the patients that don't have Cancer, In this case = 8   <br>
Position 1.2 shows the patients that have higher risk of Cancer, In this case = 1   <br>
Position 2.1 shows the Incorrect value, In this case = 2   <br>
Position 2.2 shows the Correct number of patients that have Cancer, In this case = 2   <br>
F1 Score :  57.14285714285715   <br>
Accuracy :  76.92307692307693   <br>
   <br>
---------------Using Decision Tree Algorithm---------------   <br>
Classification accuracy on train 95.83333333333334   <br>
Classification accuracy on test 69.23076923076923   <br>
</p>
