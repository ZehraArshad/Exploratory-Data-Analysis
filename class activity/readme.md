### 


#### Dataset Description

#### Country Wise Revenue Contribution

- Austrailia 🥇 1,137,367
- UK 🥈 1,051,792.0
- India 🥉1,045,800.0

#### Unique Products 

- 22

####
</br>

**Products and their transactions**

![alt text](image.png)

</br>

**Month-Year Contribution**

![alt text](image-1.png)

</br>

**Monthly Contributions**

![alt text](image-3.png)

## How to approach data for different models?

### KNN
- Standard Scaling
- Experiment with different K values

**when k=3** ⏬

![alt text](image-5.png)

<br/>

**when k=5** ⏬

![alt text](image-6.png)
</br>

**when k=7** ⏬

<br/>

![alt text](image-4.png)

<br/>

- We can conclude that we will need fix the input for better results


### Decision Tree

same pre-process as knn

</br>

![alt text](image-7.png)

- Its hard to figure out an improvment as features are not impacting results properly

**Results of corr between data and amount**

![alt text](image-8.png)

### Random Forest, LogReg

- All of them are showing accuracy no more than 50%
- This indicates that data is not good for predictions

### Kmeans

</br>

![alt text](image-9.png)

</br>


## Missed Arrows


- Not scaling returns same accuracy 
- changing threshold of amouunt from median to near mean (5000) doesn't make much difference
